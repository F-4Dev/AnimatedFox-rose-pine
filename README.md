# ✨ AnimatedFox Rosé Pine ✨
A minimal Firefox theme with a hidden URL bar and satisfying animations. (originally by [RemyIsCool](https://github.com/RemyIsCool))

![image](https://github.com/user-attachments/assets/ff9b33e6-8eb8-4b4b-bacf-466ae3752379)


If you want the same colors as the screenshot [(Rosé Pine)](https://rosepinetheme.com/), install [Firefox Color](https://addons.mozilla.org/en-US/firefox/addon/firefox-color), then click [this link](https://color.firefox.com/?theme=XQAAAAKRAQAAAAAAAABBqYhm849SCia73laEGccwS-xMDPr3WmqH6mLhhyRv-nu52zZ2ZXxbtAepG2Aokh1Ejdb1z3vrcjLsdAKABouvjElgsj_nFz6MQxH2HRXLob_aSHZCs-03dPBFDf6tPSs9IqYQstQ2Cbw-qOTEPMNK3ejQcbczf4LZTVpiOe9JSd9ix_m31iP9q97cT8kzzlHgkCa4xCvSugNadk4FxHf7Csqg4PVC6q5qfb0JnI0tyV6nqN_23o0FiIWCfD4nN1vFq4skKEYXLQVpZXuw87O8_hn6bCVjGn5MEww-8ezpXrdZ20ZS9hUa3OLWgsv_yQh1Vg
).

## Home Screen
I use the [mtab](https://github.com/maxhu08/mtab) extension with this [config](https://raw.githubusercontent.com/F-4Dev/AnimatedFox-rose-pine/refs/heads/main/mtab-config.txt).

---

## 🖥️ Requirements
 - 🦊 An up-to-date version of Firefox or LibreWolf. Other Firefox derivatives might work but I haven't tested them.
 - 🔤 [JetBrains Mono](https://www.jetbrains.com/lp/mono/) installed on your system. (If it's not installed, it will default to the default monospace font for Firefox.)

## ⬇️ Installation
1. ✅ Make sure you have everything listed in Requirements.
2. ⚙️ Enable `toolkit.legacyUserProfileCustomizations.stylesheets` in [about:config](about:config).
3. 📁 Go to about:support and copy the profile directory path.
4. ⌨️ Clone this repository into a directory called `chrome` inside the profile directory you just copied:
```bash
cd the/path/you/just/copied
git https://github.com/F-4Dev/AnimatedFox-rose-pine.git chrome
```
7. 📑 Hide the bookmarks toolbar by pressing Ctrl+Shift+B or right clicking and selecting "Never Show."
8. ❌ Right click the toolbar and select "Customize Toolbar." If you want it to look like it does in the screenshot, make it look like this:
  ![what it should look like](https://github.com/RemyIsCool/AnimatedFox/assets/97812130/9dbeae08-4705-48f4-848e-14acddde42a2) Make sure to set the titlebar density to normal and not touch.

10. 🔄 Restart your browser for the theme to be applied.

## ⚙️ Configuration

The following options can be set in about:config:

| Option          | Preference
| :-------------- | :---
| Centered Tabs   | `animatedFox.centeredTabs`  
| Centered URL    | `animatedFox.centeredUrl`  
| Square Corners (All browser elements have square corners)  | `animatedFox.squareCorners`
| Rounded Corners (Rounded corners around page content. Not compatible with square corners) | `animatedFox.roundedCorners`
| Hide Single Tab | `animatedFox.hideSingleTab`
| Show Tab Close Button (on hover) | `animatedFox.showTabCloseButton`

## 🔃 Updating
1. 📁 Go to about:support and copy the profile directory path.
2. ⌨️ Run `git pull` in the `chrome` folder:
```bash
cd the/path/you/just/copied/chrome
git pull
```
3. 🎨 Re-install the Firefox Color theme if you installed it.

## 👾 Known Issues
 - Moving around tabs is very buggy. You should instead use the keyboard shortcuts ctrl+shift+page up/down.
 - Customizing the toolbar doesn't work with the theme applied. You'll need to disable it, make your changes, and enable it again.
 - Color themes with transparency usually don't work well.

If anyone knows how to fix these issues, feel free to submit a pull request.
