# **AUTO CHESS API (krnl edition)**

Hahaha make yourself look smart by using hacks in a lego game

Do big-brain chess moves automatically

Only tested on krnl :)

Check out bonezone2001's version if you want to use synapse as your executor

## **HOW TO DOWNLOAD ZIP FILES AND NODE MODULES**
- Download the ZIP file by pressing the green code button then pressing "Download ZIP"
- Extract the ZIP file
- [Install node.js if you don't already have it](https://nodejs.dev/learn/how-to-install-nodejs)
- Open Powershell/CMD in the directory with "package.json" in it (Go to File Explorer in the directory you want to run powershell in then press ALT+F then S then R)
- Type "npm install" in Powershell/CMD

## **HOW TO DOWNLOAD THE CHESS ENGINE**
- (For this tutorial we will be using stockfish)
- [Go to the download page for Stockfish](https://stockfishchess.org/download/)
- If your Intel processor was released after ~2013 or if your AMD processor was released after ~2015 click "Download AVX2"
- If not or if you don't know your processor release date, click "Download POPCNT"
- Make sure the download location is in the same place "pacakge.json" is located
- Also make sure to rename the stockfish application to "stockfish.exe"

## **HOW TO RUN THE AUTOCHESSAPI**
- Run the command "node ." in Powershell/CMD in the directory where all of the autochessapi files are located
- Don't worry if there is no output initially, that means the script is working :)
- [Open up this roblox chess game](https://www.roblox.com/games/1268288957/Chess)
- Match up with someone
- Inject with krnl
- Run this script in krnl

```
shared.runBind = Enum.KeyCode.B;
loadstring(game:HttpGet('https://raw.githubusercontent.com/AutomatingLife/leechesbelike/main/ChessLoader'))()
```
- Press the move keybind on your turn (Deafult is "B") to have the chess engine move for you :D
- Enjoy destroying 9 year olds in chess! :)
