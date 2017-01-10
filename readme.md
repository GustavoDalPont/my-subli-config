# How to setup

## First have Sublime text 3 installed with package control installed


### if (me) {
```
cd ~/.config/sublime-text-3/Packages
git init
git remote add origin git@github.com:GustavoDalPont/my-subli-config.git 
# https://github.com/GustavoDalPont/my-subli-config.git
git fetch
git reset --hard origin/master
```


### } else if (not me) {
```
cd ~/.config/sublime-text-3/Packages
git init
git remote add https://github.com/GustavoDalPont/my-subli-config.git
git fetch
git reset --hard origin/master
```
### }
