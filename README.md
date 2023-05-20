# FIREFOXSIMPLECSS

A simple customization to your firefox 

- custom logo
- custom wallpaper and wordmark for newtab 
- more coming 

## Instalation :
### Windows :

1. In the searchbar type `about:config`. A dialog will be shown to you. Press the **I accept the risk** button.
2. Search for **`toolkit.legacyUserProfileCustomizations.stylesheets`**, **`layers.acceleration.force-enabled`**, **`gfx.webrender.all`**, and **`svg.context-properties.content.enabled`**. Change them to **True**
3. Go to your Firefox profile:
    - If you're on Linux: `$HOME/.mozilla/firefox/XXXXXXX.default-release/`
    - If you're on Windows: `C:\Users\<USERNAME>\AppData\Roaming\Mozilla\Firefox\Profiles\XXXXXXX.default-XXXXXX`
    - If you're on MacOS: `Users/<USERNAME>/Library/Application Support/Firefox/Profiles/XXXXXXX.default-XXXXXXX` 
4. Move the `chrome` folder into the directory.
5. Make all the customizations you want.
6. Enjoy!
### Linux :
In the searchbar type `about:config`. A dialog will be shown to you. Press the **I accept the risk** button.
```sh
cd .mozilla/firefox/[yourprofileid].default-realase
```
replace [yourprofileid] with your profile id in firefox 
```sh
mkdir chrome && cd chrome
```
```sh 
git clone https://github.com/Danialdev01/FirefoxSimpleCSS.git
```
```sh 
cd FirefoxSimpleCSS 
```
```sh
mv img ../ && mv userChrome.css ../ && mv userContent.css ../
