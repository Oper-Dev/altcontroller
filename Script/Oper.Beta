-- [[ Settings ]] --

getgenv().prefix = '.' -- prefix which should run the commands
getgenv().controller = 12345 -- id of whitelisted user, requirements: whitelisted, in group as premium role, note the controller must join before alts
getgenv().delayExecute = false -- recommended to be off, it make all alts wait randomly between 1-14 seconds before executing instead of executing all in same time, which would probably casue connection timeout

getgenv().lag_reducer = true -- recommended to be on, reduce lag a lot

getgenv().alts = { -- max 38 alts
    Alt1 = 12345, -- Alt3, etc make sure all have "," after each alt
    Alt2 = 12345,
}

getgenv().commands = { -- change "drop" to anything else you want drop to run when you say, same for others down
    ['OPER_DropStart'] = "drop",
    ['OPER_DropStop'] = "stop",
    ['OPER_DropUntil'] = "dropuntil",
    ['OPER_BringAlts'] = "bring",
    ['OPER_SetupAlts'] = "setup",
    ['OPER_CrashCMD'] = "crash", -- if you want swagmode crash say .crash swag
    ['OPER_TotalCashCount'] = "countcash",
    ['OPER_KickAllAlts'] = "kickalts",
    ['OPER_ToggleFreezeAlts'] = "freeze",
    ['OPER_ShowOrHideWallet'] = "wallet",
    ['OPER_AirLockAlts'] = "airlock",
    ['OPER_ResetAltsCharacters'] = "killalts",
    ['OPER_SaySomething'] = "say",
    ['OPER_SetTheFPSCap'] = "fps",
    ['OPER_CashPickingToggle'] = "cashaura",
    ['OPER_AltsVibingLOL'] = "vibe",
    ['OPER_HideAlts'] = "hide",
    ['OPER_AutoDestroyCash'] = 'loopdestroy',
    ['OPER_LoopKillUser'] = 'loopkill',
    ['OPER_StopLoopKill'] = 'stopkill',
    ['OPER_LineUp'] = 'line',
    ['OPER_HoldBlock'] = 'block',
    ['OPER_SpamMessage'] = 'spam',
    ['OPER_GodMode'] = 'god',
    ['OPER_CircleAround'] = 'circle',
    ['OPER_ChatSpy'] = 'spy',
    ['OPER_Benxlol'] = 'benx',
    ['OPER_TpPlayerTo'] = 'tp',
}

getgenv().locations = { -- change "bank" to anything else you want location name to be replaced and used with, same for others down
    ['OPER_InfrontBank'] = "bank",
    ['OPER_AdminBase'] = "base",
    ['OPER_School'] = 'school',
    ['OPER_Train'] = 'train',
    ['OPER_SafeZone3'] = 'sz3',
    ['OPER_BasketBall'] = 'basket',
    ['OPER_TacoShop'] = 'taco',
    ['OPER_AdminJail'] = 'jail',
    ['OPER_UnderTrain'] = 'undertrain',
    ['OPER_TheClub'] = 'club',
}

-- [[ Launcher ]] --

loadstring(game:HttpGet("https://raw.githubusercontent.com/Husam-Dev/altcontroller/main/operpremium.lua", true))()
