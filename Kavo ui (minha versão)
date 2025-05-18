local Kavo = {}

local tween = game:GetService("TweenService") local tweeninfo = TweenInfo.new local input = game:GetService("UserInputService") local run = game:GetService("RunService")

local Utility = {} local Objects = {}

function Utility:TweenObject(obj, properties, duration, ...) tween:Create(obj, tweeninfo(duration, ...), properties):Play() end

local themes = { SchemeColor = Color3.fromRGB(74, 99, 135), Background = Color3.fromRGB(36, 37, 43), Header = Color3.fromRGB(28, 29, 34), TextColor = Color3.fromRGB(255,255,255), ElementColor = Color3.fromRGB(45, 45, 49) } local themeStyles = { DarkTheme = { SchemeColor = Color3.fromRGB(64, 64, 64), Background = Color3.fromRGB(0, 0, 0), Header = Color3.fromRGB(0, 0, 0), TextColor = Color3.fromRGB(255,255,255), ElementColor = Color3.fromRGB(20, 20, 20) }, LightTheme = { SchemeColor = Color3.fromRGB(150, 150, 150), Background = Color3.fromRGB(255,255,255), Header = Color3.fromRGB(200, 200, 200), TextColor = Color3.fromRGB(0,0,0), ElementColor = Color3.fromRGB(224, 224, 224) }, BloodTheme = { SchemeColor = Color3.fromRGB(227, 27, 27), Background = Color3.fromRGB(10, 10, 10), Header = Color3.fromRGB(5, 5, 5), TextColor = Color3.fromRGB(255,255,255), ElementColor = Color3.fromRGB(20, 20, 20) }, GrapeTheme = { SchemeColor = Color3.fromRGB(166, 71, 214), Background = Color3.fromRGB(64, 50, 71), Header = Color3.fromRGB(36, 28, 41), TextColor = Color3.fromRGB(255,255,255), ElementColor = Color3.fromRGB(74, 58, 84
