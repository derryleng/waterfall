# Waterfall

Fork of a fork of a firefox theme.

Main features:
- When width > 1440px, puts tabs and address bar on one line
- No default buttons hidden
- Clean UI
- Dark theme only

## Installation

- In the ```about:config``` page on your Firefox browser, set the following parameters to **True** :
  - ```toolkit.legacyUserProfileCustomizations.stylesheets```
  - ```layers.acceleration.force-enabled```
  - ```gfx.webrender.all```
  - ```svg.context-properties.content.enabled```
- Copy the userChrome.css file from this repository to your **chrome** folder. You can find the **chrome** folder here :
  - On Linux : ```$HOME/.mozilla/firefox/######.default-release/chrome/```
  - On Windows : ```C:\Users\[USERNAME]\AppData\Roaming\Mozilla\Firefox\Profiles\######.default-release\chrome\```
  - On MacOS : ```Users/[USERNAME]/Library/Application Support/Firefox/Profiles/######.default-release/chrome```
  - If it doesn't exist already create a folder called chrome

## Authors:

- Andreas Grafen (original cascade theme) (https://andreas.grafen.info)
- Clément Rambaud (mods on the original file for a mouse-centered use)
‎
## License

See [LICENSE](LICENSE).
