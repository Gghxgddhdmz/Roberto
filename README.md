local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()

local Window = OrionLib:MakeWindow({Name = "IRAq CLANS", HidePremium = false, SaveConfig = true, ConfigFolder = "السكربت من صنع شاتاي و سلندر كلانPS5"})

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
	Name = "Brookhaven RP",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

--[[
Name = <string> - The name of the tab.
Icon = <string> - The icon of the tab.
PremiumOnly = <bool> - Makes the tab accessible to Sirus Premium users only.
]]

local Section = Tab:AddSection({
	Name = "السكربت من صنع سلندر شاتاي كلانءPS5"
})

--[[
Name = <string> - The name of the section.
]]

Tab:AddButton({
	Name = "Redz hub",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/REDzHUB/REDzHUB/main/REDzHUB"))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "Sender  الجديد X",
	Callback = function() loadstring(game:HttpGet('https://raw.githubusercontent.com/kigredns/SanderXV4.2.2/refs/heads/main/New.lua'))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "راقدول!",
Callback=
function()loadstring(game:HttpGet("https://raw.githubusercontent.com/H20CalibreYT/SystemBroken/main/script"))()

      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "R4D!",
	Callback = function()loadstring(game:HttpGet('https://raw.githubusercontent.com/M1ZZ001/BrookhavenR4D/main/Brookhaven%20R4D%20Script'))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "رحمه اجنبي!",
	Callback = function()loadstring(game:HttpGet('https://raw.githubusercontent.com/n0kc/AtomicHub/main/Script.lua'))() 
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "رحمه عربي!",
	Callback = function()loadstring(game:HttpGet('https://raw.githubusercontent.com/Ndora1/Ndora1/main/Nokia%20Hub.lua'))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "منع تخريب!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/hasan08122020108181818/devronaldo/main/antithsuireboe.lua"))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "Infinite Yiled!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/Infinite-Store/Infinite-Store/main/main.lua"))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "صمله صنع شاتاي!",
	Callback = function() loadstring(game:HttpGet("https://pastebin.com/raw/8Ksr7kq5"))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "TP Tool!",
	Callback = function()loadstring(game:HttpGet("https://scriptblox.com/raw/Brookhaven-RP-Mikeexc-Tptool-V1-10960"))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "1x1x1x1 سكربت!",
	Callback = function()loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-1x1x1x1-blue-gui-ANOTHER-VERSION-OF-1X1X1X1-GUI-PLS-NO-HATE-14099"))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "Rips hub!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/CasperFlyModz/discord.gg-rips/main/FPSBooster.lua"))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "رقصات!",
	Callback = function()loadstring(game:HttpGet("https://scriptblox.com/raw/Brookhaven-RP-all-emotes-6849"))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "سكربت طيران من صنع شاتاي!",
	Callback = function()loadstring(game:HttpGet("https://pastebin.com/raw/MzU5rJ7S"))()

  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "ARAB SCR!",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/ARAB-SCR/ARAB-SCR/main/AR"))()

      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

local Tab = Window:MakeTab({
	Name = "Blox fort",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

--[[
Name = <string> - The name of the tab.
Icon = <string> - The icon of the tab.
PremiumOnly = <bool> - Makes the tab accessible to Sirus Premium users only.
]]

local Section = Tab:AddSection({
	Name = "السكربت من صنع سلندر شاتاي كلان PS5"
})

Tab:AddButton({
	Name = "Redzhub!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/REDzHUB/BloxFruits/main/redz9999"))()

      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "Vector Hub!",
	Callback = function()loadstring(game:HttpGet("https://pastebin.com/raw/4QtEAA6g"))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "zia hub!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/AnDepZaiHub/AnDepZaiHubBeta/main/AnDepZaiHubBeta.lua"))()

      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "تجميع صناديق!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/ahmadsgamer2/Zekrom-Hub-X/main/Zekrom-Hub-X-exe", true))()

      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "AnSit hub!",
	Callback = function()loadstring(game:HttpGet(("https://raw.githubusercontent.com/AnSitDz/AnSitHub/main/BloxFruits"),true))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "systen blox!",
	Callback = function()loadstring(game:HttpGet("https://scriptblox.com/raw/Universal-Script-System-hub-V2-13161"))()
 
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "ايم بوت!",
	Callback = function()loadstring(game:HttpGet"https://raw.githubusercontent.com/Basicallyy/Basicallyy/main/MinGamingV4.lua")()


      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "Speed hub!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/AhmadV99/Speed-Hub-X/main/Speed%20Hub%20X.lua"))()

      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "Radon hub!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/x2-Neptune/RadonHub/main/Script.lua"))()

      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "سكربت اسطوري!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/Basicallyybeta/main/main/Mingaming.lua"))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "ray hub!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/SeaBabyBF/X-rayse/main/X-RayHub"))()
 
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "Ver hub جديد!",
	Callback = function()loadstring(game:HttpGet"https://raw.githubusercontent.com/PNguyen0199/Script/main/Fai-Fao-Ver2.lua")()

      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "طيران!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/pro1x1/Fly-scrip/main/Fly%20scrip"))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

