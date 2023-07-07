# Game Boy Mini Camera
The Game Boy Mini Camera is a Game Boy Camera cart redesigned into the size of a typical Game Boy Cart.

<img src="/assets/IMG_7210.png" width=30%> <img src="/assets/IMG_7218.png" width=40%>

## Features
* Based on [HDR's Game Boy Camera flash cart](https://github.com/HDR/Gameboy-Camera-Flashcart) schematic
  * Flashable with stock or custom ROMs
  * 2MB flash & integrated switch allows for saving 2 different ROMs (photos shared between ROMs)
  * FRAM eliminates use of battery for saved data
* Eliminates the sensor board & combines the components into a single PCB
* Replaces original lens with an iPhone XR lens array for thinner profile
* Glass lens cover to keep dust & debris from damaging the lens
* All new redesigned cartridge shell based to a standard Game Boy cart
* Custom designed label sticker

## Disclaimer
**WARNING: This is a difficult mod and requires advanced soldering skills & tools** due to the fine pitch of donor components and easily damagable resin sensor. I am not responsible for any harm done to you, your property, or family. Because of the complication required for this mod, personal support will be limited. Order any parts at your own risk! Please review the license before attempting.

## Materials
| Item | Link |
| - | - |
| Game Boy Camera (any version | ??? |
| Mini Camera PCB | PCBWay (soon) |
| build components | [list](https://github.com/gameboycamera/game-boy-mini-camera/tree/main#components) |
| shell (5 parts) | Shapeways / download (soon) | 
| iPhone XR/XS X1 lens array | [Aliexpress](https://www.aliexpress.com/item/3256803144047672.html) |
| iPhone XR lens cover | [Aliexpress](https://www.aliexpress.com/item/2251832829209044.html) |
| x2 M1x5mm screws | [Aliexpress](https://www.aliexpress.com/item/3256803019262480.html) |
| x4 M1x3mm screws | [Aliexpress](https://www.aliexpress.com/item/3256803019262480.html) |
| x6 M1.0x2x2 brass inserts | [Aliexpress](https://www.aliexpress.com/item/3256804533755184.html) |
| label sticker (optional) | Ally Thunderhill / included in shell download (soon) |

## Components
| Reference | Part | Description |
|-|-|-|
| C1 | [TAJA226K010RNJ](https://www.lcsc.com/product-detail/_Kyocera-AVX-_C11366.html) | 22uF tantalum capacitor |
| C2, C3, C4, C12, C13 | [TCC0603X7R104J500CT](https://www.lcsc.com/product-detail/Multilayer-Ceramic-Capacitors-MLCC-SMD-SMT_CCTC-TCC0603X7R104J500CT_C282518.html) | 100nF 0603 capacitor |
| C5, C6, C7, C8, C9, C10, C11 | [CC0402KRX7R7BB104](https://lcsc.com/product-detail/Multilayer-Ceramic-Capacitors-MLCC-SMD-SMT_YAGEO-CC0402KRX7R7BB104_C60474.html) | 100nF 0402 capacitor |
| C14, C15 | [CC0603JRNPO9BN220](https://www.lcsc.com/product-detail/Multilayer-Ceramic-Capacitors-MLCC-SMD-SMT_YAGEO-CC0603JRNPO9BN220_C105620.html) | 22pF 0603 capacitor |
| C16, C17 | Harvest C1 & C2 from original sensor board | 0603 capacitor |
| D1 | Harvest D2 from original cartridge | diode |
| L1 | Harvest L1 from original sensor board | 1210 inductor |
| R1 | [RC0603JR-071KL](https://www.lcsc.com/product-detail/Chip-Resistor-Surface-Mount_YAGEO-RC0603JR-071KL_C14676.html) | 1K Ω 0603 Resistor |
| SW1 | [K3-1296S-E1](https://www.lcsc.com/product-detail/Slide-Switches_Korean-Hroparts-Elec-K3-1296S-E1_C128955.html)| SPDT Switch (For 2x1MB Rom Switching) |
| U1 | MAC-GBD | Harvest U1 from original cartridge |
| U2 | [AM29F016](https://www.aliexpress.com/item/33043533022.html) | 2MB Flash |
| U3 | [FM28V100](https://www.aliexpress.com/item/4001322883101.html) | 1MB FRAM |
| U4 | [TPRT9013-33G](https://www.lcsc.com/product-detail/Linear-Voltage-Regulators-LDO_TECH-PUBLIC-TPRT9013-33GB_C587158.html) | 3.3V Voltage Regulator |
| U5 | Harvest U1 from original sensor board | sensor |

## Instructions
Coming soon

## Contributions
* **HDR** - original Game Boy Camera flash cart creator - This project has been uploaded with his permission
* **Ally Thunderhill** - assist with testing & printing labels, hosting labels in shop
* **Toxa** - the Photo! ROM creator
* **Game Boy Camera Club & Game Boy modding community** - for support & inspiration

## Featured in
* **The Verge** - [This beautiful modified Game Boy Camera fits entirely inside a cartridge](https://www.theverge.com/23780036/game-boy-camera-mini-mod-christopher-graves)
* **Gizmodo** - [Brilliantly Modded Game Boy Camera Is No Bigger Than a Cartridge](https://gizmodo.com/brilliantly-modded-game-boy-camera-is-no-bigger-than-a-1850595045)
* **PetaPixel** - [Custom Game Boy Mini Camera is the Same Size as a Game Boy Cartridge](https://petapixel.com/2023/06/30/custom-game-boy-mini-camera-is-the-same-size-as-a-game-boy-cartridge/)
* **Engadget** - [This nifty fan-made Game Boy camera is the size of a cartridge](https://www.engadget.com/this-nifty-fan-made-game-boy-camera-is-the-size-of-a-cartridge-185209536.html)
* **Time Extension** - [Camera Modder Unveils Brilliant, Miniaturized Version Of The Game Boy Camera](https://www.timeextension.com/news/2023/06/camera-modder-unveils-brilliant-miniaturized-version-of-the-game-boy-camera)
* **Retrododo** - [Game Boy Camera 2.0 Is Here Thanks To A Talented Modder](https://retrododo.com/game-boy-mini-camera/)
  
