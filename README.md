# BDRP_CustomChatCommands_FiveM

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

Now you have two commands in a chat /discord and /web.

In a TriggerEvent we can find this ^8 or this ^_ this is colors font.
Colors you can find here: https://forum.cfx.re/t/chat-formatting-colors-bold-underline/67641
