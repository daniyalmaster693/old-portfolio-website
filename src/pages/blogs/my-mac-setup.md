---
layout: ../../layouts/Blog Post Layout.astro
pageTitle: "My Mac Setup"
title: "My Mac Setup"
pubDate: "2025-02-28"
readingTime: "7 Min"
---

<img src="/Mac Setup.webp" alt="Mac Setup">

## Initial Setup

Here are some of the first things I recommend doing when setting up a new Mac:

- Before you start using it, update it to the latest version of Mac OS
- Check the specs of your machine, to make sure their the same as what you bought
- Test all the basic functions of the device to make sure everything is working properly
- Check your battery health and warranty to make sure everything is correct (you should have 100% battery health if it's a new Mac and 1 year of limited Apple Warranty)

Now for some settings:

- Go to Settings > Network > Enable Firewall
- Settings > Battery > Options > Set Wake for Network Access to Never
- Settings > Desktop & Dock > Enable Automatically hide and show the Dock
- Settings > Notifications > Go through and disable all notifications except apps where you want to receive notifications such as Calendar
- To improve Touch ID Login, you can scan the same finger multiple times to make scanning faster and more accurate

### Control Center and Menu Bar

- Settings > Control Center > Set All Control Center Modules to Don't Show in Menubar, except for Wifi
- Under Other Modules > Check show Percentage for Battery
- Check Show Keyboard Brightness in Control Center
- Set Spotlight, Siri and Time Machine to Don't Show in Menu Bar

### Display

- Settings > Displays > Night Shift > Set Schedule to Sunset to Sunrise
- Enable turn on until sunrise
- Disable Automatically Adjust Brightness
- Set the temperature to about halfway between less warm and the middle point

### Keyboard

- Settings > Keyboard > Set Key Repeat Rate to the max setting
- Set delay until repeat to the shortest setting for the best typing experience

### Trackpad

- Settings > Trackpad > Enable Tap to click
- Set click speed to medium
- Set tracking speed to 6 (3 less then the fastest speed)

### Privacy

- Settings > Privacy & Security > Analytics & Improvements > Disable everything
- Under privacy & security > Apple Advertising > Disable personalized ads

### Safari Settings

- Homepage > Edit > Disable everything except use same start page on all devices
- Settings > General > Set Safari Opens to New Window
- Settings > General > Set File download location to downloads folder
- Settings > Tabs > Set Tab Layout to Compact and Check always show website titles in tabs

## Most Used Keyboard Shortcuts

- Command + M - Minimize a window
- Command + Q - Quit an app fully
- Command + W - Close an app window
- Command + Comma - Open an app's settings
- Command + Backtick - Cycle through the open windows of the active app
- Command + Backspace - Deletes an entire line
- Option + Backspace - Deletes an entire word
- Option + Arrow Left or Right - Move the cursor word by word instead of letter by letter
- Command + Arrow Left or right - Move the cursor line by line
- Option + Shift + Arrow Left or Right - Select words faster
- Option + Shift + Volume up or down - Allows more precise control over the volume
- Option + Shift + Brightness up or down - Allows more precise control over the brightness
- Control + Command + Q - Lock you screen instantly

## Apps

<img src="/Launchpad Apps.webp" alt="Launchpad Apps">

Coming from Windows, I always loved finding new apps to improve my setup, and streamlining workflows. That's why when I decided to get a Mac, one of the factors I considered was the superior availability of apps, and launcher such as Raycast. Nonetheless, here are the apps I have installed on my Mac:

- Raycast (launcher of choice and much more, checkout my blog post about my Raycast Setup for more information)
- Dropover (superior drag and drop)
- Monitor Control (control the brightness of external displays)
- Command X (Brings the cut and paste functionality to macs)
- Hidden Bar (Hides menu bar items)
- Scrcpy (Screen mirror your android to your Mac)
- Daily (Daily agenda app)
- Localsend (Cross Platform File Sharing App)
- Visual Studio Code (Code editor of choice)
- Obsidian (Markdown Editor of choice)
- AdGuard for Safari (Ad Blocking)
- Spotify (Music)
- Firefox Developer Edition (Separate browser for Development)
- Zoom (Meetings)
- ChatGPT (easy access AI)

## Other Tweaks and Development Related Packages

- Install Homebrew using your terminal, an easy to use package manager
- Install Git for Version Control
- Install NPM and Node JS
- Install Jet Brains Mono Font

## Visual Studio Code

- Make sure you downloaded the Apple Silicon version for best performance
- Theme: Theme by Mhammed Talhaouy
- Font: Jet Brains Mono

### Extensions

- Code Spell Checker
- Astro
- Auto Rename Tag
- Fluent Icons
- Live Server
- Markdown Preview Enhanced
- Material Icon Theme
- Prettier - Code Formatter
- Code Runner
- Quokka.js

### Settings

<img src="/Visual Studio Code.webp" alt="Visual Studio Code">

"editor.autoClosingBrackets": "always",<br>
"editor.fontLigatures": true,<br>
"editor.fontSize": 13,<br>
"editor.tabSize": 2,<br>
"editor.smoothScrolling": true,<br>
"terminal.integrated.smoothScrolling": true,<br>
"workbench.list.smoothScrolling": true,<br>
"breadcrumbs.enabled": false,<br>
"workbench.activityBar.location": "top",<br>
"workbench.editor.tabActionCloseVisibility": false,<br>
"editor.formatOnSave": true,<br>
"editor.stickyScroll.enabled": false,<br>
"window.commandCenter": false,<br>
"workbench.layoutControl.enabled": false,<br>

## Other Tips

- Uninstall Garage Band (assuming you don't use it) to save almost a gigabyte of space
- To remove items from the menu bar, hold command while dragging them out (works for most items)
- Remove extra items in your finder sidebar, for easier access
- Remove all default apps from the dock, and add only apps that you use (assuming you use the dock, and not a launcher)

### Hot Corners

<img src="/Hot Corners.webp" alt="Launchpad Apps">

- Set up hot corners in Settings > Desktop & Dock > Hot Corners
- You can add a modifier key to trigger each action by holding down a modifier key while selecting an action
- Under Desktop & Dock > Disable Tiled windows have margins if you use the default window snapping in Mac OS Sequoia (15)
- Personally I have one set up to lock my screen if I hold command and drag my cursor to any corner of the display

### Apple Shortcuts

<img src="/Apple Shortcuts Startup Apps.webp" alt="Apple Shortcut">

- Toggle off all startup apps. Instead create a shortcut to open whatever apps you need, and run it after you login. This saves system resources and is slightly more inconvenient, a worth it tradeoff imo.

### Finder

- If you want to download an image from a website on Safari, you can open your developer tools > Sources > and the image should be listed in the list > right click on it > open in new window > then right click on download it
- You can remove backgrounds from images and select the subjects directly from the right click menu (across your mac too)
- You can also compress files and convert between formats directly in finder
- Inside of Finder click on view from the menu bar > uncheck show tab bar > check show tool bar, path bar, and status bar

### Dragging Windows

Run this command in terminal:

- defaults write -g NSWindowShouldDragOnGesture -bool true`

Then restart your Mac. This allow you to move a window by pressing control + command while dragging from anywhere on the window

## Conclusion

Mac OS is a very powerful OS with plenty of great features built in and hidden. This guide only scratches the surface of what is possible, but gives you enough to get you going. Hope you enjoyed!
