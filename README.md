local ScreenGui = Instance.new("ScreenGui")
local OpenMain = Instance.new("Frame")
local OpenB = Instance.new("TextButton")
local GUI = Instance.new("Frame")
local TeleportScroll = Instance.new("ScrollingFrame")
local SpawnTele = Instance.new("TextButton")
local WoodRUSTele = Instance.new("TextButton")
local FurnishingTele = Instance.new("TextButton")
local CarsTele = Instance.new("TextButton")
local LinksStoreTele = Instance.new("TextButton")
local BobsShack = Instance.new("TextButton")
local FineArtTele = Instance.new("TextButton")
local SwampTele = Instance.new("TextButton")
local PalmsTele = Instance.new("TextButton")
local CaveTele = Instance.new("TextButton")
local YellowWoodTele = Instance.new("TextButton")
local Volcano = Instance.new("TextButton")
local IceTreeTele = Instance.new("TextButton")
local EndTimesTele = Instance.new("TextButton")
local Den = Instance.new("TextButton")
local StrangeMan = Instance.new("TextButton")
local SkiiLodge = Instance.new("TextButton")
local GodAxeB = Instance.new("TextButton")
local MaxSpeedB = Instance.new("TextButton")
local Credits = Instance.new("TextLabel")
local TeleportWoodB = Instance.new("TextButton")
local ImageButton = Instance.new("ImageButton")
local TeleportsText = Instance.new("TextLabel")
local FlyB = Instance.new("TextButton")
local Logo = Instance.new("ImageButton")
local Frame = Instance.new("Frame")
local Frame_2 = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local TextLabel_2 = Instance.new("TextLabel")
local TextLabel_3 = Instance.new("TextLabel")
local NoClipB = Instance.new("TextButton")
local CloseGUI = Instance.new("TextButton")
local PlayerTeleportB = Instance.new("TextButton")
local TeleportPlayerGUI = Instance.new("Frame")
local Player6B = Instance.new("TextButton")
local Player5B = Instance.new("TextButton")
local Player3B = Instance.new("TextButton")
local Player2B = Instance.new("TextButton")
local Player1B = Instance.new("TextButton")
local PlayerSelectScreen = Instance.new("TextLabel")
local Player4B = Instance.new("TextButton")
local boarder = Instance.new("Frame")
local boarder_2 = Instance.new("Frame")
local boarder_3 = Instance.new("Frame")
local TPPlayerB = Instance.new("TextButton")
local CloseTeleports = Instance.new("TextButton")
--Properties:
ScreenGui.Parent = game.CoreGui

OpenMain.Name = "OpenMain"
OpenMain.Parent = ScreenGui
OpenMain.BackgroundColor3 = Color3.new(1, 1, 1)
OpenMain.Position = UDim2.new(-0.0125000011, 0, 0.541425824, 0)
OpenMain.Size = UDim2.new(0, 131, 0, 31)
OpenMain.Style = Enum.FrameStyle.DropShadow

OpenB.Name = "OpenB"
OpenB.Parent = OpenMain
OpenB.BackgroundColor3 = Color3.new(0.85098, 0.721569, 1)
OpenB.BorderColor3 = Color3.new(0.521569, 0.368627, 0.541176)
OpenB.BorderSizePixel = 2
OpenB.Position = UDim2.new(0.00763358781, 0, -0.0257318616, 0)
OpenB.Size = UDim2.new(0, 113, 0, 16)
OpenB.Font = Enum.Font.Garamond
OpenB.Text = "Open GUI"
OpenB.TextColor3 = Color3.new(0, 0, 0)
OpenB.TextSize = 14
OpenB.MouseButton1Down:connect(function()
GUI.Visible=true
OpenMain.Visible=false
end)

GUI.Name = "GUI"
GUI.Parent = ScreenGui
GUI.BackgroundColor3 = Color3.new(0.909804, 0.843137, 1)
GUI.Position = UDim2.new(-5.58793545e-08, 0, 0.134874716, 0)
GUI.Size = UDim2.new(0, 272, 0, 378)
GUI.Visible = false
GUI.Style = Enum.FrameStyle.DropShadow
GUI.Active=true
GUI.Draggable=true

TeleportScroll.Name = "Teleport Scroll"
TeleportScroll.Parent = GUI
TeleportScroll.BackgroundColor3 = Color3.new(0.85098, 0.721569, 1)
TeleportScroll.BorderColor3 = Color3.new(0.419608, 0.2, 0.427451)
TeleportScroll.BorderSizePixel = 3
TeleportScroll.Position = UDim2.new(0.351145029, 0, 0.342203557, 0)
TeleportScroll.Size = UDim2.new(0, 155, 0, 216)

SpawnTele.Name = "SpawnTele"
SpawnTele.Parent = TeleportScroll
SpawnTele.BackgroundColor3 = Color3.new(0.85098, 1, 0.905882)
SpawnTele.Position = UDim2.new(0.0387096778, 0, 0.0185185224, 0)
SpawnTele.Size = UDim2.new(0, 130, 0, 23)
SpawnTele.Font = Enum.Font.ArialBold
SpawnTele.Text = "Spawn"
SpawnTele.TextColor3 = Color3.new(0, 0, 0)
SpawnTele.TextSize = 14
SpawnTele.MouseButton1Down:connect(function()
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(155,3,74))end
)

