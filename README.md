# Yo, guaringohabriel, I'm really happy for you, I'ma let you finish, but most of the commands are based on PHP which I hate or are just reinventing the square wheel, like brew list

# Mac CLI

 OS X command line tools for developers

![image](https://github.com/guarinogabriel/mac-cli/raw/master/demo/demo.gif)

The ultimate tool for developers to manage their Mac. It provides a huge set of command line commands that automate the usage of your OS X system.
When you run a function, the executed command is displayed and that helps you memorize each of the Utilities for future usage.

---

### Installation in 2 Simple Steps

1- Download command line tool to your local machine:
> `git clone https://github.com/guarinogabriel/mac-cli.git && cd mac-cli`

2- Run the installer. There are 2 install options:

The following command will install the minimum required dependencies:
> `sh mac install`

The following command will install all the dependencies and integrated projects:
> `sh mac install:all`

Re-open your terminal client. You will be able to run all the commands listed below, for example:
> `mac help`

---

### Configuration

Update the shell script to match your local environment configuration. Global variables are defined at the beginning of the file.

---

### Requirements

These are the requirements to be able to run all the commands (all the dependencies/requirements can be installed running "mac install"):

* Homebrew
* GIT
* PyPA (pip)
* Pipe Viewer (pv)
* Python

---

### Integrated Projects

The following amazing projects have been integrated on the mac script (all the integrated projects can be installed running `mac install:all`):
* Glances (https://github.com/nicolargo/glances)
* speedtest-cli (https://github.com/sivel/speedtest-cli)
---

### Commands List

| Command  | Description | Arguments |
| ------------- | ------------- | ------------- |
| `mac list`  | List all available commands in mac script  | |
| `mac list:general`  | List all general commands in mac script  | |
| `mac list:network`  | List all network commands in mac script  | |
| `mac list:performance`  | List all performance commands in mac script  | |
| `mac list:xcode`  | List all Xcode commands in mac script  | |

### General Commands

| Command  | Description | Arguments |
| ------------- | ------------- | ------------- |
| `mac install`  | Install all mac script dependencies to be able to run all commands  | |
| `mac install:all`  | Install all mac script dependencies and integrated projects  | |
| `mac update`  | Install OS X software updates, update installed Ruby gems, Homebrew, npm and their installed packages  | |
| `mac lock`  | Lock  | |
| `mac restart`  | Restart OS X  | |
| `mac sleep`  | Sleep mode  | |
| `mac shutdown`  | Shutdown  | |
| `mac time`  | Show clock at top right position in Terminal/iTerm  | |
| `mac screensaver`  | Start screensaver  | |
| `mac apps:close-all`  | Close all opened apps  | |
| `mac apps:app-store`  | Get list of installed apps from App Store  | |
| `mac eject-all`  | Eject all mounted volumes and disks  | |
| `mac battery:status`  | Get battery status  | |
| `mac info`  | Get OS X version information  | |


### Network Utilities

| Command  | Description |
| ------------- | ------------- |
| `mac speedtest`  | Internet connection speed test  |
| `mac speedtest:infinite`  | Run internet speed test each 5 minutes  |
| `mac ports`  | List of used ports  |
| `mac ip:local`  | Get local IP address  |
| `mac ip:public`  | Get public IP address  |


### Performance and maintenance Utilities

| Command  | Description |
| ------------- | ------------- |
| `mac system`  | Show system information to review mac performance  |
| `mac temp`  | Show temperature, fan and battery statistics  |
| `mac memory`  | See memory usage sorted by memory consumption  |
| `mac trash:empty`  | Empty trash |
| `mac trash:size`  | Calculate trash size |
| `mac downloads:cleanup`  | Remove all files and directories from Downloads directory |

### Xcode Utilities

| Command  | Description |
| ------------- | ------------- |
| `mac xcode:cleanup`  | Cleanup Xcode files to free up hard disk space  |
