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
`MD`         🠖  **EU**

<br>

### Header Based

- The header may include several regions.
- The region will be chosen depending on it's priority.

*May sometimes not work as not all **ROM**s use* <br>
*this mechanic, especially in **European** region.*

<br>
<br>

## More Features

<br>

- Option to choose between `YM2612` and `YM3438`

    *Changes Ladder Effect behavior.*
    
    <br>
    

- **Composite Blending**

    *Smooth dithering patterns in games.*
    
    <br>

- **Audio Filters**:
    
    <kbd> Model 1 </kbd> <kbd> Model 2 </kbd> <kbd> Minimal </kbd> <kbd> No Filter </kbd>
    
    <br>
    
- **Sprite Limit**
    
    *Enables more sprites.*
    
    <br>
    
- **Multitaps**:

    <kbd> Team player </kbd> <kbd> J-Cart </kbd> <kbd> 4-way </kbd>

    <br>

- **CPU Turbo**
    
    *Mitigates slowdowns.*

    <br>

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