local Tab = Window:MakeTab({
	Name = "mm2",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

--[[
Name = <string> - The name of the tab.
Icon = <string> - The icon of the tab.
PremiumOnly = <bool> - Makes the tab accessible to Sirus Premium users only.
]]

local Section = Tab:AddSection({
	Name = "السكربت من صنع سلندر شاتاي كلانPS5"
})

Tab:AddButton({
	Name = "عدم موت!",
	Callback = function()loadstring(game:HttpGet("https://pastebin.com/raw/4izZLAmH"))()

      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "ايم بوت!",
	Callback = function()loadstring(game:HttpGet('https://pastebin.com/raw/71YWvURH'))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "فيه كل شيئ!",
	Callback = function()loadstring(game:HttpGet('https://raw.githubusercontent.com/scriptemt/CE-Technologies/main/script', true))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "Ruby hub!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/Deni210/murdersvssherrifsduels/main/rubyhub", true))()

      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "VR7!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/VR7ss/VR7/main/MM2"))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "s_o_a_b!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/s-o-a-b/nexus/main/loadstring"))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "جديد!",
	Callback = function()loadstring(game:HttpGet("https://pastebin.com/raw/UTuWzEcZ"))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "اسطوري!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/Au0yX/Community/main/XhubMM2"))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "Xhub!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/Au0yX/Community/main/XhubMM2"))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "Kinh!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/LOLking123456/eggs/main/MM2"))()

      	
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "xking!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/Soxpcoxod/Tt/main/Kigogi"))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "مره اسطوري!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/Joystickplays/psychic-octo-invention/main/yarhm.lua", false))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "ثاني من صنع VR7!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/VR7ss/VR7/main/MM2"))()

      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "جديد mm2!",
	Callback = function()loadstring(game:HttpGet('https://pastebin.com/raw/PGCZSiAY'))()
 
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

local Tab = Window:MakeTab({
	Name = "Balde bal ",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

--[[
Name = <string> - The name of the tab.
Icon = <string> - The icon of the tab.
PremiumOnly = <bool> - Makes the tab accessible to Sirus Premium users only.
]]

local Section = Tab:AddSection({
	Name = "السكربت من صنع سلندر شاتاي كلانPS5"
})


Tab:AddButton({
	Name = "Baldebal1!",
	Callback = function()loadstring(game:HttpGet('https://pastebin.com/raw/71YWvURH'))()
 
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "Baldebal2!",
	Callback = function()loadstring(game:HttpGet('https://pastebin.com/raw/71YWvURH'))()
 
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "Baldebal3!",
	Callback = function()loadstring(game:HttpGet('https://raw.githubusercontent.com/scriptemt/CE-Technologies/main/script', true))()

      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "Baldebal4!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/Deni210/murdersvssherrifsduels/main/rubyhub", true))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "Baldebal5!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/VR7ss/VR7/main/MM2"))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "Baldebal6!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/s-o-a-b/nexus/main/loadstring"))()
 
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "Baldebal7!",
	Callback = function()loadstring(game:HttpGet("https://pastebin.com/raw/UTuWzEcZ"))()

      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "Baldebal8!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/Au0yX/Community/main/XhubMM2"))()

      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "Baldebal7!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/Au0yX/Community/main/XhubMM2"))()

      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "Baldebal10!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/LOLking123456/eggs/main/MM2"))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "Baldebal11!",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Soxpcoxod/Tt/main/Kigogi"))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "Baldebal12!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/Joystickplays/psychic-octo-invention/main/yarhm.lua", false))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "Baldebal13!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/VR7ss/VR7/main/MM2"))()

      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

local Tab = Window:MakeTab({
	Name = "Adopt me ",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

--[[
Name = <string> - The name of the tab.
Icon = <string> - The icon of the tab.
PremiumOnly = <bool> - Makes the tab accessible to Sirus Premium users only.
]]

local Section = Tab:AddSection({
	Name = "السكربت من صنع سلندر شاتاي كلانPS5"
})

Tab:AddButton({
	Name = "Freehub!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/FreeeScripts/FREEHub/main/Loader", true))()

      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "YTPLhub!",
	Callback = function()loadstring(game:HttpGet('https://gitfront.io/r/ReQiuYTPL/wFUydaK74uGx/hub/raw/ReQiuYTPLHub.lua'))()
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "ادوبت مي!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/Dan..."))();
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "مره قوي!",
	Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/Ultra-Scripts/AdoptmeScript/main/AdoptmeScript/1XED629-adopt-me.lua"))()

      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "قديم!",
	Callback = function()loadstring(game:HttpGet("https://pastebin.com/raw/wx7J90FD"))();

      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "اسطوري!",
	Callback = function()loadstring(game:HttpGet('https://raw.githubusercontent.com/Penguin285/AdoptMe/main/tradeScam'))()
 
      		
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "Dope pet!",
	Callback = function()
loadstring(gam
