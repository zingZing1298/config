# config
config for terminals, nvim, etc

# Install wsl
wsl --install Ubuntu

# Install oh-my-posh
winget install JanDeDobbeleer.OhMyPosh -s winget

Set env path:
$env:Path += ";C:\Users\user\AppData\Local\Programs\oh-my-posh\bin"

Upgrade default theme:
winget upgrade JanDeDobbeleer.OhMyPosh -s winget

Get MINGW and Zig through Choco
choco install zig
choco intall mingw
