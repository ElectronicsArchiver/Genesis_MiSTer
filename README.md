# Genesis MiSTer

Port of ***[FPGAGen]*** *to the* ***[MiSTer]*** *platform.*

<br>

## Install

1. Copy all  `.rbf`  files to the root folder of an **SD Card**.

2. Place your **ROM**s into the  `Genesis`  folder.

    *Allowed Formats:*   <kbd> BIN </kbd> <kbd> GEN </kbd> <kbd> MD </kbd> 

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

### Header Based

A header can specify multiple regions and their <br>
priority to indicate in what order they are chosen.

*May sometimes not work as not all **ROM**s use* <br>
*this mechanic, especially in **European** region.*

<br>

### File Extension

| Type  | Region 
|:-----:|:------:
| `.BIN` | ***JP***
| `.GEN` | ***US***
| `.MD`  | ***EU***

<br>
<br>

## More Features

<br>

- Option to choose between `YM2612` and `YM3438`

    *Changes Ladder Effect behavior.*
    
- **Composite Blending**

    *Smooth dithering patterns in games.*
    
- **Audio Filters**:
    
    <kbd> Model 1 </kbd> <kbd> Model 2 </kbd> <kbd> Minimal </kbd> <kbd> No Filter </kbd>
    
- **Sprite Limit**
    
    *Enables more sprites.*
    
- **Multitaps**:

    <kbd> Team player </kbd> <kbd> J-Cart </kbd> <kbd> 4-way </kbd>

- **CPU Turbo**
    
    *Mitigates slowdowns.*

- **SVP Chip**
    
    *Virtual Racing*

<br>


<!----------------------------------------------------------------------------->

[FPGAGen]: https://github.com/Torlus/fpgagen
[MiSTer]: https://github.com/MiSTer-devel/Main_MiSTer/wiki
