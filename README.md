![image](https://gitlab.com/xXBlackMaskXx/sss/raw/master/ScreenShots.png)

# ScreenShots Script

As the name suggests, this is a screenshoting script... yeah... revealing, I know ;P

## Installation

```shell
$ git clone https://gitlab.com/xXBlackMaskXx/sss
$ cd sss
$ cp screenshot.sh [wherever you want]
```

### Dependencies

| Required?  | Package name       | Description
|------------|--------------------|------------
| Yes        | git                | Distributed version control system
| Yes		 | maim	              | Utility to take a screenshot
| Yes (No?)  | ttf-font-awesome   | Iconic font designed for Bootstrap
| Yes (or...)| dmenu              | Generic menu for X
| (...or) Yes| rofi (+ rofi-dmenu)| A window switcher, application launcher and dmenu replacement

#### Recommended dmenu

```shell
$ git clone https://gitlab.com/xXBlackMaskXx/dmenu
$ cd dmenu
$ sudo make clean install
```