# w_am_digiscanner_reh – Metal Detector Prop Replace

This repository provides a **replacement for the default GTA V prop `w_am_digiscanner`**, used as a metal detector.  
The resource is plug-and-play and only contains streamed model files — no scripts or configuration required.

---

## Preview

**Metal Detector (Model Preview):**  
![Preview 1]([https://rex-studio.com/RexStudio/other/metaldetector.png](https://rex-studio.com/RexStudio/other/metaldetector.png))

**Image 2 (Model Preview 2):**  
![Preview 2]([https://rex-studio.com/RexStudio/other/metaldetector.png](https://rex-studio.com/RexStudio/other/metaldetector2.png))

(Replace `URL_TO_IMAGE_1` and `URL_TO_IMAGE_2` with your uploaded image links.)

---

## Repository Structure

```
Metaldetector_props/
├── fxmanifest.lua
├── README.md
└── stream/
    ├── w_am_digiscanner_reh.ydr
    └── w_am_digiscanner_reh.ytyp
```

The `stream/` folder contains the custom prop files that replace the original model.

---

## Installation (FiveM)

1. Place the resource folder inside your `resources/` directory.

2. Use this `fxmanifest.lua`:

```lua
fx_version 'cerulean'
game 'gta5'

name 'w_am_digiscanner_reh'
description 'Metal detector prop replacement'
author 'YourName / Reh'
version '1.0.0'

files {
    'stream/w_am_digiscanner_reh.ytyp'
}

data_file 'DLC_ITYP_REQUEST' 'stream/w_am_digiscanner_reh.ytyp'
```

3. Add the resource in your server.cfg:
```cfg
ensure Metaldetector_props
```

4. Restart your server.  
   The default prop will now be replaced by the custom model.

---

## Usage

No script change is required.  
Any script, mapping or scenario using the default **w_am_digiscanner** prop will automatically show this custom model.

---

## Credits

- Model / Replace: **Reh**  
- Resource Setup: *(add your name if needed)*

---

## License

Free to use on any FiveM server as long as credits remain intact.  
Commercial redistribution of the model is forbidden without explicit permission from the author.
