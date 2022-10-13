# Prepare the Development Environment for Macbook
Installation steps of required programs into Macbook to prepare it to develop software

# 1 - Install favourite browser
### Mozilla Firefox for Mac: https://www.mozilla.org/en-US/firefox/mac/
### Google Chrome: https://www.google.com/chrome/

# 2 - Install Homebrew [1]

### Run the command in terminal:

`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`

It also installs "Command Line Tools for Xcode"

# 3 - Install JDK 17

### Download *Arm 64 DMG Installer* from:
https://www.oracle.com/java/technologies/downloads/#jdk17-mac

### Installing the JDK on macOS
https://docs.oracle.com/en/java/javase/16/install/installation-jdk-macos.html#GUID-F575EB4A-70D3-4AB4-A20E-DBE95171AB5F

### Uninstalling the JDK on macOS
https://docs.oracle.com/en/java/javase/16/install/installation-jdk-macos.html#GUID-F9183C70-2E96-40F4-9104-F3814A5A331F

# 4 - Install Homebrew in M1 Mac

Homebrew is an open-source package manager for macOS that offers an easy way to install software and tolls through the command line. If you are a coder, developer, Terminal lover, or more tech-savvy than an average Mac user, you can use Homebrew to simplify software installation on your Mac. [1]

Run the commands in order:
`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`

The you will see a prompt as:

"*==> Next steps:*"

"*Run these three commands in your terminal to add Homebrew to your PATH:*"

Run the commands in order. 

Now just run this command to be sure that everything is working: `brew help`

# 5 - Install iTerm2 + zsh + oh-my-zsh [2]

- Install iTerm2: `brew install iterm2 --cask`
- Install oh-my-zsh: `sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`

### Change Oh My Zsh Theme:

Open zsh source: `nano ~/.zshrc`

Change theme as: **ZSH_THEME="agnoster"**

Activate the change: `source ~/.zshrc`

### Install Powerline font [3]

- `git clone https://github.com/powerline/fonts.git --depth=1`
- `cd fonts`
- `./install.sh`
- `cd ..`
- `rm -rf fonts`

### Oh My Zsh Plugins: 

"Oh My Zsh comes bundled with plugins, which allow you to take advantage of functionality of many sorts to your shell just by enabling them."

The link: https://github.com/ohmyzsh/ohmyzsh/wiki/Plugins

# 6 - Install VS Code

https://code.visualstudio.com/download

Under Mac, click "**Apple Silicon**"

# 7 - Spectacle

Spectacle: https://www.spectacleapp.com/

# 8 - CMake

For M1: `arch -arm64 brew install cmake` 

# References:

[1] - https://www.igeeksblog.com/how-to-install-homebrew-on-mac/

[2] - https://medium.com/ayuth/iterm2-zsh-oh-my-zsh-the-most-power-full-of-terminal-on-macos-bdb2823fb04c

[3] - https://fmacedoo.medium.com/oh-my-zsh-with-powerline-fonts-pretty-simple-as-you-deserve-fbe7f6d23723

[4] - 

[5] - 
