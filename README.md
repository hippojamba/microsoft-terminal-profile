# microsoft-terminal-profile
```json
{
  "globals": {
    "alwaysShowTabs": true,
    "defaultProfile": "{2c4de342-38b7-51cf-b940-2309a097f518}",
    "initialCols": 120,
    "initialRows": 30,
    "keybindings": [
      {
        "command": "closeTab",
        "keys": [
          "ctrl+w"
        ]
      },
      {
        "command": "newTab",
        "keys": [
          "ctrl+t"
        ]
      },
      {
        "command": "newTabProfile0",
        "keys": [
          "ctrl+shift+1"
        ]
      },
      {
        "command": "newTabProfile1",
        "keys": [
          "ctrl+shift+2"
        ]
      },
      {
        "command": "newTabProfile2",
        "keys": [
          "ctrl+shift+3"
        ]
      },
      {
        "command": "newTabProfile3",
        "keys": [
          "ctrl+shift+4"
        ]
      },
      {
        "command": "nextTab",
        "keys": [
          "ctrl+tab"
        ]
      },
      {
        "command": "openSettings",
        "keys": [
          "ctrl+,"
        ]
      },
      {
        "command": "prevTab",
        "keys": [
          "ctrl+shift+tab"
        ]
      },
      {
        "command": "scrollDown",
        "keys": [
          "ctrl+shift+down"
        ]
      },
      {
        "command": "scrollDownPage",
        "keys": [
          "ctrl+shift+pgdn"
        ]
      },
      {
        "command": "scrollUp",
        "keys": [
          "ctrl+shift+up"
        ]
      },
      {
        "command": "scrollUpPage",
        "keys": [
          "ctrl+shift+pgup"
        ]
      },
      {
        "command": "switchToTab0",
        "keys": [
          "alt+1"
        ]
      },
      {
        "command": "switchToTab1",
        "keys": [
          "alt+2"
        ]
      },
      {
        "command": "switchToTab2",
        "keys": [
          "alt+3"
        ]
      },
      {
        "command": "switchToTab3",
        "keys": [
          "alt+4"
        ]
      },
      {
        "command": "switchToTab4",
        "keys": [
          "alt+5"
        ]
      }
    ],
    "requestedTheme": "system",
    "showTabsInTitlebar": true,
    "showTerminalTitleInTitlebar": true,
    "wordDelimiters": " ./\\()\"'-:,.;<>~!@#$%^&*|+=[]{}~?\u2502"
  },
  "profiles": [
    {
      "acrylicOpacity": 0.5,
      "closeOnExit": true,
      "colorScheme": "One Half Dark",
      "commandline": "wsl.exe -d Ubuntu",
      "cursorColor": "#FFFFFF",
      "cursorShape": "bar",
      "fontFace": "Consolas",
      "fontSize": 10,
      "guid": "{2c4de342-38b7-51cf-b940-2309a097f518}",
      "historySize": 9001,
      "icon": "ms-appx:///ProfileIcons/{9acb9455-ca41-5af7-950f-6bca1bc9722f}.png",
      "name": "Ubuntu",
      "padding": "0, 0, 0, 0",
      "snapOnInput": true,
      "startingDirectory": "C:/Projects",
      "useAcrylic": false
    },
    {
      "acrylicOpacity": 0.5,
      "background": "#012456",
      "closeOnExit": true,
      "colorScheme": "Campbell",
      "commandline": "powershell.exe",
      "cursorColor": "#FFFFFF",
      "cursorShape": "bar",
      "fontFace": "Consolas",
      "fontSize": 10,
      "guid": "{61c54bbd-c2c6-5271-96e7-009a87ff44bf}",
      "historySize": 9001,
      "icon": "ms-appx:///ProfileIcons/{61c54bbd-c2c6-5271-96e7-009a87ff44bf}.png",
      "name": "Windows PowerShell",
      "padding": "0, 0, 0, 0",
      "snapOnInput": true,
      "startingDirectory": "%USERPROFILE%",
      "useAcrylic": false
    },
    {
      "acrylicOpacity": 0.75,
      "closeOnExit": true,
      "colorScheme": "Campbell",
      "commandline": "cmd.exe",
      "cursorColor": "#FFFFFF",
      "cursorShape": "bar",
      "fontFace": "Consolas",
      "fontSize": 10,
      "guid": "{0caa0dad-35be-5f56-a8ff-afceeeaa6101}",
      "historySize": 9001,
      "icon": "ms-appx:///ProfileIcons/{0caa0dad-35be-5f56-a8ff-afceeeaa6101}.png",
      "name": "cmd",
      "padding": "0, 0, 0, 0",
      "snapOnInput": true,
      "startingDirectory": "%USERPROFILE%",
      "useAcrylic": true
    }
  ],
  "schemes": [
    {
      "name": "Campbell",
      "background": "#0C0C0C",
      "black": "#0C0C0C",
      "blue": "#0037DA",
      "brightBlack": "#767676",
      "brightBlue": "#3B78FF",
      "brightCyan": "#61D6D6",
      "brightGreen": "#16C60C",
      "brightPurple": "#B4009E",
      "brightRed": "#E74856",
      "brightWhite": "#F2F2F2",
      "brightYellow": "#F9F1A5",
      "cyan": "#3A96DD",
      "foreground": "#F2F2F2",
      "green": "#13A10E",
      "purple": "#881798",
      "red": "#C50F1F",
      "white": "#CCCCCC",
      "yellow": "#C19C00"
    },
    {
      "name": "One Half Dark",
      "background": "#282C34",
      "black": "#282C34",
      "blue": "#61AFEF",
      "brightBlack": "#5A6374",
      "brightBlue": "#61AFEF",
      "brightCyan": "#56B6C2",
      "brightGreen": "#98C379",
      "brightPurple": "#C678DD",
      "brightRed": "#E06C75",
      "brightWhite": "#DCDFE4",
      "brightYellow": "#E5C07B",
      "cyan": "#56B6C2",
      "foreground": "#DCDFE4",
      "green": "#98C379",
      "purple": "#C678DD",
      "red": "#E06C75",
      "white": "#DCDFE4",
      "yellow": "#E5C07B"
    },
    {
      "name": "Solarized Dark",
      "background": "#073642",
      "black": "#073642",
      "blue": "#268BD2",
      "brightBlack": "#002B36",
      "brightBlue": "#839496",
      "brightCyan": "#93A1A1",
      "brightGreen": "#586E75",
      "brightPurple": "#6C71C4",
      "brightRed": "#CB4B16",
      "brightWhite": "#FDF6E3",
      "brightYellow": "#657B83",
      "cyan": "#2AA198",
      "foreground": "#FDF6E3",
      "green": "#98C379",
      "purple": "#D33682",
      "red": "#D30102",
      "white": "#EEE8D5",
      "yellow": "#B58900"
    }
  ]
}
```
