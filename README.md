🧰 Chest Counter for Fortnite

For those of you searching for the "One Piece" (the golden token from the Pirate Shop) and wanting to keep track of how many chests you’ve opened, this tool will make the process easier. I created it with the help of Claude and have done some testing, but if you run into any issues or bugs, please let me know—I’ll try to release an updated version with those fixes. Good luck! (I’m just as desperate to find that token as you are, which is exactly why I built this tool! :'c)

✨ What it does

- Counts every chest you loot: normal, rare and spirit chests, with or without the "Search" prompt.
- Counts chests you break open with your pickaxe, too (you can turn this off in Settings).
- Only YOUR chests: chests opened by teammates or other players don't count.
- Total and daily history: a big total, today's count, a 14-day chart and a list of every day you played.
- Works on its own: each match is counted about 2 minutes after it ends, even if you jump straight into the next one with "Play again".
- Keeps your disk clean: it can delete old replays once they've been counted.
- 5 languages: English, Español, Português, Français and Deutsch.

🛡️ Safe by design

Chest Counter never touches the game. It doesn't inject anything, read memory or modify files.
It only reads the replay files Fortnite already saves on your PC after every match. Inside those replays, the game records which player opened each chest, and that's how it knows which ones were yours.

🚀 Getting started
In Fortnite, go to Settings → Game → Replays and turn on Record Replays (Battle Royale).
Download ChestCounter.zip from the Releases page.
Right-click the ZIP → Extract All… and pick any folder you like (for example, your Documents).

⚠️ Don't run it from inside the ZIP. Extract it first, or it won't be able to start.
- Open the ChestCounter folder and double-click Start Chest Counter.bat.
- No Python? It will offer to install it for you.
- The first launch sets up the replay reader. This takes 2–5 minutes and only happens once.
- If Windows shows a blue "Windows protected your PC" screen, click More info → Run anyway. This happens with most small tools that aren't from a big company.
- Play! Keep the app open (minimized is fine) and watch your total grow. 📈
- Not sure about something? Click the ? button in the app for a quick guide.

📋 Requirements
Windows 10 or 11
Python 3 (installed automatically if missing)
About 300 MB of free space for .NET 10, downloaded automatically on first run (no admin rights needed)

💡 Good to know
Chests destroyed with explosives from far away (more than ~8 m) can't be credited to you, because Fortnite doesn't store your own hits in the replay.
When the app gets a smarter reader, it re-reads your matches. Your total may go down a little while it fixes old counts.
Made a mistake or opened chests with replays turned off? Use Manual correction (−1 / +1).
Your data lives in %APPDATA%\ChestCounter. To uninstall, delete the app folder, %APPDATA%\ChestCounter and %LOCALAPPDATA%\ChestCounter.

🙏 Credits
Replay parsing is powered by FortniteReplayDecompressor by Shiqan and its fork MoreFortniteReplayDecompression by Cristiano3120 (MIT license).

⚖️ License & disclaimer
Released under the MIT License. Chest Counter is a fan-made tool and is not affiliated with or endorsed by Epic Games. Fortnite is a trademark of Epic Games, Inc.
