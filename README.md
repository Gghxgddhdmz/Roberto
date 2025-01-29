local player = game.Players.LocalPlayer
local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()
local Window = OrionLib:MakeWindow({Name = "script ROBERTO part 2", HidePremium = false, SaveConfig = true, ConfigFolder = "OrionTest"})

--[[
Name = <string> - The name of the UI.
HidePremium = <bool> - Whether or not the user details shows Premium status or not.
SaveConfig = <bool> - Toggles the config saving in the UI.
ConfigFolder = <string> - The name of the folder where the configs are saved.
IntroEnabled = <bool> - Whether or not to show the intro animation.
IntroText = <string> - Text to show in the intro animation.
IntroIcon = <string> - URL to the image you want to use in the intro animation.
Icon = <string> - URL to the image you want displayed on the window.
CloseCallback = <function> - Function to execute when the window is closed.
]]


local Tab = Window:MakeTab({
    Name = "سكربتات هبد بس تفيدكم",
    Icon = "rbxassetid://4483345998",
    PremiumOnly = false
})
local player = game.Players.LocalPlayer.Character
pl = game.Players.LocalPlayer
t = true
local fps = setfpscap
local L7N = 120

local Ha = Health 
local kmodh = 0


--[[
Name = <string> - The name of the tab.
Icon = <string> - The icon of the tab.
PremiumOnly = <bool> - Makes the tab accessible to Sirus Premium users only.
]]

local Section = Tab:AddSection({
    Name =  " كسمك باسل يامهزله هاذا سكربت لعيون امىك يزنوىءه اسم حساب باسل بروب M_K162 "
})

--[[
Name = <string> - The name of the section.
]]

OrionLib:MakeNotification({
    Name = "اهلا بكم بسكربت لحن بارت 2",
    Content = "Notification content... what will it say??",
    Image = "rbxassetid://4483345998",
    Time = 5
})

--[[
Title = <string> - The title of the notification.
Content = <string> - The content of the notification.
Image = <string> - The icon of the notification.
Time = <number> - The duration of the notfication.
]]

Tab:AddButton({
    Name = "تعديل FPS اول ما تضغظ عليه يصير فريماتك 120",
    Callback = function()
             fps(L7N)
      end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The functi
]]

Tab:AddButton({
	Name = "سكربت طيران ",
	Callback = function()
        loadstring("\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\40\39\104\116\116\112\115\58\47\47\103\105\115\116\46\103\105\116\104\117\98\117\115\101\114\99\111\110\116\101\110\116\46\99\111\109\47\109\101\111\122\111\110\101\89\84\47\98\102\48\51\55\100\102\102\57\102\48\97\55\48\48\49\55\51\48\52\100\100\100\54\55\102\100\99\100\51\55\48\47\114\97\119\47\101\49\52\101\55\52\102\52\50\53\98\48\54\48\100\102\53\50\51\51\52\51\99\102\51\48\98\55\56\55\48\55\52\101\98\51\99\53\100\50\47\97\114\99\101\117\115\37\50\53\50\48\120\37\50\53\50\48\102\108\121\37\50\53\50\48\50\37\50\53\50\48\111\98\102\108\117\99\97\116\111\114\39\41\44\116\114\117\101\41\41\40\41\10\10")()
  	end    
})

Tab:AddButton({
	Name = "سكربت طيران العادي 2",
	Callback = function()
		loadstring(game:HttpGet("https://pastebin.com/raw/TinK2zh7"))()
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "قتل نفسك ",
	Callback = function()
        player.Humanoid.Health = kmodh
  	end    
})
Tab:AddSlider({
    Name = "تحكم في سرعة لاعب",
    Min = 1,
    Max = 850,
    Default = 85,
    Color = Color3.fromRGB(255,255,255),
    Increment = 1,
    ValueName = "bananas",
    Callback = function(speed)
        player.Humanoid.WalkSpeed = (speed)
    end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "سكربت R6",
	Callback = function()
        loadstring(game:HttpGet(('https://raw.githubusercontent.com/Imagnir/r6_anims_for_r15/main/r6_anims.lua'),true))()
  	end    
})

