# How To Use
```lua
-- loading GRH-Service (Adding Global GRH To Every Script)
loadstring(game:HttpGet("https://raw.githubusercontent.com/GrblxHOfficial/GRH-Service/main/source.lua"))()

-- GRH-Service Syntax
GRH.Noclip = bool

GRH.InfJump = bool

GRH.FindNearestPlayer(Whitelist) -- function that returns nearest player to your character, whitelist must be table with whitelisted players or blank table

GRH.ws(number) -- change walkspeed

GRH.jp(number) -- change jump power

GRH.lp -- local player

GRH.c -- local player character

GRH.m -- local player mouse

GRH.grav(number) -- change gravity

GRH.Aimbot.Enabled = bool
GRH.Aimbot.AimAtPlayer = Player
GRH.Aimbot.AimPart = "Head"

GRH.FindNearsetPlayerToMouse(Whitelist) -- functon that returns nearest player to mouse

GRH.WallCheck(Object, ObjectsToIgnore) -- function that returns are Object is visible on camera.

GRH.GodMode() -- Enter God Mode
-- Release Soon.
```
