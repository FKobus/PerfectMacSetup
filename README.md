# PerfectMacSetup
All the tools you need on a new mac! And how to install them at the moment of this writing.

## Start with installing the following applications:

### HomeBrew
The missing package manager for every mac
https://brew.sh/

```
# run in your terminal
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

### iTerm2
iTerm is a better performant terminal than the one that comes out of the box with your mac.
- https://www.iterm2.com/

### fish (optional)
If you don't like bash, or want to use something more intuitive, give fish a try.
https://fishshell.com/

```
# run in your terminal
brew install fish
echo '/usr/local/bin/fish' | sudo tee -a /etc/shells
chsh -s `which fish`
```
Close your terminal and reopen for your new fish shell.

### Oh-my-fish
https://github.com/oh-my-fish/oh-my-fish

```
curl -L https://get.oh-my.fish | fish
```

> **&lt;code like a pro&gt;**<br>
 I'm using fish with oh-my-fish and my own [feest](https://github.com/FKobus/theme-feest) theme. Install is super easy and can be done with one command: `omf install https://github.com/FKobus/theme-feest`<br>
 `omf theme feest`<br>
 **&lt;/code like a pro&gt;**<br>

### Spectacle
Don't worry anymore about your window management.
https://www.spectacleapp.com/

### BeardedSpice
Do you develop with headphones? Then this is a must have!
https://beardedspice.github.io/

### VS Code
https://code.visualstudio.com/

### Docker
https://store.docker.com/editions/community/docker-ce-desktop-mac
(I'm using edge)

### KeePassX
https://www.keepassx.org/

### Sequel Pro
https://www.sequelpro.com/

### Slack
https://slack.com/

## Tweaking your mac
After installing the necessary applications it't time to tweak your mac.

### Changing the hostname
```
sudo scutil --set HostName <HOSTNAME>
```

