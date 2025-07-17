# gwfox: Minimal Elegance for Firefox (Unofficial)

**gwfox** is a lightweight, modern UI customization for **Firefox 138+**, designed to offer a cleaner, distraction-free browsing experience.  
Fully compatible with **macOS** and **Windows**, including native **Mica integration** on **Windows 11**.

<p align="center">
  <img src="https://github.com/rakhalfps/gwfox-css/blob/a48c59d71b99a00244582478ce7df9ab29cbfebe/Media/PREVIEW.png?raw=true" alt="gwfox preview" width="750"/>
</p>

---

## 🛠️ Installation

1. **Download** this repository as a ZIP or clone it.  
2. Open your Firefox **profile directory**:  
   - Visit `about:support` in the address bar.  
   - Click **"Open Folder"** next to **"Profile Directory"**.  
3. Copy the `chrome` folder and `user.js` file into your profile directory.  
   - Overwrite existing files if prompted.  
4. **Restart Firefox**.

> ✅ Your profile folder should now include:  
> - `/chrome/userChrome.css`  
> - `/chrome/userContent.css`  
> - `user.js`

---

## ⚙️ Configuration

Open `about:config` in Firefox and modify the following preferences:

### Set to `true`
- `toolkit.legacyUserProfileCustomizations.stylesheets`  
- `svg.context-properties.content.enabled`  
- `widget.windows.mica` *(Windows only)*  
- `widget.windows.mica.toplevel-backdrop` → `2`  

### Set to `false`
- `sidebar.animation.enabled`  
- `widget.macos.native-context-menus` *(optional on macOS)*  

Restart Firefox to apply changes.

---

## ✨ Optional Enhancements

Unlock additional macOS-inspired layout refinements:

- Address bar moved to sidebar  
- Bookmarks bar hidden at the bottom  
- Compact layout with macOS-style window controls  

To enable:  
1. Open `about:config`  
2. Add a new Boolean preference:  
   - Name: `gwfox.plus`  
   - Value: `true`

---

## 🙏 Credits

This customization is based on the original [gwfox](https://github.com/akkva/gwfox) by **@akkva**.  
This version builds on it with refined layouts and aesthetic improvements.

---

[▶️ Click here to view the WebM demo](https://github.com/user-attachments/assets/193190a8-9bbe-4c23-818b-508e9927f636)
