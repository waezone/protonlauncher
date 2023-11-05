# Proton Launcher
Because running other things along side a game is hard.
## How to use.
Be sure you have steam installed, and at least 1 version of Proton installed.
Run your windows executable as such  
`./protonlauncher [command]`  
If you want to run an application along side something launched normally with steam, you can specify the appID of what you launched.
`./protonlauncher -i [appID] [command]`  
And if it was run with a specific proton version.
`./protonlauncher -v [protonver] -i [appID] [command]`  
Heres a real example  
`./protonlauncher -v 8.0 -i 220 "LiveSplit.exe"`  
This command runs LiveSplit.exe with proton version 8.0, along side Half-Life 2 already launched from steam.
So now LiveSplit's autosplitting feature can read the memory of Half-Life 2 to autosplit.
