# roblox-autotapper
this is only for clicker simulator. I will be making other autoGrinding for other games soon.


-- select the following code below, and execute it with sypanpse X into Roblox
-- Remember, make it a lua file, example: README.lua

_G.autoTap = true;
while _G.autoTap = true do
remotePath = game:GameService("replicated storage").Aero.AeroRemoteServices.ClickService.Click:FireServer(unpack(args))
spawn(function()
while autoTap == true do
local args = {[1] = 1}
remotePath.ClickService.Click:FireServer(unpack(args))
    end
  end)




--this is beta, so if there is a bug pls let me know!
