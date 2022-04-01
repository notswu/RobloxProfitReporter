# RobloxProfitReporter

<html>
  <body>
    Get a profit report every so often on how much robux you've made / lost. (In RAP)

    --- Config Explanation ---

    The config for this program is pretty simple. I can run you through it.
    
    UserId - Your roblox UserID. You can get this by going to your profile on roblox and copying the numbers in the link.
    CheckTime - The amount of time the program should wait before sending another profit report. (In Seconds)
    Webhook - Your discord webhook.
    Username - The username that webhook will have.
    Message - The message the program will send to your webhook. This is where you should put pings like @everyone or @Recrucity
    Title - The title of the embed.


    --- Example Config ---

    [main]
    userid = 249228070
    checktime = 86400

    [discord]

    webhook = https://discord.com/api/webhooks/959526308482805780/hB4KMPZZ7hOC3qYJJJdVcujXj76jFJRG9TY_tQhfKwHGI-lTx_shdFkA1oymMNppw2v8
    username = Profit Reporter
    message = Profit Report! @everyone
    title = Profit Report!
    
    - Message me on Discord if you have an questions. Recrucity#4040 -
  </body>
</html>
