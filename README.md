# google-voice-desktop-app fork

## Why a fork?
I forked this project because I saw a lot of cool PR's that weren't getting merged, so I built a fork with them included.

___

## Why
I'm annoyed at the lack of desktop app for voice, like hangouts had.

## What does it do
It just lets you keep voice open without a chrome browser. It will also check the dom for notifications and display a badge in the task bar and closing the app will send it to a tray instead of closing.

## Support
Currently supports both OSX, Windows 10 & Linux

Questions? Ideas? Join us in discord https://discord.gg/3SSS6vkKET

## Install
Go to the [Releases Page](https://github.com/Jerrkawz/google-voice-desktop-app/releases) and download the release for your OS.

Simply uzip and drag into the applications folder (mac) or run the executable (windows) or run the app image (ubuntu)

**Mac Note: The mac version is unsigned, so you will have to click "Open Anyway" after running, or go to Settings > Security & Privacy > General > Open Anyway. Sorry not paying for a dev license just for this**


**Linux Note: You will have to make the AppImage executable in order to run it. Right Click > Properties > Permissions > Allow Executing file as a program**

## Themes
New in 1.1 we now have different themes! You can change your theme by clicking on the customize menu on the left side of the page

![Customize](/screenshots/customize.png?raw=true)

Not only themes but also a system for themeing! If you want to create your own theme and contribute back to the project you can do that [here](THEMES.md)

## Run From Source
`git clone https://github.com/reesericci/google-voice-desktop-app.git`

`npm install`

`electron .`

To build yourself you can run
`electron-builder --linux` or `electron-builder --mac` or `electron-builder --windows`

## Attributions
<div>Customize Icon made by <a href="https://www.flaticon.com/authors/dmitri13" title="dmitri13">dmitri13</a> from <a href="https://www.flaticon.com/" title="Flaticon">www.flaticon.com</a></div>

Dracula https://github.com/dracula/dracula-theme

Solar / Minty / Cerulean https://bootswatch.com/
