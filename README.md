# Prepare the Development Environment for Macbook
Installation steps of required programs into Macbook to prepare it to develop software

# 1 - Install favourite browser
### Mozilla Firefox for Mac: https://www.mozilla.org/en-US/firefox/mac/
### Google Chrome: https://www.google.com/chrome/

# 2 - Install Homebrew [1]

### Run the command in terminal:

`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`

It also installs "Command Line Tools for Xcode"

# 3 - # Install OpenJDK [1]

`brew install openjdk`

If you see "zsh: command not found: brew" error in terminal [2], probably it was caused by, homebrew was saved in "/opt/homebrew/", and not in "/usr/local/...."

To fix it, run the command:
`export PATH=/opt/homebrew/bin:$PATH`


References:

[1] - https://stackoverflow.com/questions/64788005/java-jdk-for-the-apple-silicon-chips

[2] - https://stackoverflow.com/questions/36657321/after-installing-homebrew-i-get-zsh-command-not-found-brew/71919315

[3] - 

[4] - 

[5] - 