WoodRUSTele.Name = "WoodRUS Tele"
WoodRUSTele.Parent = TeleportScroll
WoodRUSTele.BackgroundColor3 = Color3.new(0.85098, 1, 0.905882)
WoodRUSTele.Position = UDim2.new(0.0390000008, 0, 0.0590000004, 0)
WoodRUSTele.Size = UDim2.new(0, 130, 0, 23)
WoodRUSTele.Font = Enum.Font.ArialBold
WoodRUSTele.Text = "Wood R Us"
WoodRUSTele.TextColor3 = Color3.new(0, 0, 0)
WoodRUSTele.TextSize = 14
WoodRUSTele.MouseButton1Click:connect(function()
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(265,3,57))end
)

FurnishingTele.Name = "Furnishing Tele"
FurnishingTele.Parent = TeleportScroll
FurnishingTele.BackgroundColor3 = Color3.new(0.85098, 1, 0.905882)
FurnishingTele.Position = UDim2.new(0.0390000008, 0, 0.0989999995, 0)
FurnishingTele.Size = UDim2.new(0, 130, 0, 23)
FurnishingTele.Font = Enum.Font.ArialBold
FurnishingTele.Text = "Furnishing"
FurnishingTele.TextColor3 = Color3.new(0, 0, 0)
FurnishingTele.TextSize = 14
FurnishingTele.MouseButton1Click:connect(function()
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(491, 3, -1720))end
)

CarsTele.Name = "Cars Tele"
CarsTele.Parent = TeleportScroll
CarsTele.BackgroundColor3 = Color3.new(0.85098, 1, 0.905882)
CarsTele.Position = UDim2.new(0.0390000008, 0, 0.137999997, 0)
CarsTele.Size = UDim2.new(0, 130, 0, 23)
CarsTele.Font = Enum.Font.ArialBold
CarsTele.Text = "Cars"
CarsTele.TextColor3 = Color3.new(0, 0, 0)
CarsTele.TextSize = 14
CarsTele.MouseButton1Click:connect(function()
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(509, 3, -1463))end
)

LinksStoreTele.Name = "Links Store Tele"
LinksStoreTele.Parent = TeleportScroll
LinksStoreTele.BackgroundColor3 = Color3.new(0.85098, 1, 0.905882)
LinksStoreTele.Position = UDim2.new(0.0390000008, 0, 0.178000003, 0)
LinksStoreTele.Size = UDim2.new(0, 130, 0, 23)
LinksStoreTele.Font = Enum.Font.ArialBold
LinksStoreTele.Text = "Links Store"
LinksStoreTele.TextColor3 = Color3.new(0, 0, 0)
LinksStoreTele.TextSize = 14
LinksStoreTele.MouseButton1Click:connect(function()
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(4607,7.5,-798))end
)

BobsShack.Name = "Bobs Shack"
BobsShack.Parent = TeleportScroll
BobsShack.BackgroundColor3 = Color3.new(0.85098, 1, 0.905882)
BobsShack.Position = UDim2.new(0.0390000008, 0, 0.216999993, 0)
BobsShack.Size = UDim2.new(0, 130, 0, 23)
BobsShack.Font = Enum.Font.ArialBold
BobsShack.Text = "Bobs Shack"
BobsShack.TextColor3 = Color3.new(0, 0, 0)
BobsShack.TextSize = 14
BobsShack.MouseButton1Click:connect(function()
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(260, 8, -2542))end
)

FineArtTele.Name = "Fine Art Tele"
FineArtTele.Parent = TeleportScroll
FineArtTele.BackgroundColor3 = Color3.new(0.85098, 1, 0.905882)
FineArtTele.Position = UDim2.new(0.0390000008, 0, 0.256999999, 0)
FineArtTele.Size = UDim2.new(0, 130, 0, 23)
FineArtTele.Font = Enum.Font.ArialBold
FineArtTele.Text = "Fine Art"
FineArtTele.TextColor3 = Color3.new(0, 0, 0)
FineArtTele.TextSize = 14
FineArtTele.MouseButton1Down:connect(function()
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(5207, -166, 719))end
)

SwampTele.Name = "Swamp Tele"
SwampTele.Parent = TeleportScroll
SwampTele.BackgroundColor3 = Color3.new(0.85098, 1, 0.905882)
SwampTele.Position = UDim2.new(0.0390000008, 0, 0.296999991, 0)
SwampTele.Size = UDim2.new(0, 130, 0, 23)
SwampTele.Font = Enum.Font.ArialBold
SwampTele.Text = "Swamp"
SwampTele.TextColor3 = Color3.new(0, 0, 0)
SwampTele.TextSize = 14
SwampTele.MouseButton1Click:connect(function()
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(-1209,132,-801))end
)

PalmsTele.Name = "Palms Tele"
PalmsTele.Parent = TeleportScroll
PalmsTele.BackgroundColor3 = Color3.new(0.85098, 1, 0.905882)
PalmsTele.Position = UDim2.new(0.0390000008, 0, 0.345999986, 0)
PalmsTele.Size = UDim2.new(0, 130, 0, 23)
PalmsTele.Font = Enum.Font.ArialBold
PalmsTele.Text = "Palms"
PalmsTele.TextColor3 = Color3.new(0, 0, 0)
PalmsTele.TextSize = 14
PalmsTele.MouseButton1Click:connect(function()
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(2549, -5, -42))end
)

