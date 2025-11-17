# w_am_digiscanner_reh – Metal Detector Prop Replace

This repository provides a **replacement for the default GTA V prop `w_am_digiscanner`**, used as a metal detector.  
The resource is plug-and-play and only contains the streamed model files — no scripts or configuration required.

---

## Repository Structure

w_am_digiscanner_reh/
├── fxmanifest.lua
├── README.md
└── stream/
├── w_am_digiscanner_reh.ydr
└── w_am_digiscanner_reh.ytyp

The `stream/` folder contains the custom prop files that will replace the original model.

---

## Installation (FiveM)

1. Place the resource folder inside your `resources/` directory.

2. Ensure your `fxmanifest.lua` looks like this:

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
Add the resource to your server.cfg:

ensure w_am_digiscanner_reh
Restart your server.
Any script or mapping that uses the original w_am_digiscanner prop will automatically display this custom model.

Usage
No edits are needed in your scripts.
The replacement works automatically as soon as the resource is streamed.

Credits
Model / Replace: Reh

Resource Setup: (fill in if needed)

License
Free to use for any FiveM project as long as credits stay intact.
Commercial redistribution of the model is forbidden without explicit authorization from the author.

markdown