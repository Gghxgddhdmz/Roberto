local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()
local Window = OrionLib:MakeWindow({Name = "ROBERTO", HidePremium = false, SaveConfig = true, ConfigFolder = "ABOM7MD"})

local Tab = Window:MakeTab({
	Name = "سكربت تحتاجه",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

local Section = Tab:AddSection({
	Name = "كسمك يامتعب ياقحبه"
})

Tab:AddButton({
	Name = "انفنتي",
	Callback = function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
  	end    
}) 

Tab:AddButton({
	Name = "FLY 1",
	Callback = function()
--ARCEUS X FLY V2 SCRIPT
loadstring("\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\40\39\104\116\116\112\115\58\47\47\103\105\115\116\46\103\105\116\104\117\98\117\115\101\114\99\111\110\116\101\110\116\46\99\111\109\47\109\101\111\122\111\110\101\89\84\47\98\102\48\51\55\100\102\102\57\102\48\97\55\48\48\49\55\51\48\52\100\100\100\54\55\102\100\99\100\51\55\48\47\114\97\119\47\101\49\52\101\55\52\102\52\50\53\98\48\54\48\100\102\53\50\51\51\52\51\99\102\51\48\98\55\56\55\48\55\52\101\98\51\99\53\100\50\47\97\114\99\101\117\115\37\50\53\50\48\120\37\50\53\50\48\102\108\121\37\50\53\50\48\50\37\50\53\50\48\111\98\102\108\117\99\97\116\111\114\39\41\44\116\114\117\101\41\41\40\41\10\10")()
  	end    
})

Tab:AddButton({
	Name = "FLY 2",
	Callback = function()
	loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Fly-Gui-Modded-10763"))()
  	end    
})


Tab:AddButton({
	Name = "ادمن",
	Callback = function()

  	end    
})

Tab:AddButton({
	Name = "تخفيف لاق",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/CasperFlyModz/discord.gg-rips/main/FPSBooster.lua"))()
  	end    
})

Tab:AddButton({
	Name = "يرفع الFPS",
	Callback = function()
local gui = Instance.new("ScreenGui")
gui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")

local frame = Instance.new("Frame")
frame.Size = UDim2.new(0.2, 0, 0.3, 0)
frame.BackgroundColor3 = Color3.fromRGB(0, 0, 100)
frame.Active = true
frame.Draggable = true
frame.Position = UDim2.new(0.5, 0, 0.5, 0)
frame.Parent = gui

local madeByText = Instance.new("TextLabel")
madeByText.Size = UDim2.new(1, 0, 0.1, 0)
madeByText.Position = UDim2.new(0, 0, 0.9, 0)
madeByText.Text = "Made by gta5gmplyofficial"
madeByText.TextColor3 = Color3.fromRGB(255, 255, 255)
madeByText.BackgroundTransparency = 1
madeByText.FontSize = Enum.FontSize.Size18
madeByText.Parent = frame

local pilihText = Instance.new("TextLabel")
pilihText.Size = UDim2.new(1, 0, 0.2, 0)
pilihText.Position = UDim2.new(0, 0, 0, 0)
pilihText.Text = "Pilih FPS"
pilihText.TextColor3 = Color3.fromRGB(255, 255, 255)
pilihText.FontSize = Enum.FontSize.Size24
pilihText.Parent = frame

local options = {"60 FPS", "120 FPS", "255 FPS", "Max FPS"}
for i, option in ipairs(options) do
    local fpsButton = Instance.new("TextButton")
    fpsButton.Name = option
    fpsButton.Size = UDim2.new(1, 0, 0.2, 0)
    fpsButton.Position = UDim2.new(0, 0, (i-1) * 0.2, 0)
    fpsButton.Text = option
    fpsButton.Parent = frame

    fpsButton.MouseButton1Click:Connect(function()
        if option == "Max FPS" then
            fpsButton.TextColor3 = Color3.fromRGB(0, 255, 0)
        end
        local notification = Instance.new("TextLabel")
        notification.Size = UDim2.new(0.3, 0, 0.1, 0)
        notification.Position = UDim2.new(0.5, 0, 0.8, 0)
        notification.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
        notification.TextColor3 = Color3.fromRGB(0, 0, 0)
        notification.Text = "Fps selected successfully"
        notification.Parent = gui
        wait(2)
        notification:Destroy()
    end)
end
  	end    
})

Tab:AddButton({
	Name = "يعدم لك اللاق",
	Callback = function()
loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-antilag-15462"))()
  	end    
})

Tab:AddButton({
	Name = "سكاي هيب",
	Callback = function()
loadstring(game:HttpGet("https://scriptblox.com/raw/Universal-Script-Sky-Hub-10706"))()
  	end    
})

Tab:AddButton({
	Name = "سكربت Ghost",
	Callback = function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/GhostPlayer352/Test4/main/GhostHub'))()
  	end    
})

local Tab = Window:MakeTab({
	Name = "سكربتات صمله",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

local Section = Tab:AddSection({
	Name = "كسختك يامضحكه يامتعب هههههههه" 
})

Tab:AddButton({
	Name = "صمله1",
	Callback = function()
wait(0.5)local ba=Instance.new("ScreenGui")
local ca=Instance.new("TextLabel")local da=Instance.new("Frame")
local _b=Instance.new("TextLabel")local ab=Instance.new("TextLabel")ba.Parent=game.CoreGui
ba.ZIndexBehavior=Enum.ZIndexBehavior.Sibling;ca.Parent=ba;ca.Active=true
ca.BackgroundColor3=Color3.new(0.176471,0.176471,0.176471)ca.Draggable=true
ca.Position=UDim2.new(0.698610067,0,0.098096624,0)ca.Size=UDim2.new(0,370,0,52)
ca.Font=Enum.Font.SourceSansSemibold;ca.Text="ولكك كسمكككك يامتعب يامصخره يخو القحبه نزل سكربت عليك وعلى كسمك يبن الزنوه يامستجد"ca.TextColor3=Color3.new(0,1,1)
ca.TextSize=22;da.Parent=ca
da.BackgroundColor3=Color3.new(0.196078,0.196078,0.196078)da.Position=UDim2.new(0,0,1.0192306,0)
da.Size=UDim2.new(0,370,0,107)_b.Parent=da
_b.BackgroundColor3=Color3.new(0.176471,0.176471,0.176471)_b.Position=UDim2.new(0,0,0.800455689,0)
_b.Size=UDim2.new(0,370,0,21)_b.Font=Enum.Font.Arial;_b.Text="made by ur mom"
_b.TextColor3=Color3.new(0,1,1)_b.TextSize=20;ab.Parent=da
ab.BackgroundColor3=Color3.new(0.176471,0.176471,0.176471)ab.Position=UDim2.new(0,0,0.158377,0)
ab.Size=UDim2.new(0,370,0,44)ab.Font=Enum.Font.ArialBold;ab.Text= "Status: Active"
ab.TextColor3=Color3.new(0,1,1)ab.TextSize=20;local bb=game:service'VirtualUser'
game:service'Players'.LocalPlayer.Idled:connect(function()
bb:CaptureController()bb:ClickButton2(Vector2.new())
ab.Text="Roblox tried to kick u but i kicked him instead"wait(2)ab.Text="St
