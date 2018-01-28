![logo](https://i.imgur.com/294uZ8G.png)
# PC Control bot

Through this bot you can execute actions on your PC directly from Telegram!

This bot is available in English and Italian.

## Getting Started

### Prerequisites

Python 2.7, an [Imgur client ID](https://api.imgur.com/)
and a [BotFather](https://t.me/BotFather) token

GNU/Linux users: you need to install the python-tk package

### Run at startup
Windows: press the Windows key+R and type ```shell:startup```, then add a link to the pyw file into the startup folder.

## Setup the bot

Launch the setup with ```python bot_setup.pyw```

Select your language from the options menu and add your tokens.

Install requirements.

Now start it!

![setup](https://i.imgur.com/JJBVG9I.png)

## Set the permissions

Click the "Change user permissions" button to add or remove someone from the allowed users.\
Just insert the wanted Telegram username (write it without @) and select if you want to add the permissions or
remove them

Example:

![privs](https://i.imgur.com/DyL2F8w.png)

You're ready!

### Available commands

| Command | Description | Note
| --- | --- | --- |
| /shutdown | Shutdown your PC |
| /reboot | Reboot your PC |
| /logout | Log out from your current account | Currently not working on Linux |
| /hibernate | Hibernate your PC |
| /cancel | Annul the previous command | It work with the first two commands_t |
| /check | Check the PC status |
| /launch | Launch a program | Example: /launch notepad |
| /link | Open a web link | Example: /link http://google.com (don't use "www") |
| /memo | Show a memo on your pc |
| /task | Check if a process is currently running or kill it| Example: /task chrome |
| /screen | Take a screenshot and receive it through Imgur |
| /menu | Shows the inline menù |
| /kb or /keyboard | Brings the normal keyboard up |

You can set a delay time for the execution of the first four commands by using _t + time in seconds after a command.\
Example: ```/shutdown_t 20```

## Contributors
Thanks to [Jasoc](https://github.com/jasoc) for the awesome [logo](https://i.imgur.com/V6B5ZEf.png)!