CaveTele.Name = "Cave Tele"
CaveTele.Parent = TeleportScroll
CaveTele.BackgroundColor3 = Color3.new(0.85098, 1, 0.905882)
CaveTele.Position = UDim2.new(0.0390000008, 0, 0.386000007, 0)
CaveTele.Size = UDim2.new(0, 130, 0, 23)
CaveTele.Font = Enum.Font.ArialBold
CaveTele.Text = "Cave"
CaveTele.TextColor3 = Color3.new(0, 0, 0)
CaveTele.TextSize = 14
CaveTele.MouseButton1Down:connect(function()
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(3581,-179,430))end
)

YellowWoodTele.Name = "Yellow Wood Tele"
YellowWoodTele.Parent = TeleportScroll
YellowWoodTele.BackgroundColor3 = Color3.new(0.85098, 1, 0.905882)
YellowWoodTele.Position = UDim2.new(0.0390000008, 0, 0.425000012, 0)
YellowWoodTele.Size = UDim2.new(0, 130, 0, 23)
YellowWoodTele.Font = Enum.Font.ArialBold
YellowWoodTele.Text = "Yellow Wood"
YellowWoodTele.TextColor3 = Color3.new(0, 0, 0)
YellowWoodTele.TextSize = 14
YellowWoodTele.MouseButton1Down:connect(function()
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(-1049,-5.9 ,-934.7 ))end
)

Volcano.Name = "Volcano"
Volcano.Parent = TeleportScroll
Volcano.BackgroundColor3 = Color3.new(0.85098, 1, 0.905882)
Volcano.Position = UDim2.new(0.0390000008, 0, 0.465000004, 0)
Volcano.Size = UDim2.new(0, 130, 0, 23)
Volcano.Font = Enum.Font.ArialBold
Volcano.Text = "Volcano"
Volcano.TextColor3 = Color3.new(0, 0, 0)
Volcano.TextSize = 14
Volcano.MouseButton1Down:connect(function()
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(-1585,622,1140))end
)

IceTreeTele.Name = "Ice Tree Tele"
IceTreeTele.Parent = TeleportScroll
IceTreeTele.BackgroundColor3 = Color3.new(0.85098, 1, 0.905882)
IceTreeTele.Position = UDim2.new(0.0390000008, 0, 0.504000008, 0)
IceTreeTele.Size = UDim2.new(0, 130, 0, 23)
IceTreeTele.Font = Enum.Font.ArialBold
IceTreeTele.Text = "Ice Tree"
IceTreeTele.TextColor3 = Color3.new(0, 0, 0)
IceTreeTele.TextSize = 14
IceTreeTele.MouseButton1Down:connect(function()
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(1505.7,412.4 ,3253 ))
end)

EndTimesTele.Name = "End Times Tele"
EndTimesTele.Parent = TeleportScroll
EndTimesTele.BackgroundColor3 = Color3.new(0.85098, 1, 0.905882)
EndTimesTele.Position = UDim2.new(0.0390000008, 0, 0.54400003, 0)
EndTimesTele.Size = UDim2.new(0, 130, 0, 23)
EndTimesTele.Font = Enum.Font.ArialBold
EndTimesTele.Text = "End Times"
EndTimesTele.TextColor3 = Color3.new(0, 0, 0)
EndTimesTele.TextSize = 14
EndTimesTele.MouseButton1Click:connect(function()
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(113, -214, -951))end
)

Den.Name = "Den"
Den.Parent = TeleportScroll
Den.BackgroundColor3 = Color3.new(0.85098, 1, 0.905882)
Den.Position = UDim2.new(0.0390000008, 0, 0.583999991, 0)
Den.Size = UDim2.new(0, 130, 0, 23)
Den.Font = Enum.Font.ArialBold
Den.Text = "Den"
Den.TextColor3 = Color3.new(0, 0, 0)
Den.TextSize = 14
Den.MouseButton1Down:connect(function() 
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(331, 45, 1941))
end)

StrangeMan.Name = "Strange Man"
StrangeMan.Parent = TeleportScroll
StrangeMan.BackgroundColor3 = Color3.new(0.85098, 1, 0.905882)
StrangeMan.Position = UDim2.new(0.0390000008, 0, 0.662000002, 0)
StrangeMan.Size = UDim2.new(0, 130, 0, 23)
StrangeMan.Font = Enum.Font.ArialBold
StrangeMan.Text = "Strange Man"
StrangeMan.TextColor3 = Color3.new(0, 0, 0)
StrangeMan.TextSize = 14
StrangeMan.MouseButton1Click:connect(function()
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(1061, 16, 1131))end
)

SkiiLodge.Name = "SkiiLodge"
SkiiLodge.Parent = TeleportScroll
SkiiLodge.BackgroundColor3 = Color3.new(0.85098, 1, 0.905882)
SkiiLodge.Position = UDim2.new(0.0390000008, 0, 0.622000023, 0)
SkiiLodge.Size = UDim2.new(0, 130, 0, 23)
SkiiLodge.Font = Enum.Font.ArialBold
SkiiLodge.Text = "SkiiLodge"
SkiiLodge.TextColor3 = Color3.new(0, 0, 0)
SkiiLodge.TextSize = 14
SkiiLodge.MouseButton1Click:connect(function()
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(1244, 62, 2306))end
)

