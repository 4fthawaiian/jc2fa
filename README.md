# Command line 2fa

# Requirements

* https://github.com/lastpass/lastpass-cli (`brew install lastpass-cli` on mac)
* https://www.nongnu.org/oath-toolkit/ (`brew install oath-toolkit` on mac)

# Setup

* replace `jctotp` with whatever your string is named in lastpass in `jc2fa` script
* replace `lastpass@mccroreys.com` with your lastpass username in `getpwd` script
* place both files in `~/bin` and make sure the directory is in your path
* store the key for your jumpcloud 2fa in lastpass (I use the string `jctotp` for mine, but whatever works). 
* You can generate a new string in the jumpcloud console:

<img src="jc.png">

# Note:
You will need to use your lastpass password to retrieve the key for the jc2fa script. The session will last for a while,but I generally have to enter my password several times in a day's work. 

<img src="example.gif">
