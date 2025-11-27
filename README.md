# OPLAdvance Theme

<p align="center">
  <img src="https://github.com/PixeliGer/OPL-Theme-OPLAdvance/blob/main/assets/logo.png">
</p>

<div align = center>
  
  ![BUILT WITH](https://img.shields.io/badge/BUILT%20WITH-%E2%9D%A4-cd6133?labelColor=ff793f&style=for-the-badge&logoColor=f0f0f0)
  [![Made With GIMP](https://img.shields.io/badge/gimp-5C5543?style=for-the-badge&logo=gimp&logoColor=white&label=Made%20With)](https://www.gimp.org/)
  ![PS2](https://img.shields.io/badge/ps2-007acc?style=for-the-badge&logo=playstation&logoColor=white&label=Made%20For)
  ![Downloads](https://img.shields.io/github/downloads/PixeliGer/OPL-Theme-OPLAdvance/total?style=for-the-badge)

  [![Download Theme](https://custom-icon-badges.demolab.com/badge/-Download-35BF5C?style=for-the-badge&logo=download&logoColor=white)](https://github.com/PixeliGer/OPL-Theme-OPLAdvance/releases/latest)

</div>

Relive the **USBAdvance** days, where 'plug-and-play' often felt more like 'plug-and-pray.' This theme pays homage to the classic USBAdvance while reimagining it for the modern era—seamlessly blending nostalgia with the evolution of USB game loading on the PS2.

<div align = middle>
  <br>
  
  &ensp;[<kbd> <br> Installation <br> </kbd>](#-installation)&ensp;
  &ensp;[<kbd> <br> Features <br> </kbd>](#-features)&ensp;
  &ensp;[<kbd> <br> Screenshots <br> </kbd>](#-screenshots)&ensp;
  &ensp;[<kbd> <br> Recommendations <br> </kbd>](#-recommendations)&ensp;
  &ensp;[<kbd> <br> More Themes <br> </kbd>](https://pixeliger.github.io/opl-themes/)&ensp;
    
  <br>  
</div>

## 🌱 Inspiration

<p align="middle">
  <img width="48%" src="https://github.com/PixeliGer/OPL-Theme-OPLAdvance/blob/main/assets/inspiration/reference_1.png">
  <img width="48%" src="https://github.com/PixeliGer/OPL-Theme-OPLAdvance/blob/main/assets/inspiration/reference_2.png">
</p>

## ✨ Features

- A renewed version of a well-known classic
- A trip to the past but with the advantages of the most modern technology
- Working with HD/Full-HD on 16:9 and 4:3
- Compatible with the latest versions of [Open Ps2 Loader 1.2](https://github.com/ps2homebrew/Open-PS2-Loader/releases)

## 📸 Screenshots

##### Games List

<p align="middle">  
  <img width="48%" src="https://github.com/PixeliGer/OPL-Theme-OPLAdvance/blob/main/assets/screenshots/screenshot_1.png">
  <img width="48%" src="https://github.com/PixeliGer/OPL-Theme-OPLAdvance/blob/main/assets/screenshots/screenshot_3.png">
  <img width="48%" src="https://github.com/PixeliGer/OPL-Theme-OPLAdvance/blob/main/assets/screenshots/screenshot_5.png">
  <img width="48%" src="https://github.com/PixeliGer/OPL-Theme-OPLAdvance/blob/main/assets/screenshots/screenshot_7.png">
  <img width="48%" src="https://github.com/PixeliGer/OPL-Theme-OPLAdvance/blob/main/assets/screenshots/screenshot_9.png"> 
  <img width="48%" src="https://github.com/PixeliGer/OPL-Theme-OPLAdvance/blob/main/assets/screenshots/screenshot_11.png"> 
</p>

##### 🌟NEW🌟 Info Screen

<p align="middle">  
  <img width="48%" src="https://github.com/PixeliGer/OPL-Theme-OPLAdvance/blob/main/assets/screenshots/screenshot_2.png">
  <img width="48%" src="https://github.com/PixeliGer/OPL-Theme-OPLAdvance/blob/main/assets/screenshots/screenshot_4.png">
  <img width="48%" src="https://github.com/PixeliGer/OPL-Theme-OPLAdvance/blob/main/assets/screenshots/screenshot_6.png">
  <img width="48%" src="https://github.com/PixeliGer/OPL-Theme-OPLAdvance/blob/main/assets/screenshots/screenshot_8.png">
  <img width="48%" src="https://github.com/PixeliGer/OPL-Theme-OPLAdvance/blob/main/assets/screenshots/screenshot_10.png"> 
  <img width="48%" src="https://github.com/PixeliGer/OPL-Theme-OPLAdvance/blob/main/assets/screenshots/screenshot_12.png"> 
</p>

## 💾 Installation

**1. Initially, ensure your OPL folder is structured like this on your Device or in your Shared folder**

```
APPS/
ART/
CD/
CFG/
CHT/
DVD/
POPS/
THM/
VMC/
```

**2. Download one of the zip files that contains one of the Theme variants from the [Releases](https://github.com/PixeliGer/OPL-Theme-OPLAdvance/releases/latest) page or using the green `DOWNLOAD` button at the top, (make sure it's one with the `thm_` prefix in its name)**

```
thm_OPLAdvance
```

**3. Extract the ZIP file and move the theme folder to your `THM` directory.**

```
THM/
├─ thm_OPLAdvance/
```

> [!NOTE]  
> Themes must be placed inside a folder named `THM` (in uppercase) for any of the devices: SMB share, HDD, USB, SD (MX4SIO), once the device starts, OPL will list the themes found in these locations

- **SMB** (Network Share)

In the root directory or drive you set as your PS2SMB share, in a THM folder

```
PS2SMB/THM/thm_OPLAdvance/
```

- **USB**, **SD** device

In the root of the drive or partition set for OPL, in a THM folder

```
mass:/THM/thm_OPLAdvance/
```

- **HDD** (Internal hard drive)

Place the THM folder in the `OPL Partition` of the HDD `+OPL`, you can create the partition if it doesn't exist, by using `uLaunchELF`: [FileBrowser > MISC > HddManager]

```
hdd0:/+OPL/THM/thm_OPLAdvance/
```

> [!IMPORTANT]  
> Themes on any of these devices won’t display unless the device is enabled, so make sure to enable the device where your themes are stored through the OPL settings.

> [!WARNING]
> Avoid installing themes on the Memory Card, as their storage size can impact the proper functioning of the themes and cause issues with OPL.

**4. Launch OPL, if it was already open, restart it.**

**5. Go to `OPL Settings` and then `Display Settings`. In the `Theme` option, find and select your theme, then click `OK` to apply it.**

## 💡 Recommendations

To enhance your experience with the theme, consider these recommendations:

- Make sure you are using an updated or recent version of [Open Ps2 Loader 1.2](https://github.com/ps2homebrew/Open-PS2-Loader/releases/tag/latest)
- Download the assets for the `ART` folder (Background Image, Cover, Screenshots, etc.) using the latest version of [OPL Manager](https://oplmanager.com/site/)
- Use **OPL Manager** to edit the `CFG` files for each game, to correctly display the game information.
