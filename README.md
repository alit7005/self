# [SelfBot](https://telegram.me/alit7005)

Professional SelfBot Based On NEW TG-CLI


* * *

## Commands

| Use help |
| [#!/]help | just send help in your group and get the commands |

**You can use "#", "!", or "/" to begin all commands

* * *

# Installation

```sh
# Let's install the self-bot.
cd $HOME
git clone https://github.com/alit7005/self.git
cd self
chmod +x beyond.sh
./beyond.sh install
./beyond.sh # Enter a phone number & confirmation code.
```
### One command
To install everything in one command, use:
```sh
cd $HOME && git clone https://github.com/alit7005/self.git && cd self && chmod +x beyond.sh && ./beyond.sh install && ./beyond.sh
```

* * *

### Sudo And Bot

Open ./bot/bot.lua and add your ID to the "sudo_users" section in the following format:
```
    sudo_users = {
    365910979,
    0,
    YourID
  }
```
add your ID at line 4 and 131 in bot.lua
Then restart or reload.


# Developers!

[ali](https://github.com/alit700) ([Telegram](https://telegram.me/alit7005))
