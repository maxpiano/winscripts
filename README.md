# Winscripts
*scripts and infos to make a windows machine ready for development*
## Links
* [EN International Keyboard without dead keys](https://github.com/thomasfaingnaert/win-us-intl-altgr/releases/download/v1.0/us-inter.zip)
* [Scoop Package Manager](https://github.com/lukesampson/scoop)
## Commands
- create hard link for .ideavimrc *(run in cmd)*
```
mklink /h C:\Users\{USER}\.ideavimrc C:\Users\{USER}\winstuff\phpstorm\.ideavimrc
```
## [Scoop](https://github.com/lukesampson/scoop)
- install scoop *(run in powershell)*
```
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
iwr -useb get.scoop.sh | iex
```
- add buckets
```
scoop bucket add extras
```
- install apps
```
scoop install vcredist2015
scoop install neovim
```