HOW TO USE 

1. Clone this repo to your machine
2. Set up your ~/.zshrc to read the bashrc inside the repo. Like,

```bash
vi ~/.zshrc
```

Insert this line at the bottom:
```bash
export DOTFILES=LOCATION_OF_CLONED_REPO
source $DOTFILES/bashrc
```


Replace LOCATION_OF_CLONED_REPO by the actual location of cloned dotfiles, for me it is 
```bash
export DOTFILES=~/dotfiles
source $DOTFILES/bashrc
```

Note - The alias `e` (setup in `bash/aliases`) wont work if the above location is named anything other than `$DOTFILES`.
