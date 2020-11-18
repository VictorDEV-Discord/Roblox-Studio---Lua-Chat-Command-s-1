Hello, my name is VictorDEV...

# Remove Workspace Gravity:
game.Players.PlayerAdded:Connect(function(plyr)
  plyr.Chatted:Connect(function(args)
    if args == "/removegravity" then
      if plyr.userId == game.CreatorId then
        workspace.Gravity = 0
       end
     end
   end)
end)

# Add Workspace Gravity:
game.Players.PlayerAdded:Connect(function(plyr)
  plyr.Chatted:Connect(function(args)
    if args == "/removegravity" then
      if plyr.userId == game.CreatorId then
        workspace.Gravity = 196.6
       end
     end
   end)
end)
