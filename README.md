local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()

--local Tab = Window:MakeTab({
	Name = "Tab 1",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})
--OrionLib:MakeNotification({
	Name = "luz Hub",
	Content = "bem vindo a luz hub",
	Image = "rbxassetid://4483345998",
	Time = 5
})
--Tab:AddButton({
	Name = "esp",
	Callback = function(

-- ESP para Arsenal

-- Configurações
local espColor = Color3.new(1, 0, 0) -- Cor do ESP (vermelho)
local transparency = 0.75 -- Transparência do ESP (0 a 1)

-- Função para criar o ESP
function createESP(player)
    local gui = Instance.new("BillboardGui")
    gui.Name = "ESP"
    gui.AlwaysOnTop = true
    gui.LightInfluence = 0
    gui.Size = UDim2.new(1.75, 0, 1.75, 0)

    local frame = Instance.new("Frame", gui)
    frame.BackgroundColor3 = espColor
    frame.Size = UDim2.new(1, 0, 1, 0)
    frame.BorderSizePixel = 4
    frame.BorderColor3 = Color3.new(0, 0, 0)

    gui.Parent = player.Character.Head
end
-- ESP para Arsenal
-- Feito por xMiles_Games

-- Configurações
local espColor = Color3.new(1, 0, 0) -- Cor do ESP (vermelho)
local transparency = 0.75 -- Transparência do ESP (0 a 1)

-- Função para criar o ESP
function createESP(player)
    local gui = Instance.new("BillboardGui")
    gui.Name = "ESP"
    gui.AlwaysOnTop = true
    gui.LightInfluence = 0
    gui.Size = UDim2.new(1.75, 0, 1.75, 0)

    local frame = Instance.new("Frame", gui)
    frame.BackgroundColor3 = espColor
    frame.Size = UDim2.new(1, 0, 1, 0)
    frame.BorderSizePixel = 4
    frame.BorderColor3 = Color3.new(0, 0, 0)

    gui.Parent = player.Character.Head
end

-- Loop para atualizar o ESP
while true do
    for _, player in pairs(game.Players:GetPlayers()) do
        if player ~= game.Players.LocalPlayer and player.Character and player.Character:FindFirstChild("Head") then
            createESP(player)
        end
    end
    wait(1) end)
      		print("funcionado")
  	end    
})
--OrionLib:Init()
