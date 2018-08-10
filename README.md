# My Personal Spacemacs Config

## Installation

1. Install `emacs`
    * [Ubuntu PPA](https://launchpad.net/~kelleyk/+archive/ubuntu/emacs)
    * macOS:
        ```bash
        $ brew install emacs-plus
        $ ln -s /usr/local/opt/emacs-plus/Emacs.app/ /Applications/
        ```

1. Install the the [Nerd Fonts](https://github.com/ryanoasis/nerd-fonts)
1. Clone this repository, including submodules.
    ```bash
    $ git clone --recursive https://github.com/florian-jackisch/spacemacs-config.git
    ```
    
1. Link configuration files:
    ```bash
    $ ./setup.sh
    ```
    
1. Start `emacs`. This will download your packages.