Tab:AddButton({
	Name = "سكربت ESP",
	Callback = function()
		loadstring(game:HttpGet("https://raw.githubusercontent.com/tbao143/thaibao/main/TbaoHubEsp"))()
  	end    
})



--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "سكربت rtx",
	Callback = function()
        loadstring(game:HttpGet("https://pastebin.com/raw/CHT5hzTB"))()
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "سكربت قوست مب الاصلي!",
	Callback = function()
        loadstring(game:HttpGet('https://pastebin.com/raw/2jbkJhRD'))(
        )
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]


Tab:AddButton({
	Name = "سكربت قوست الاصلي",
	Callback = function()
        loadstring(game:HttpGet('https://raw.githubusercontent.com/GhostPlayer352/Test4/main/GhostHub'))()
  	end    
})

Tab:AddButton({
	Name = "سكربت تحكم بنفسك وفيه اشياء",
	Callback = function()
		loadstring(game:HttpGet("https://pastebin.com/raw/cUP5CjK5", true))()
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]



--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "سكربتي القديم!",
	Callback = function()
        loadstring(game:HttpGet('https://pastebin.com/raw/aLnerzDU'))()
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]


Tab:AddButton({
	Name = " سكربت سبراني مفتاح سكربت sabraniun",
	Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/emb5/Dance/main/Hub"))()
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

local Tab = Window:MakeTab({
	Name = "سكربتات AFK",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

--[[
Name = <string> - The name of the tab.
Icon = <string> - The icon of the tab.
PremiumOnly = <bool> - Makes the tab accessible to Sirus Premium users only.
]]


Tab:AddButton({
	Name = "سكربت صمله 1!",
	Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/evxncodes/mainroblox/main/anti-afk", true))()
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "سكربت صمله 2!",
	Callback = function()
        loadstring(game:HttpGet(('https://raw.githubusercontent.com/RTrade/Voidz/main/AntiAFK.lua'),true))()
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "سكربت صمله 3",
	Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/ArgetnarYT/scripts/main/AntiAfk2.lua"))()
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "سكربت صمله 4!",
	Callback = function()
        wait(0.5)local ba=Instance.new("ScreenGui")
        local ca=Instance.new("TextLabel")local da=Instance.new("Frame")
        local _b=Instance.new("TextLabel")local ab=Instance.new("TextLabel")ba.Parent=game.CoreGui
        ba.ZIndexBehavior=Enum.ZIndexBehavior.Sibling;ca.Parent=ba;ca.Active=true
        ca.BackgroundColor3=Color3.new(0.176471,0.176471,0.176471)ca.Draggable=true
        ca.Position=UDim2.new(0.698610067,0,0.098096624,0)ca.Size=UDim2.new(0,370,0,52)
        ca.Font=Enum.Font.SourceSansSemibold;ca.Text="Anti AFK Script"ca.TextColor3=Color3.new(0,1,1)
        ca.TextSize=22;da.Parent=ca
        da.BackgroundColor3=Color3.new(0.196078,0.196078,0.196078)da.Position=UDim2.new(0,0,1.0192306,0)
        da.Size=UDim2.new(0,370,0,107)_b.Parent=da
        _b.BackgroundColor3=Color3.new(0.176471,0.176471,0.176471)_b.Position=UDim2.new(0,0,0.800455689,0)
        _b.Size=UDim2.new(0,370,0,21)_b.Font=Enum.Font.Arial;_b.Text="made by no one "
        _b.TextColor3=Color3.new(0,1,1)_b.TextSize=20;ab.Parent=da
        ab.BackgroundColor3=Color3.new(0.176471,0.176471,0.176471)ab.Position=UDim2.new(0,0,0.158377,0)
        ab.Size=UDim2.new(0,370,0,44)ab.Font=Enum.Font.ArialBold;ab.Text="Status: Active"
        ab.TextColor3=Color3.new(0,1,1)ab.TextSize=20;local bb=game:service'VirtualUser'
        game:service'Players'.LocalPlayer.Idled:connect(function()
        bb:CaptureController()bb:ClickButton2(Vector2.new())
        ab.Text="Roblox tried to kick u but i kicked him instead"wait(2)ab.Text="Status : Active"end)
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "سكربت صمله 5!",
	Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/batusz/main/roblox/__Anti__Afk__Script__", true))()
  	end    
})

		--[[
		Name = <string> - The name of the button.
		Callback = <function> - The function of the button.
		]]



--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "سكربت صمله 6",
	Callback = function()
		loadstring(game:HttpGet("https://pastebin.com/raw/SZkHcmKR"))()
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]


local Tab = Window:MakeTab({
	Name = "سكربتات ادمن لعيون كسم باسل",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

--[[
Name = <string> - The name of the tab.
Icon = <string> - The icon of the tab.
PremiumOnly = <bool> - Makes the tab accessible to Sirus Premium users only.
]]


local Section = Tab:AddSection({
	Name = "والله لاكون كابوسك يباسل لقبه حمني اسمه بروب M_K162"
})

--[[
Name = <string> - The name of the section.
]]

Tab:AddButton({
	Name = "سكربت انفنتي!",
	Callback = function()
        loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]


Tab:AddButton({
	Name = "سكربت ادمن NA",
	Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/FilteringEnabled/NamelessAdmin/main/Source"))();
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "سكربت ادمن LOGS نقطه بلشات زي .FLY",
	Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/BloodyBurns/Hex/main/Iv%20Admin%20v3.lua"))()
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]


Tab:AddButton({
	Name = "سكربت نادر يلي عليه فيس ضحكه!",
	Callback = function()
        loadstring(game:HttpGet('https://raw.githubusercontent.com/leg1337/legadmv2/main/legadminv2.lua'))()
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "سكربت تقريبا يعني كلشي موجود فيه",
	Callback = function()
        loadstring(game:HttpGet("https://scriptblox.com/raw/Universal-Script-Sky-Hub-10706"))()
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "سكربت تحكم في لاعبك",
	Callback = function()
        loadstring(game:HttpGet('https://raw.githubusercontent.com/anyahubs/swordgame/main/anya.lua'))()
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]


local Tab = Window:MakeTab({
	Name = "سكربتات بروكن هافن",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

--[[
Name = <string> - The name of the tab.
Icon = <string> - The icon of the tab.
PremiumOnly = <bool> - Makes the tab accessible to Sirus Premium users only.
]]

Tab:AddButton({
	Name = "سكربت بروكن هافن فيه هيلديس ورجل وكلشي تبيه 1",
	Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/JulHubz/JulHub/main/JulHub"))()
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "سكربت ريدز مميزات كثيره تفعل بسفينه واي شي تبيه",
	Callback = function()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "سكربت رقصات!",
	Callback = function()
        loadstring(game:HttpGet("https://scriptblox.com/raw/Brookhaven-RP-all-emotes-6849"))()
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

local Tab = Window:MakeTab({
	Name = "الوصف كلام مهم",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

--[[
Name = <string> - The name of the tab.
Icon = <string> - The icon of the tab.
PremiumOnly = <bool> - Makes the tab accessible to Sirus Premium users only.
]]

local Section = Tab:AddSection({
	Name = "طيب يشباب ذا سكربت صنعته عشان باسل اوريكم كيف بهينه بس فقط لا اكثر وا الحين بعلن اعتزالي بعد الغدرات يلي جتني بس يلا عوافي ومتاكد يباسل انك بتشوف كلامي بس والله ثم والله ماتعدي مني دامك طحت على يدي اسمك بروب M_K162 وبس والله اعلن اعتزالي وبتوفيق للجميع"
})

--[[
Name = <string> - The name of the section.
]]

local Section = Tab:AddSection({
	Name = "يلا يلشحاد كسمك يجديد باسل زنوه ههه رد على سكربتي لو قدرت"
})

--[[
Name = <string> - The name of the section.
]]

local Section = Tab:AddSection({
	Name = "بتوفيق لكم جميعا لو تواجهك مشاكل تعال تيك l73mo"
})

--[[
Name = <string> - The name of the section.
]]
