# BDRP_CustomChatCommands

- This script is completely primitive
- It is very easy to work with it and add new commands
- The script contains command / discord but you can easy create next command 

#BDRP_Client.lua create next commands
- For example you need command /web or teamspeak3 no problem:

1,You copy the original and paste it one line lower


RegisterCommand("discord", function ()
    TriggerEvent("chatMessage", "^8 [The name of your server]" .. " ^6 Discord: ^7 ^_Yours discord adress")
end) --/discord

RegisterCommand("web", function ()
    TriggerEvent("chatMessage", "^8 [The name of your server]" .. " ^6 WEB: ^7 ^_Yours Yours website")
end) --/web

