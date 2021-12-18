# johndotfiles
These are my current dotfiles for the sway window manager. Be sure that if a directory has a README file to read it so that you don't miss any of my configs.
In order for the screenshot keybinds to properly work, you must also install both the grim and slurp package.

For those who are using Macbook Pros, you can download the macfanctld package for fan detection. Its default configuration is the same as apple's, so your fans should work fine after you run the daemon. I have not included the line for them to run at startup due to the fact that many people are starting to use other init systems which are not systemd. In order to have macfanctld run on startup, you'll need to configure it for your specific init system. Alternatively, you can simply open a terminal on a workspace you dont usually use and run "mcf" in that terminal to enable the daemon.
