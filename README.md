# gwfox: Clean, Modern Firefox Interface for macOS & Windows!

**gwfox** is a lightweight, modern UI tweak for **Firefox 142+**, designed for a clean, distraction-free browsing experience.  
Supports **macOS** and **Windows 11** with native Mica effects.

<p align="center">
  <img src="https://github.com/rakhalfps/gwfox-css/blob/a48c59d71b99a00244582478ce7df9ab29cbfebe/Media/PREVIEW.png?raw=true" alt="gwfox preview" width="750"/>
</p>

---

## Installation

1. Download the latest release ZIP from [here](https://github.com/rakhalfps/gwfox-css/releases) or clone this repository.  
2. Open Firefox, go to `about:support`, click **Open Folder** next to **Profile Directory**.  
3. Copy the `chrome` folder and `user.js` file into your profile folder (overwrite if needed).  
4. Restart Firefox.

---

## Configuration (`about:config`)

Set these to `true`:  
- `toolkit.legacyUserProfileCustomizations.stylesheets`  
- `svg.context-properties.content.enabled`  
- `widget.windows.mica` *(Windows only)*  
- `widget.windows.mica.toplevel-backdrop` = `2`

Set these to `false`:  
- `sidebar.animation.enabled`  
- `widget.macos.native-context-menus` *(optional on macOS)*

Restart Firefox.

---

## Optional macOS-style Layout

Create a Boolean pref:  
- `gwfox.plus` = `true`

---

## Credits

Based on [gwfox by @akkva](https://github.com/akkva/gwfox), enhanced with layout and style improvements.

---

[▶️ Demo video](https://github.com/user-attachments/assets/193190a8-9bbe-4c23-818b-508e9927f636)
