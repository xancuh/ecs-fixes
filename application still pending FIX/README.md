# application still pending
this is the most simplest fix. you will not need to go in your db and accept it that way, that's more complicated.

1. Go to "services/Roblox/Roblox.Website/Controllers/Internal" and open `BypassController.cs`.
2. Find somewhere to put it. I recommend you put it somewhere towards the bottom or below the first-second HttpGet thing.
3. Visit the terminal that is running `dotnet run` or `dotnet run --configuration Release` and do CTRL+C, then run the same command that it was running before.

Done!

Guide by **z9nj** on Discord.
Contact me for any inquiries. Do NOT message me about other fixes, they are on this repo. If they are not, just tell me.