GodAxeB.Name = "God Axe B"
GodAxeB.Parent = GUI
GodAxeB.BackgroundColor3 = Color3.new(0.815686, 0.882353, 1)
GodAxeB.BorderSizePixel = 2
GodAxeB.Position = UDim2.new(0.0276143812, 0, 0.643200755, 0)
GodAxeB.Size = UDim2.new(0, 72, 0, 50)
GodAxeB.Font = Enum.Font.Bodoni
GodAxeB.Text = "God Axe"
GodAxeB.TextColor3 = Color3.new(0, 0, 0)
GodAxeB.TextSize = 14
GodAxeB.MouseButton1Down:connect(function()
    local a=game:GetService("Players").LocalPlayer:GetMouse()a.Button1Down:connect(function(b)Pressing=false end)function GetAxe()if game.Players.LocalPlayer.Character:FindFirstChild("Tool")then return game.Players.LocalPlayer.Character:FindFirstChild("Tool")end end;local c={['GoldAxe']=50,['BasicHatchet']=0.2,['Axe1']=0.55,['Axe2']=0.93,['AxeAlphaTesters']=1.5,['Rukiryaxe']=1.68,['Axe3']=1.45,['AxeBetaTesters']=1.45,['FireAxe']=0.6,['SilverAxe']=1.6,['EndTimesAxe']=10000000,['AxeChicken']=0.1,['CandyCaneAxe']=0}local Pressing=false;local a=game:GetService("Players").LocalPlayer:GetMouse()a.Button1Down:connect(function(b)Pressing=false end)a.Button1Down:connect(function(b)Pressing=true;poop(GetAxe())end)function cut(d)local e=game.Players.LocalPlayer:GetMouse().Target;local f=game.Players.LocalPlayer:GetMouse().Hit;local g=e.CFrame:pointToObjectSpace(f.p).Y+e.Size.Y/2;if e.Parent:WaitForChild("CutEvent",0.1)then game.ReplicatedStorage.Interaction.RemoteProxy:FireServer(e.Parent.CutEvent,{["cuttingClass"]="Axe",["cooldown"]=0,["hitPoints"]=c[d.ToolName.Value],["sectionId"]=e.ID.Value,["tool"]=d,["faceVector"]=Vector3.new(-1,0,0),["height"]=g})end end;function poop(d)for h=1,100 do if Pressing==true then cut(d)end end end
end)

MaxSpeedB.Name = "Max Speed B"
MaxSpeedB.Parent = GUI
MaxSpeedB.BackgroundColor3 = Color3.new(0.815686, 0.882353, 1)
MaxSpeedB.BorderSizePixel = 2
MaxSpeedB.Position = UDim2.new(0.0276143812, 0, 0.308931082, 0)
MaxSpeedB.Size = UDim2.new(0, 72, 0, 50)
MaxSpeedB.Font = Enum.Font.Bodoni
MaxSpeedB.Text = "Max Speed"
MaxSpeedB.TextColor3 = Color3.new(0, 0, 0)
MaxSpeedB.TextSize = 14
MaxSpeedB.MouseButton1Down:connect(function()
while true do
    wait()
    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 120
end
end)

TeleportWoodB.Name = "Teleport Wood B"
TeleportWoodB.Parent = GUI
TeleportWoodB.BackgroundColor3 = Color3.new(0.333333, 1, 0.498039)
TeleportWoodB.BorderColor3 = Color3.new(0.666667, 0.666667, 1)
TeleportWoodB.BorderSizePixel = 3
TeleportWoodB.Position = UDim2.new(0.676470578, 0, 0.095238097, 0)
TeleportWoodB.Size = UDim2.new(0, 72, 0, 56)
TeleportWoodB.Font = Enum.Font.Bodoni
TeleportWoodB.Text = "Teleport All Dropped Wood"
TeleportWoodB.TextColor3 = Color3.new(0, 0, 0)
TeleportWoodB.TextScaled = true
TeleportWoodB.TextSize = 14
TeleportWoodB.TextWrapped = true
TeleportWoodB.MouseButton1Down:connect(function()

Option = false
Found = false
Tool = "None"
Down = false
Mouse = game.Players.LocalPlayer:GetMouse()
 
Client = game.ReplicatedStorage.Interaction.ClientSetListPlayer
players = game.Players
for i, v in pairs(players:GetPlayers()) do
if v.Name ~= players.LocalPlayer.Name then
Client:InvokeServer(players.LocalPlayer.BlacklistFolder, v, true)
end
end
players.PlayerAdded:connect(function(plr)
Client:InvokeServer(players.LocalPlayer.BlacklistFolder, plr, true)
end)
 
function move(object)
object:MoveTo(game.Players.LocalPlayer.Character.Head.Position + Vector3.new(5, -4, 5))
object.WoodSection.Anchored = true
wait(2)
object.WoodSection.Anchored = false
end
 
function tree(object, class)
for i, v in pairs(object:GetChildren()) do
if v.Name == "TreeClass" then
if v.Value == class then
if Found == false then
move(object)
Found = true
end
end
end
end
end
 
function cut(object, class)
for i, v in pairs(object:GetChildren()) do
if v.Name == "TreeClass" then
if v.Value == class then
for a, b in pairs(object:GetChildren()) do
if b.Name == "Owner" then
for c, d in pairs(b:GetChildren()) do
if d.Name == "OwnerString" then
if d.Value == game.Players.LocalPlayer.Name then
move(object)
else
if d.Value == "" then
move(object)
end
end
end
end
end
end
end
end
end
end

for i, v in pairs(game.Workspace.LogModels:GetChildren()) do
cut(v, "Generic")
end
for i, v in pairs(game.Workspace.LogModels:GetChildren()) do
cut(v, "Birth")
end
for i, v in pairs(game.Workspace.LogModels:GetChildren()) do
cut(v, "CaveCrawler")
end
for i, v in pairs(game.Workspace.LogModels:GetChildren()) do
cut(v, "Cherry")
end
for i, v in pairs(game.Workspace.LogModels:GetChildren()) do
cut(v, "Fir")
end
for i, v in pairs(game.Workspace.LogModels:GetChildren()) do
cut(v, "GoldSwampy")
end
for i, v in pairs(game.Workspace.LogModels:GetChildren()) do
cut(v, "GreenSwampy")
end
for i, v in pairs(game.Workspace.LogModels:GetChildren()) do
cut(v, "Koa")
end
for i, v in pairs(game.Workspace.LogModels:GetChildren()) do
cut(v, "Oak")
end
for i, v in pairs(game.Workspace.LogModels:GetChildren()) do
cut(v, "Palm")
end
for i, v in pairs(game.Workspace.LogModels:GetChildren()) do
cut(v, "Pine")
end
for i, v in pairs(game.Workspace.LogModels:GetChildren()) do
cut(v, "Volcano")
end
for i, v in pairs(game.Workspace.LogModels:GetChildren()) do
cut(v, "Walnut")
end
for i, v in pairs(game.Workspace.LogModels:GetChildren()) do
cut(v, "Frost")
end
for i, v in pairs(game.Workspace.LogModels:GetChildren()) do
cut(v, "SnowGlow")
end
for i, v in pairs(game.Workspace.LogModels:GetChildren()) do
cut(v, "LoneCave")
end
end)

