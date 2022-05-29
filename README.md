# Genesis MiSTer    [![Badge License]][License]    [![Badge Port]][Port]

Port of ***[SEGA Megadrive / Genesis]*** *to the* ***[MiSTer]*** *platform.*

<br>

## Install

1. Copy all `.rbf` files to the root folder of an **SD Card**.

2. Place your **ROM**s into the `Genesis` folder.

    *ROM Formats:* `BIN` , `GEN` , `MD` 

<br>
<br>

## Hotkeys

The following hotkeys reset the region.

<br>

| Key | Region | Type
|:---:|:------:|:----:
| <kbd> F1 </kbd> | ***JP*** | ***NTSC***
| <kbd> F2 </kbd> | ***US*** | ***NTSC***
| <kbd> F3 </kbd> | ***EU*** | ***PAL***

<br>
<br>

## Auto Region Selection

There are two versions of region detection.

<br>

### File Extension

`BIN`  🠖  **JP** <br>
`GEN`  🠖  **US** <br>
`MD`       🠖  **EU**

<br>

### Header Based

- The header may include several regions.
- The region will be chosen depending on it's priority.

*May sometimes not work as not all **ROM**s use* <br>
*this mechanic, especially in **European** region.*

<br>
<br>

## Other Features

- Option to choose between `YM2612` and `YM3438`

    *Changes Ladder Effect behavior.*
    

- **Composite Blending**

    *Smooth dithering patterns in games.*

- **Audio Filters**:
    
    - Model 1
    - Model 2
    - Minimal
    - No Filter
    
    
- **Sprite Limit**
    
    *Enables more sprites.*

- **Multitaps**:

    - Team player
    - J-Cart
    - 4-way


- **CPU Turbo**
    
    *Mitigates slowdowns.*

- **SVP Chip**
    
    *Virtual Racing*

<br>


<!----------------------------------------------------------------------------->

[SEGA Megadrive / Genesis]: https://en.wikipedia.org/wiki/Sega_Genesis
[MiSTer]: https://github.com/MiSTer-devel/Main_MiSTer/wiki
[Port]: https://github.com/Torlus/fpgagen

[License]: LICENSE


<!--------------------------------{ Badges }----------------------------------->

[Badge License]: https://img.shields.io/badge/License-GPL_3-blue.svg?style=for-the-badge
[Badge Port]: https://img.shields.io/badge/Port_Of-FPGAGen-EF2D5E.svg?style=for-the-badge