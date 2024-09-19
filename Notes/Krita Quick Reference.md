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

## Input Device Tips / Tricks

- [Drawing Tablet Quick Reference](Notes/Drawing%20Tablet%20Quick%20Reference.md)
- [Trackpad Quick Reference](Notes/Trackpad%20Quick%20Reference.md)

## Android Tablet Tips / Tricks

An important note: the settings dialog may be too big horizontally for a small android tablet screen. You can drag the top of the window to move it left/right/up/down to access the full window. This is especially important on Samsung Z Fold devices.

On a small tablet it can be wise to use the full screen canvas view and pop-up palette. This allows you to use the whole screen with your stylus and easily access different brushes and recently used colors. Note: the pop-up palette will show your favorite brushes by default and which brushes it shows, as well as how many to show, can be configured within the main Krita settings.

### General Settings

^0f3b48

- general
    - window
        - disable HiDPI support
    - tools
        - tool options location: in toolbar
        - disable 'enable touch painting'
    - misc (when krita starts)
        - show session manager
        - save session on exit
- canvas input settings (use a non default profile / see above for saving fix)
    - look for any gestures/touch/pen stuff that needs removing
    - show pop up widget
        - set gesture to 'two finger tap'
	- pan canvas
		- set gesture to 'five finger drag'
    - zoom canvas
        - set gesture to 'five finger tap'
    - touch gestures
        - set gesture undo to 'four finger drag'
        - set gesture redo to 'four finger tap'
        - set gesture toggle canvas mode to 'three finger tap'
- tablet settings
    - adjust pressure curve
- pop-up palatte
    - disable show rotation ring (if desired)
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

## KemoNine's Device/Input Config

The below are the main hid settings KemoNine uses with a Samsung Android tablet plus S Pen, Wacom One (Small) drawing tablet and a Logitech T650 track pad. They only use these 3 devices for working with Krita and have tuned their config accordingly.

### Device Configs

The following are the device configs KemoNine uses within each device's setup/config tool(s).

- [Wacom One (Small) Drawing Tablet](Notes/Drawing%20Tablet%20Quick%20Reference.md#^163d42)
- [Logitech T650 Trackpad](Notes/Trackpad%20Quick%20Reference.md#^9233aa)
- [Samsung Z Fold 4](Notes/Krita%20Quick%20Reference.md#^0f3b48)

### Krita Input Config

The below are the input settings KemoNine uses within Krita

- S Pen
	- Click: Toggle pop-up palette with S-Pen
	- Double click: show canvas only
	- All other options set to 'do nothing'
- Canvas Input Settings
	- Remove /all/ but the below
	- Tool invocation
		- Mouse Button - Left Button - Activate
		- Key Combination - Return - Confirm
		- Key Combination - Esc - Cancel
	- Alternate Invocation - All shortcuts removed
	- Change Primary Setting - All shortcuts removed
	- Pan Canvas
		- Mouse Button - Space + Left Button - Pan Mode
	- Rotate Canvas - All shortcuts removed
	- Zoom Canvas
		- Gesture - Five Finger Tap - Zoom Mode
	- Show Popup Widget
		- Mouse Button - Right Button - Activate
		- Gesture - Two Finger Tap - Activate
	- Select Layer - All shortcuts removed
	- Exposure and Gamma - All shortcuts removed
	- Switch Time - All shortcuts removed
	- Zoom and Rotate Canvas
		- Gesture - Two Finger Drag - Rotate Mode
	- Touch Gestures
		- Gesture - Four Finger Tap - Redo
		- Gesture - Four Finger Drag - Undo
		- Gesture - Three Finger Tap - Toggle Canvas Only Mode

## Screenshots

### Main Krita View With File Open

![](Notes/attachments/Imagepipe_359.jpg)

### Canvas View

![](Notes/attachments/Imagepipe_360.jpg)

### Pop-up Palette

![](Notes/attachments/Imagepipe_361.jpg)