ImageButton.Parent = TeleportWoodB
ImageButton.BackgroundColor3 = Color3.new(1, 1, 1)
ImageButton.BackgroundTransparency = 1
ImageButton.Position = UDim2.new(0.122549057, 0, -0.718837559, 0)
ImageButton.Size = UDim2.new(0, 53, 0, 56)
ImageButton.Image = "rbxassetid://2396612568"

TeleportsText.Name = "Teleports Text"
TeleportsText.Parent = GUI
TeleportsText.BackgroundColor3 = Color3.new(0.490196, 0.94902, 1)
TeleportsText.BorderColor3 = Color3.new(0.419608, 0.2, 0.427451)
TeleportsText.BorderSizePixel = 3
TeleportsText.Position = UDim2.new(0.352941155, 0, 0.280112058, 0)
TeleportsText.Size = UDim2.new(0, 155, 0, 26)
TeleportsText.Font = Enum.Font.Bodoni
TeleportsText.Text = "Place Teleports"
TeleportsText.TextColor3 = Color3.new(0, 0, 0)
TeleportsText.TextSize = 16

FlyB.Name = "Fly B"
FlyB.Parent = GUI
FlyB.BackgroundColor3 = Color3.new(0.815686, 0.882353, 1)
FlyB.BorderSizePixel = 2
FlyB.Position = UDim2.new(0.0276143812, 0, 0.478868425, 0)
FlyB.Size = UDim2.new(0, 72, 0, 50)
FlyB.Font = Enum.Font.Bodoni
FlyB.Text = "Fly"
FlyB.TextColor3 = Color3.new(0, 0, 0)
FlyB.TextSize = 14

