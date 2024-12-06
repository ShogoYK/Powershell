# Dependencies
Before cloning this repo, install the dependencies:
- [scoop](#scoop)
- [Terminal Icons](#terminal-icons)
- [NerdFonts](#nerd-fonts) (or any font to be compatible with terminal icons and oh-my-posh)
- [oh-my-posh](#oh-my-posh)

## [scoop]
Docs here: https://scoop.sh/
Installation: 

```
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
Invoke-RestMethod -Uri https://get.scoop.sh | Invoke-Expression
```

## [Terminal Icons]
Docs here: https://www.powershellgallery.com/packages/Terminal-Icons/0.9.0
Installation: 

```
Install-Module -Name Terminal-Icons -RequiredVersion 0.9.0
```

## [Nerd Fonts]
Docs here:https://www.nerdfonts.com/
Installation for this one I'm not sure, but a caveman way is:

```
wget https://github.com/ryanoasis/nerd-fonts/releases/download/v3.3.0/Hack.zip -P $HOME\Downloads
```

## [oh-my-posh]
Docs here: https://ohmyposh.dev/
Installation:

```
winget install JanDeDobbeleer.OhMyPosh -s winget
```

## Clone this repo!!!

Usually this folder is located in C:\<UserName>\Documents
Or, sometimes when windows is windowing: C:\<UserName>\OneDrive\Documents
Either way, we'll do it by:

SSH:

```bash
git clone git@github.com:ShogoYK/Powershell.git $HOME/Documents/
```

HTTPS:
```bash
git clone https://github.com/ShogoYK/Powershell.git $HOME/Documents/
```
