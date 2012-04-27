zsh-syntax-highlighting
==========================================================================================================

**[Fish shell](http://www.fishshell.com) like syntax highlighting for [Zsh](http://www.zsh.org).**

*Requirements: zsh 4.3.9 or superior.*

## Install it


### In your ~/.zshrc

* Download the script or clone this repository:

      git clone git://github.com/nlevchuk/zsh-syntax-highlighting.git

* Source the script **at the end** of `~/.zshrc`:

      source /path/to/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh

* Source `~/.zshrc`  to take changes into account:

      source ~/.zshrc


### With oh-my-zsh

* Download the script or clone this repository in [oh-my-zsh](http://github.com/robbyrussell/oh-my-zsh) plugins directory:

      cd ~/.oh-my-zsh/plugins/
      git clone git://github.com/nlevchuk/zsh-syntax-highlighting.git

* Activate the plugin in `~/.zshrc` (in **last** position):

      plugins=( [plugins...] zsh-syntax-highlighting)

* Source `~/.zshrc`  to take changes into account:
    
      source ~/.zshrc
