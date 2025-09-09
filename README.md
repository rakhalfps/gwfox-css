# GWFOX: Modern Transparent UI for Firefox!

<p align="center">
  <img src="https://github.com/rakhalfps/gwfox-css/blob/a48c59d71b99a00244582478ce7df9ab29cbfebe/Media/PREVIEW.png?raw=true" alt="GWFOX preview" width="750"/>
</p>

---

> [!WARNING]
> This is a **forked version** with **Windows transparency** enabled.  
> Some transparency features may affect web page rendering.  
> Only download releases from this repository to avoid unofficial or malicious copies.  
> We do **not** have an official Discord or other distribution channels.

---

> [!NOTE]
> **Features of GWFOX Forked Edition:**
> - Windows 11 transparency (Mica & Acrylic)  
> - macOS-style UI layout  
> - Lightweight & distraction-free  
> - Optional macOS layout (`gwfox.plus`)  
> - Stripped, fast-loading fork  

---

> [!IMPORTANT]
> **Installation Instructions:**
> 1. Download the latest ZIP from [Releases](https://github.com/rakhalfps/gwfox-css/releases) or clone the repository.  
> 2. Open Firefox → `about:support` → **Open Folder** next to your profile.  
> 3. Copy the `chrome` folder and `user.js` file into your profile.  
> 4. Restart Firefox to apply changes.  

> [!TIP]
> - Make sure Firefox is **completely closed** before copying files.  
> - To enable transparency on **all websites**, install the **[Zen Internet](https://addons.mozilla.org/en-US/firefox/addon/zen-internet/)** Firefox add-on after GWFOX installation.

---

> [!NOTE]
> **Transparency Settings (`about:config`):**
> - `widget.windows.mica`  
> - `widget.windows.mica.popups` = 1 or 2  
> - `browser.tabs.allow_transparent_browser` ⚠️ May affect some web pages  

> [!INFO]
> These settings control Windows transparency and Acrylic blur effects. Only change them if you are familiar with `about:config`.

---

> [!IMPORTANT]
> **Configuration (`about:config`):**
> **Set to `true`:**  
> - `toolkit.legacyUserProfileCustomizations.stylesheets`  
> - `svg.context-properties.content.enabled`  
> - `widget.windows.mica` *(Windows only)*  
> - `widget.windows.mica.toplevel-backdrop = 2`  

> **Set to `false`:**  
> - `sidebar.animation.enabled`  
> - `widget.macos.native-context-menus` *(optional macOS)*  

> **Optional macOS-style layout:**  
> - `gwfox.plus = true`  

> [!TIP]
> Restart Firefox after changing configuration values to ensure all settings take effect.

---

**Optional macOS Layout:**  
Enable the Boolean pref `gwfox.plus = true` for a macOS-style toolbar layout.  
This only affects aesthetics; transparency features remain unchanged.

---

> [!NOTE]
> **Credits:**  
> Forked and enhanced from [gwfox by @akkva](https://github.com/akkva) to enable **Windows transparency** and **macOS effects**.

---

## Demo Video

Click the thumbnail below to watch a **full demo of GWFOX in action**:

[![GWFOX Demo](https://github.com/rakhalfps/gwfox-css/blob/a48c59d71b99a00244582478ce7df9ab29cbfebe/Media/PREVIEW.png?raw=true)](https://github.com/user-attachments/assets/193190a8-9bbe-4c23-818b-508e9927f636)


