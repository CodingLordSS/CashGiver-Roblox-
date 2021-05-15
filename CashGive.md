# CashGiver-Roblox-
Created by MrScout4T7 (Reth)

game.Players.PlayerAdded:connect(function(player)
	local Stats = Instance.new("IntValue")
	Stats.Parent = player
	Stats.Name = "leaderstats"
	
	local Cash = Instance.new("IntValue")
	Cash.Parent = Stats
	Cash.Name = "Cash"
	Cash.Value = 0
	
	while true do
		Cash.Value = Cash.Value + 100
		wait(10)
	end
end)
