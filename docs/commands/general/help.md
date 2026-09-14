---
id: help
title: /help
slug: /commands/help
---

# /help

This command is used to get information about a command, or if not specified, a list of available commands.

### Command Usage {#usage}

The help command is called with a specified command to get information about it.
If no command is specified, a list of available commands to the user will be displayed.

| command       | command (optionnal) |
| ------------- | ----------------- |
| `/help`       | `[(command)]`     |

### Command Result {#result}

**If a command is specified**, informations and usage methods will be shown.
The shown information is from [Pixtoka's documentation](https://docs.pixtoka.xyz) site.

**If no command is specified**, a list of the available commands for the user depending on his current permission will be displayed.
Some other informations like bot status and links will be added if enabled.

:::tip
To customize what is displayed to user using this command. Type `/setup help` and follow the bot instructions. Visit the [`/setup`](/administration/setup) command page to learn more.
:::