# gwfox: Custom Firefox CSS for macOS & Windows  
*Clean, modern UI tweaks for Firefox 138+ with optional features for enhanced usability and native look on Windows and macOS*

![Preview GIF](https://github.com/rakhalfps/gwfox-css/raw/8c88a3494879b8712ccd79a18131166667e9a27e/Media/preview.gif)

---

## How to Install

1. **Copy Files**  
Place the downloaded `chrome` folder into your Firefox **profile folder**.

2. **Change Settings**  
Go to `about:config` in Firefox and update these preferences:

- Set to `true`:
  - `toolkit.legacyUserProfileCustomizations.stylesheets`
  - `svg.context-properties.content.enabled`
  - `widget.windows.mica` *(Windows only)*
  - `widget.windows.mica.toplevel-backdrop` → set to `2` *(Windows only)*

- Set to `false`:
  - `sidebar.animation.enabled`
  - `widget.macos.native-context-menus` *(optional, macOS)*

3. **Restart Firefox**

---

## Optional Feature

To enable extra style tweaks (like bottom bookmarks toolbar and sidebar address bar), create a new Boolean preference in `about:config`:

- Name: `gwfox.plus`  
- Value: `true`

---

## Notes

- *Windows/macOS only* features are marked.  
- Backup your Firefox profile before changing settings.

---

## Screenshots

![Screenshot 1](https://github.com/rakhalfps/gwfox-css/raw/e89275a979284036e0ae046faaf521f20d3aaf1e/Media/1.png)  
![Screenshot 2](https://github.com/rakhalfps/gwfox-css/raw/e89275a979284036e0ae046faaf521f20d3aaf1e/Media/2.png)

---

## Related Repository

For more info and latest updates, visit:  
[gwfox on GitHub](https://github.com/akkva/gwfox)

---

Enjoy your cleaner Firefox UI!
