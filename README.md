# git-url-vim
A vim plugin to create a url to specific repo, branch + line number.    

## Purpose
Uses hotkey `\gu` to create github url to branch, file, and line number of file + line currently being edited.
   
The url is then on your clipboard for sharing. Also, a url link to click in the lower left hand corner appears.

## Installation
I recommend to install with pathogen:
```
cd ~/.vim/bundle
git clone https://github.com/tkjef/git-url-vim
```

If you don't have Pathogen installed here is the repo with installation instructions:  
https://github.com/tpope/vim-pathogen

## Use
Once installed you can use the default hotkey of `<leader>gu` when editing a file.   
Default `<leader>` is `\` so use `\gu` if you haven't altered your leader.  
This creates a github url to the branch, file, and line number you're currently on and puts it on your clipboard.  
It will also be provided in the lower left hand corner to be clicked on.

![https://github.com/tkjef/git-url-vim/blob/master/vim-github-urls_screenshot.png](https://github.com/tkjef/git-url-vim/blob/master/vim-github-urls_screenshot.png)
