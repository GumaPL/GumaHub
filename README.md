game.StarterGui:SetCore( 
    "ChatMakeSystemMessage",  { 
        Text = "{GumaHub} Loading Please wait", 
        Color = Color3.fromRGB( 255,0,0 ), 
        Font = Enum.Font.Arial, 
        FontSize = Enum.FontSize.Size24 
    } 
)

wait(6)

game.StarterGui:SetCore( 
    "ChatMakeSystemMessage",  { 
        Text = "{GumaHub} Loading Done Thanks for using GumaHub", 
        Color = Color3.fromRGB( 255,0,0 ), 
        Font = Enum.Font.Arial, 
        FontSize = Enum.FontSize.Size24 
    } 
)

wait(0.5)

game.StarterGui:SetCore( 
    "ChatMakeSystemMessage",  { 
        Text = "{GumaHub} KocMoc Bee swarm Loading", 
        Color = Color3.fromRGB( 255,0,0 ), 
        Font = Enum.Font.Arial, 
        FontSize = Enum.FontSize.Size24 
    } 
)

wait(2)

game.StarterGui:SetCore( 
    "ChatMakeSystemMessage",  { 
        Text = "{GumaHub} KocMoc Loaded", 
        Color = Color3.fromRGB( 255,0,0 ), 
        Font = Enum.Font.Arial, 
        FontSize = Enum.FontSize.Size24 
    } 

wait(1)

game.StarterGui:SetCore( 
    "ChatMakeSystemMessage",  { 
        Text = "{GumaHub} Have fun", 
        Color = Color3.fromRGB( 255,0,0 ), 
        Font = Enum.Font.Arial, 
        FontSize = Enum.FontSize.Size24 
    } 
)

wait(0.3)

loadstring(game:HttpGet("https://raw.githubusercontent.com/not-weuz/Lua/main/kocmoc.lua"))()

)