local flying = false
FlyB.MouseButton1Click:connect(function()
flying = not flying
repeat wait()
until game.Players.LocalPlayer and game.Players.LocalPlayer.Character and game.Players.LocalPlayer.Character:findFirstChild("Torso") and game.Players.LocalPlayer.Character:findFirstChild("Humanoid")
local mouse = game.Players.LocalPlayer:GetMouse()
repeat wait() until mouse
local plr = game.Players.LocalPlayer
local torso = plr.Character.Torso
local deb = true
local ctrl = {f = 0, b = 0, l = 0, r = 0}
local lastctrl = {f = 0, b = 0, l = 0, r = 0}
local maxspeed = 200
local speed = 0
if flying then
end

function FlyFunction()
local bg = Instance.new("BodyGyro", torso)
bg.P = 9e4
bg.maxTorque = Vector3.new(9e9, 9e9, 9e9)
bg.cframe = torso.CFrame
local bv = Instance.new("BodyVelocity", torso)
bv.velocity = Vector3.new(0,0.1,0)
bv.maxForce = Vector3.new(9e9, 9e9, 9e9)
repeat wait()
plr.Character.Humanoid.PlatformStand = true
if ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0 then
speed = speed+.5+(speed/maxspeed)
if speed > maxspeed then
speed = maxspeed
end
elseif not (ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0) and speed ~= 0 then
speed = speed-1
if speed < 0 then
speed = 0
end
end
if (ctrl.l + ctrl.r) ~= 0 or (ctrl.f + ctrl.b) ~= 0 then
bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (ctrl.f+ctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(ctrl.l+ctrl.r,(ctrl.f+ctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed
lastctrl = {f = ctrl.f, b = ctrl.b, l = ctrl.l, r = ctrl.r}
elseif (ctrl.l + ctrl.r) == 0 and (ctrl.f + ctrl.b) == 0 and speed ~= 0 then
bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (lastctrl.f+lastctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(lastctrl.l+lastctrl.r,(lastctrl.f+lastctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed
else
bv.velocity = Vector3.new(0,0.1,0)
end
bg.cframe = game.Workspace.CurrentCamera.CoordinateFrame * CFrame.Angles(-math.rad((ctrl.f+ctrl.b)*50*speed/maxspeed),0,0)
until not flying
ctrl = {f = 0, b = 0, l = 0, r = 0}
lastctrl = {f = 0, b = 0, l = 0, r = 0}
speed = 0
bg:Destroy()
bv:Destroy()
plr.Character.Humanoid.PlatformStand = false
end
mouse.KeyDown:connect(function(key)
if key:lower() == "w" then
ctrl.f = 1
elseif key:lower() == "s" then
ctrl.b = -1
elseif key:lower() == "a" then
ctrl.l = -1
elseif key:lower() == "d" then
ctrl.r = 1
end
end)
mouse.KeyUp:connect(function(key)
if key:lower() == "w" then
ctrl.f = 0
elseif key:lower() == "s" then
ctrl.b = 0
elseif key:lower() == "a" then
ctrl.l = 0
elseif key:lower() == "d" then
ctrl.r = 0
end
end)
FlyFunction()
end)

clip = true
NoClipB.MouseButton1Click:connect(function()
    clip = not clip
    game:GetService('RunService').Stepped:connect(function()
        if not clip then
            game.Players.LocalPlayer.Character.Head.CanCollide = false
            game.Players.LocalPlayer.Character.Torso.CanCollide = false
            game.Players.LocalPlayer.Character["Left Leg"].CanCollide = false
            game.Players.LocalPlayer.Character["Right Leg"].CanCollide = false
        end
    end)
end)

Logo.Name = "Logo"
Logo.Parent = GUI
Logo.BackgroundColor3 = Color3.new(1, 1, 1)
Logo.BorderSizePixel = 4
Logo.Position = UDim2.new(-0.00694444822, 0, -0.00493839337, 0)
Logo.Size = UDim2.new(0, 44, 0, 44)
Logo.Image = "rbxassetid://2391933162"
Logo.ImageColor3 = Color3.new(0.87451, 0.811765, 1)

Frame.Parent = Logo
Frame.BackgroundColor3 = Color3.new(0.87451, 0.811765, 1)
Frame.BorderSizePixel = 3
Frame.Position = UDim2.new(1.1427139, 0, -0.00560224056, 0)
Frame.Size = UDim2.new(0, 48, 0, 9)

Frame_2.Parent = Logo
Frame_2.BackgroundColor3 = Color3.new(0.87451, 0.811765, 1)
Frame_2.BorderSizePixel = 3
Frame_2.Position = UDim2.new(0.00768723339, 0, 1.12829936, 0)
Frame_2.Size = UDim2.new(0, 9, 0, 43)

TextLabel.Parent = GUI
TextLabel.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel.BackgroundTransparency = 1
TextLabel.Position = UDim2.new(0.136029422, 0, -0.00560224056, 0)
TextLabel.Size = UDim2.new(0, 35, 0, 50)
TextLabel.Font = Enum.Font.Garamond
TextLabel.Text = "L"
TextLabel.TextColor3 = Color3.new(0, 1, 1)
TextLabel.TextSize = 24

TextLabel_2.Parent = GUI
TextLabel_2.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel_2.BackgroundTransparency = 1
TextLabel_2.Position = UDim2.new(-0.029411763, 0, -0.00840336084, 0)
TextLabel_2.Size = UDim2.new(0, 243, 0, 50)
TextLabel_2.Font = Enum.Font.Garamond
TextLabel_2.Text = "umber Tycoon   GUI"
TextLabel_2.TextColor3 = Color3.new(1, 1, 1)
TextLabel_2.TextSize = 17

TextLabel_3.Parent = GUI
TextLabel_3.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel_3.BackgroundTransparency = 1
TextLabel_3.Position = UDim2.new(0.485294133, 0, -0.00560224056, 0)
TextLabel_3.Size = UDim2.new(0, 35, 0, 50)
TextLabel_3.Font = Enum.Font.Garamond
TextLabel_3.Text = "2"
TextLabel_3.TextColor3 = Color3.new(0, 1, 1)
TextLabel_3.TextSize = 24

NoClipB.Name = "NoClip B"
NoClipB.Parent = GUI
NoClipB.BackgroundColor3 = Color3.new(0.815686, 0.882353, 1)
NoClipB.BorderSizePixel = 2
NoClipB.Position = UDim2.new(0.0257352944, 0, 0.812169254, 0)
NoClipB.Size = UDim2.new(0, 72, 0, 47)
NoClipB.Font = Enum.Font.Bodoni
NoClipB.Text = "No Clip"
NoClipB.TextColor3 = Color3.new(0, 0, 0)
NoClipB.TextSize = 14

CloseGUI.Name = "Close GUI"
CloseGUI.Parent = GUI
CloseGUI.BackgroundColor3 = Color3.new(1, 0, 0)
CloseGUI.BorderColor3 = Color3.new(0, 0, 0)
CloseGUI.Position = UDim2.new(0.930147052, 0, -0.0291005298, 0)
CloseGUI.Size = UDim2.new(0, 26, 0, 26)
CloseGUI.Font = Enum.Font.SourceSans
CloseGUI.Text = "X"
CloseGUI.TextColor3 = Color3.new(0, 0, 0)
CloseGUI.TextSize = 14
CloseGUI.MouseButton1Down:connect(function()
OpenMain.Visible=true
GUI.Visible=false
end)

PlayerTeleportB.Name = "Player Teleport B"
PlayerTeleportB.Parent = GUI
PlayerTeleportB.BackgroundColor3 = Color3.new(0.701961, 0.701961, 1)
PlayerTeleportB.BorderSizePixel = 4
PlayerTeleportB.Position = UDim2.new(0.0551470444, 0, 0.158730164, 0)
PlayerTeleportB.Size = UDim2.new(0, 151, 0, 25)
PlayerTeleportB.Font = Enum.Font.ArialBold
PlayerTeleportB.Text = "Player Teleport"
PlayerTeleportB.TextColor3 = Color3.new(0, 0, 0)
PlayerTeleportB.TextSize = 14
PlayerTeleportB.MouseButton1Down:connect(function()
TeleportPlayerGUI.Visible=true
end)

TeleportPlayerGUI.Name = "Teleport Player GUI"
TeleportPlayerGUI.Parent = ScreenGui
TeleportPlayerGUI.BackgroundColor3 = Color3.new(1, 1, 1)
TeleportPlayerGUI.Position = UDim2.new(0.831833303, 0, 0.499360323, 0)
TeleportPlayerGUI.Size = UDim2.new(0, 114, 0, 258)
TeleportPlayerGUI.Visible = false
TeleportPlayerGUI.Style = Enum.FrameStyle.RobloxSquare
TeleportPlayerGUI.Active=true
TeleportPlayerGUI.Draggable=true

Player6B.Name = "Player6B"
Player6B.Parent = TeleportPlayerGUI
Player6B.BackgroundColor3 = Color3.new(1, 1, 1)
Player6B.Position = UDim2.new(-0.0132870637, 0, 0.866432965, 0)
Player6B.Size = UDim2.new(0, 101, 0, 23)
Player6B.Style = Enum.ButtonStyle.RobloxRoundDropdownButton
Player6B.Font = Enum.Font.SourceSans
Player6B.Text = ""
Player6B.TextColor3 = Color3.new(0, 0, 0)
Player6B.TextSize = 12

Player5B.Name = "Player5B"
Player5B.Parent = TeleportPlayerGUI
Player5B.BackgroundColor3 = Color3.new(1, 1, 1)
Player5B.Position = UDim2.new(-0.0132870637, 0, 0.737910688, 0)
Player5B.Size = UDim2.new(0, 101, 0, 23)
Player5B.Style = Enum.ButtonStyle.RobloxRoundDropdownButton
Player5B.Font = Enum.Font.SourceSans
Player5B.Text = ""
Player5B.TextColor3 = Color3.new(0, 0, 0)
Player5B.TextSize = 12

Player3B.Name = "Player3B"
Player3B.Parent = TeleportPlayerGUI
Player3B.BackgroundColor3 = Color3.new(1, 1, 1)
Player3B.Position = UDim2.new(-0.0132870637, 0, 0.482281208, 0)
Player3B.Size = UDim2.new(0, 101, 0, 23)
Player3B.Style = Enum.ButtonStyle.RobloxRoundDropdownButton
Player3B.Font = Enum.Font.SourceSans
Player3B.Text = ""
Player3B.TextColor3 = Color3.new(0, 0, 0)
Player3B.TextSize = 12

Player2B.Name = "Player2B"
Player2B.Parent = TeleportPlayerGUI
Player2B.BackgroundColor3 = Color3.new(1, 1, 1)
Player2B.Position = UDim2.new(-0.0220589936, 0, 0.35886541, 0)
Player2B.Size = UDim2.new(0, 101, 0, 23)
Player2B.Style = Enum.ButtonStyle.RobloxRoundDropdownButton
Player2B.Font = Enum.Font.SourceSans
Player2B.Text = ""
Player2B.TextColor3 = Color3.new(0, 0, 0)
Player2B.TextSize = 12

Player1B.Name = "Player1B"
Player1B.Parent = TeleportPlayerGUI
Player1B.BackgroundColor3 = Color3.new(1, 1, 1)
Player1B.Position = UDim2.new(-0.0220589936, 0, 0.234219164, 0)
Player1B.Size = UDim2.new(0, 101, 0, 23)
Player1B.Style = Enum.ButtonStyle.RobloxRoundDropdownButton
Player1B.Font = Enum.Font.SourceSans
Player1B.Text = ""
Player1B.TextColor3 = Color3.new(0, 0, 0)
Player1B.TextSize = 12

PlayerSelectScreen.Name = "PlayerSelectScreen"
PlayerSelectScreen.Parent = TeleportPlayerGUI
PlayerSelectScreen.BackgroundColor3 = Color3.new(0.14902, 0.14902, 0.14902)
PlayerSelectScreen.BorderColor3 = Color3.new(0.85098, 0.721569, 1)
PlayerSelectScreen.BorderSizePixel = 3
PlayerSelectScreen.Position = UDim2.new(-0.0263157897, 0, 0.11240311, 0)
PlayerSelectScreen.Size = UDim2.new(0, 104, 0, 23)
PlayerSelectScreen.Font = Enum.Font.SourceSans
PlayerSelectScreen.Text = ""
PlayerSelectScreen.TextColor3 = Color3.new(0.333333, 1, 0)
PlayerSelectScreen.TextSize = 13

Player4B.Name = "Player4B"
Player4B.Parent = TeleportPlayerGUI
Player4B.BackgroundColor3 = Color3.new(1, 1, 1)
Player4B.Position = UDim2.new(-0.0132869445, 0, 0.612034082, 0)
Player4B.Size = UDim2.new(0, 101, 0, 23)
Player4B.Style = Enum.ButtonStyle.RobloxRoundDropdownButton
Player4B.Font = Enum.Font.SourceSans
Player4B.Text = ""
Player4B.TextColor3 = Color3.new(0, 0, 0)
Player4B.TextSize = 12

boarder.Name = "boarder"
boarder.Parent = TeleportPlayerGUI
boarder.BackgroundColor3 = Color3.new(0.85098, 0.721569, 1)
boarder.Position = UDim2.new(-0.0964912251, 0, 0.10077519, 0)
boarder.Size = UDim2.new(0, 6, 0, 226)

boarder_2.Name = "boarder"
boarder_2.Parent = TeleportPlayerGUI
boarder_2.BackgroundColor3 = Color3.new(0.85098, 0.721569, 1)
boarder_2.Position = UDim2.new(1.02631581, 0, 0.10077519, 0)
boarder_2.Size = UDim2.new(0, 6, 0, 226)

boarder_3.Name = "boarder"
boarder_3.Parent = TeleportPlayerGUI
boarder_3.BackgroundColor3 = Color3.new(0.85098, 0.721569, 1)
boarder_3.Position = UDim2.new(-0.0964912251, 0, 0.992248058, 0)
boarder_3.Size = UDim2.new(0, 116, 0, 10)

TPPlayerB.Name = "TP Player B"
TPPlayerB.Parent = TeleportPlayerGUI
TPPlayerB.BackgroundColor3 = Color3.new(0.490196, 0.94902, 1)
TPPlayerB.BorderSizePixel = 3
TPPlayerB.Position = UDim2.new(-0.0789473653, 0, -0.0620155036, 0)
TPPlayerB.Size = UDim2.new(0, 113, 0, 32)
TPPlayerB.Font = Enum.Font.ArialBold
TPPlayerB.Text = "Click To Teleport"
TPPlayerB.TextColor3 = Color3.new(0, 0, 0)
TPPlayerB.TextSize = 14

CloseTeleports.Name = "Close Teleports"
CloseTeleports.Parent = TeleportPlayerGUI
CloseTeleports.BackgroundColor3 = Color3.new(1, 0, 0)
CloseTeleports.BorderColor3 = Color3.new(0, 0, 0)
CloseTeleports.Position = UDim2.new(0.289473712, 0, 0.984496117, 0)
CloseTeleports.Size = UDim2.new(0, 42, 0, 11)
CloseTeleports.Font = Enum.Font.SourceSans
CloseTeleports.Text = "X"
CloseTeleports.TextColor3 = Color3.new(0, 0, 0)
CloseTeleports.TextSize = 14
CloseTeleports.MouseButton1Down:connect(function()
TeleportPlayerGUI.Visible=false
end)

--script area:

 Player1B.MouseButton1Down:connect(function()
      PlayerSelectScreen.Text = Player1B.Text
    end)
 Player2B.MouseButton1Down:connect(function()
      PlayerSelectScreen.Text = Player2B.Text
    end)
 Player3B.MouseButton1Down:connect(function()
      PlayerSelectScreen.Text = Player3B.Text
    end)
 Player4B.MouseButton1Down:connect(function()
      PlayerSelectScreen.Text = Player4B.Text
    end)
 Player5B.MouseButton1Down:connect(function()
      PlayerSelectScreen.Text = Player5B.Text
    end)
 Player6B.MouseButton1Down:connect(function()
      PlayerSelectScreen.Text = Player6B.Text
    end)
    local buttons = {
     TeleportPlayerGUI.Player1B,
     TeleportPlayerGUI.Player2B,
     TeleportPlayerGUI.Player3B,
     TeleportPlayerGUI.Player4B,
     TeleportPlayerGUI.Player5B,
     TeleportPlayerGUI.Player6B
    }

for i, v in pairs(game.Players:GetChildren()) do
      buttons[i].Text = v.Name
      buttons[i].Visible = true
    end
    game.Players.PlayerRemoving:connect(function()
      for i, v in pairs(game.Players:GetChildren()) do
        buttons[i].Text = v.Name
        buttons[i].Visible = true
      end
    end)
    game.Players.PlayerAdded:connect(function()
      for i, v in pairs(game.Players:GetChildren()) do
        buttons[i].Text = v.Name
        buttons[i].Visible = true
      end
    end)

if TeleportPlayerGUI.Player1B.text == " " then
Player1B.Visible = false
end

if TeleportPlayerGUI.Player2B.text == " " then
Player2B.Visible = false
end

if TeleportPlayerGUI.Player3B.text == " " then
Player3B.Visible = false
end

if TeleportPlayerGUI.Player4B.text == " " then
Player4B.Visible = false
end

if TeleportPlayerGUI.Player5B.text == " " then
Player5B.Visible = false
end

if TeleportPlayerGUI.Player6B.text == "" then
Player6B.Visible = false
end

TPPlayerB.MouseButton1Down:connect(function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = workspace[PlayerSelectScreen.Text].HumanoidRootPart.CFrame
end)

TPPlayerB.MouseButton1Down:connect(function()
for i, v in pairs(game.Workspace.Properties:GetChildren()) do
        if v.Owner.Value == game.Players[PlayerSelectScreen.Text] then
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.OriginSquare.CFrame
end
end
end)
