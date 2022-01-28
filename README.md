


> **DISCLAIMER**  
> This is an old repo.  
> I changed my strategy a while ago.  
> [Here the new repo](https://github.com/jesuswasrasta/dotfiles)




# GitEnvironment
My personal Git setup for Windows (Git aliases, Bash shell aliases and so on)

## How to use
Starting from here, consider <home> as your user folder (C:\Users\<username>).  

Copy/merge these files in <home> folder:
* .bash_profile
* .bashrc
* .gitattributes
* .gitconfig
* .gitexcludes

## MinTTY
MinTTY saves its configuration into <home>\.minttyrc file
Then it saves other stuff into <home>\.mintty\ folder;
For istance, themes are in <home>\.mintty\themes.  

Copy there the content of the user folder in this repo
to use these MinTTY configurations.  

## Customizing Bash prompt
I don't like user@computer stuff in Bash prompt, nor
the unuseful MINGW string, so I deleted them.  
To modify default Git Bash prompt, edit this file:
C:\Program Files\Git\etc\profile.d\git-prompt.sh

Here there is mine.  
