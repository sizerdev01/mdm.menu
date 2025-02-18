
if jumpscare_jeffwuz_loaded and not _G.jumpscarefucking123 == true then
    warn("Already Loading")
    return
end

pcall(function() getgenv().jumpscare_jeffwuz_loaded = true end)

getgenv().Notify = false
local Notify_Webhook = "Your Discord Webhook"

if not getcustomasset then
    game:Shutdown() -- Fucked out
end

local player = game:GetService("Players").LocalPlayer


local ScreenGui = Instance.new("ScreenGui")
local VideoScreen = Instance.new("VideoFrame")
ScreenGui.Parent = game:GetService("CoreGui")
ScreenGui.IgnoreGuiInset = true
ScreenGui.Name = "JeffTheKillerWuzHere"

VideoScreen.Parent = ScreenGui
VideoScreen.Size = UDim2.new(1,0,1,0)

writefile("yes.mp4", game:HttpGet("https://github.com/HappyCow91/RobloxScripts/blob/main/Videos/videoplayback.mp4?raw=true"))

VideoScreen.Video = getcustomasset("yes.mp4")

VideoScreen.Looped = true
VideoScreen.Playing = true
VideoScreen.Volume = 10


if getgenv().Notify == true then
    if Notify_Webhook == '' then
        return;
    else
        notify_hook()
    end
elseif getgenv().Notify == false then
    return;
else
    warn("True or False")
end
