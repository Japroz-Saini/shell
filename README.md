# shell
My Shell Config
```bash
fortune | cowsay -f tux
PS1="\W $ "

export BASH_SILENCE_DEPRECATION_WARNING=1
# Setting PATH for Python 3.8
# The original version is saved in .bash_profile.pysave
PATH="/Library/Frameworks/Python.framework/Versions/3.8/bin:${PATH}"
export PATH

# Setting PATH for Python 3.8
# The original version is saved in .bash_profile.pysave
PATH="/Library/Frameworks/Python.framework/Versions/3.8/bin:${PATH}"
export PATH

# Setting PATH for Python 3.8
# The original version is saved in .bash_profile.pysave
PATH="/Library/Frameworks/Python.framework/Versions/3.8/bin:${PATH}"
export PATH
export PATH="/usr/local/opt/mysql-client/bin:$PATH"

export PATH="$HOME/.yarn/bin:$HOME/.config/yarn/global/node_modules/.bin:$PATH"
alias tree="find . -print | sed -e 's;[^/]*/;|____;g;s;____|; |;g'"                                                                                                                         
```
Brew Installs:
```bash
brew install iterm2
brew install fortune
brew install cowsay

## After this add the `.bash_profile` by entering the following command

cd
vim .bash_profile
```
