# Arctic Documents

## Launching Arctic
CreateWindow("Name Of Script", Color.fromRGB(255, 0, 0)) -- Set This To You're Color Liking.

## Creating A Menu
CreateMenu("Name Of Menu")

## Creating A Regular Button
CreateRegButton("NameOfButton", "Menu To Be In", function()
    Script Here!
end)

## Creating A Toggle Button
CreateTogButton("NameOfButton", "Menu To Be In", ChangeToToggleVariable, function()
    Script Here!
end)

## Creating A Search Button
CreateSearchButton("NameOfButton", "Menu To Be In", function(CalledText)
    Script Here!
    -- Note, All Text Written Will Be Set As CalledText
end)

## Creating A Togglable Search Button
CreateToggleSearchButton("NameOfButton", "Menu To Be In", ChangeToToggleVariable, function(CalledText)
    Script Here!
    -- Note, All Text Written Will Be Set As A Called Text
end)

## Creating A Notification
CreateNotification("TextOfNotification", 15 -- Duration )

End.
