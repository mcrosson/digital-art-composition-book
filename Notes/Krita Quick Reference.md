---
tags:
  - note
  - quick-reference
source: "N/A"
created_at: 2024-09-13
---

```table-of-contents
title: **Table of Contents**
```

---

## Brushes, Palettes & More

- [brush] Bic ballpoint: [https://krita-artists.org/t/cheap-ballpoint-pen-brush/17170](https://krita-artists.org/t/cheap-ballpoint-pen-brush/17170)
- [brush] Copic Markers: [https://krita-artists.org/t/realistic-copic-marker-like-brushes/41203](https://krita-artists.org/t/realistic-copic-marker-like-brushes/41203)
- [brush] Graphite: [https://krita-artists.org/t/graphite-brushes-for-the-new-pattern-blend-modes/28036](https://krita-artists.org/t/graphite-brushes-for-the-new-pattern-blend-modes/28036)
- [brush] Sketch Pencils: `RM_Sketch_V1.bundle` from [https://files.kde.org/krita/extras/](https://files.kde.org/krita/extras/)
- [brush] Charcoal: `Charcoal_KA.bundle` from [https://files.kde.org/krita/extras/charcoal/](https://files.kde.org/krita/extras/charcoal/)
- [palate] copic marker colors: [https://raw.githubusercontent.com/maborotopia/Krita_resources/master/copic322_color.gpl](https://raw.githubusercontent.com/maborotopia/Krita_resources/master/copic322_color.gpl)
- [palate] copic colors (more robust): [https://www.deviantart.com/d-signer/art/All-358-COPIC-Digital-Marker-Colours-ASE-ACO-GPL-765188823](https://www.deviantart.com/d-signer/art/All-358-COPIC-Digital-Marker-Colours-ASE-ACO-GPL-765188823)

## Logitech T650 Tips / Tricks

- point and click tab
  - primary click: click with one finger
  - right click: click with 2 fingers
  - middle click: disabled
  - pointer movement: disabled
  - enable dragging: disabled
- naviage windows tab
  - disable everything
- scroll tab
  - enable vertical scrolling
  - enable horizontal scrolling
  - disable back/forward
  - enable zoom in and out
- krita settings
  - add undo & redo to main toolbar
  - canvas input settings
    - remove non-modified mouse wheel options from 'zoom canvas'
    - add mouse wheel left/right/up/down to pan canvas

## Small Tablet Tips / Tricks

An important note: the settings dialog may be too big horizontally for a small android tablet screen. You can drag the top of the window to move it left/right/up/down to access the full window. This is especially important on Samsung Z Fold devices.

On a small tablet it can be wise to use the full screen canvas view and pop-up palette. This allows you to use the whole screen with your stylus and easily access different brushes and recently used colors. Note: the pop-up palette will show your favorite brushes by default and which brushes it shows, as well as how many to show, can be configured within the main Krita settings.

### Multi-touch / Gestures

- Two finger tap: activate pop-up palette
- Three finger tap: toggle canvas only mode
- Four finger drag: Undo
- Four finger tap: redo

### General Settings

- general
    - window
        - disable HiDPI support
    - tools
        - tool options location: in toolbar
        - disable 'enable touch painting
    - misc (when krita starts)
        - show session manager
        - save session on exit
- canvas input settings (use a non default profile / see above for saving fix)
    - look for any gestures/touch/pen stuff that needs removing
    - show pop up widget
        - set to 'two finger tap'
    - zoom canvas
        - set gesture to five finger tap
    - touch gestures
        - set undo to four finger drag
        - set redo to four finger tap
        - set toggle canvas mode to three finger tap
- tablet settings
    - adjust pressure curve
- pop-up palatte
    - disable show rotation ring
- s pen actions
    - click: toggle pop up palette with s-pen
    - double click: show canvas only
    - gestures: set all to do nothing

### Things to consider

- bug fix input profile settings: [https://krita-artists.org/t/cannot-save-input-profile-does-not-persist-on-startup-on-android/55693/4](https://krita-artists.org/t/cannot-save-input-profile-does-not-persist-on-startup-on-android/55693/4)
- s pen click button is mouse middle click on galaxy fold devices
- pop up palatte _is_ quick settings (like sketchbook puck)
- gestures in the config can likely do brush size up/dn and undo/redo
- can tune brush settings shown via the pop up palatte ui
- go through favorite brushes and set up to 10 ; these will show on the popup palatte
- use portrait mode when editing brushes ; you need the height to see everything and you can use the top of the pop-up window to move it left/right for full access

### External storage resources folder on Android

- export/prep everything you want to keep (reuse desktop default resources dir if desired)
- settings -> resources
- use the ICON that pops the android folder selector
- select the folder you want to use and grant storage permissions to it
- save settings & quit krita
- force stop krita in app settings
- (ONLY IF REIMPORTING EXPORTS) - relaunch krita and import data
- copy the resources dir you want to use to the selected folder
- launch krita. this _will_ take awhile and may look like its frozen
- clear any warnings/errors
- quit krita
- force stop krita
- relaunch and enjoy

## Screenshots

### Main Krita View With File Open

![](Notes/attachments/Imagepipe_359.jpg)

### Canvas View

![](Notes/attachments/Imagepipe_360.jpg)

### Pop-up Palette

![](Notes/attachments/Imagepipe_361.jpg)
