# OpenCore for intel nuc8i5ben

![nuc8i5bek-nuc8i5beh-pb-16x9.png.rendition.intel.web.1920.1080](./assets/nuc8i5bek-nuc8i5beh-pb-16x9.png.rendition.intel.web.1920.1080.webp)

## ç®ä»

å®ç¾ ðã

|       Key        |         Value          |
| :--------------: | :--------------------: |
| OpenCore version |         0.8.9          |
|  MacOS version   | Ventura 13.2.1 (22D68) |

## Bios è®¾ç½®

- Devices -> USB -> Port Device Charging Mode: off
- Devices -> USB -> USB Legacy -> Disabled
- Security -> Thunderbolt Security Level: Legacy Mode
- Power -> Wake on LAN from S4/S5: Stay Off
- Boot -> Boot Configuration -> Network Boot: Disable
- Boot -> Secure Boot -> Disable

## å®è£è¯´æ

- **æçæ¯å ç¨äºè¯»å¡å¨çç¡¬æ¹çæ¬éé¢æåéç½å¡é©±å¨ï¼å¦æä½ æ¯è±ç¹å°ç½å¡éè¦æ´æ¢ä¸ºè±ç¹å°ç½å¡é©±å¨**
- è®°å¾æ¢ä¸ç ï¼éé¢æ²¡æèªå¸¦ç
- ä¸è¦æ¢æºåï¼å¦å usb æ¥å£æ æ³ä½¿ç¨ï¼éè¦æ¿æ¢ USBPorts.kext å plist çæºåå¼ï¼ä½ ä¼åä»£ç çè¯å¾ç®åæå¼æ¹ä¸ä¸¤ä¸ªå°æ¹å°±è¡
- å·²ç»ç¨æ¥åäºå¥½å å¹´çä»£ç ï¼æ²¡å¥é®é¢ãè½å¼åï¼è¿ä¸ªé¡¹ç®ä¹æ¯å¨ mac ä¸ç³»ç»ä¸ä¼ ä¸æ¥ç
- github æææå¤ç efi æä¹ç¨è¿ï¼ç¨èµ·æ¥æ¯ç°å¨éç½®çå¡ãä¸ç¥éå¥é®é¢ï¼å¦ææç efi æé®é¢ä½ ä»¬ä¹å¯ä»¥ççï¼[https://github.com/zearp/Nucintosh](https://github.com/zearp/Nucintosh)

## ç¡¬ä»¶

|   Key    |                                     Value                                     | Other      |
| :------: | :---------------------------------------------------------------------------: | ---------- |
|   CPU    |          IntelÂ® Coreâ¢ i5-8259U Processor (6M Cache, up to 3.80 GHz)           | 4c8h       |
|   æ¾å¡   |               Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                |            |
|   åå­   |               Lexar LD4AS016G-H2666G - 16 GB (1 rank, 16 banks)               | x2 å± 32GB |
| æ çº¿ç½å¡ |          Broadcom BCM43xx 1.0 (7.77.111.1 AirPortDriverBrcmNIC-1766)          | 94360cs2   |
| æçº¿ç½å¡ |                    Intel(R) Ethernet Connection (6) I219-V                    |            |
|   å£°å¡   | Realtek ALC233 @ Intel Cannon Point-LP PCH - cAVS (Audio, Voice, Speech) [D0] |            |
|   ç¡¬ç   |                             WD Blue SN570 1TB SSD                             |            |
|   æ¥å£   |          USB-C (DP1.2) X1<br/>HDMI 2.0a X1<br/>RJ45 ç½å£ X1<br/>...           |            |

## æ­£å¸¸å·¥ä½

- CPU æ­£å¸¸ç¿é¢
- åéç½å¡ - éç©ºæé
- å£°å¡
- ç¡ç 
- æ ¸æ¾æ­£å¸¸é©±å¨ï¼æ¯æç¼©æ¾/å¤è§

## å­å¨çé®é¢

- ~~å¼æºå¶åå¡ä½ï¼ä¸ç®¡æ¯è¿å¥ win è¿æ¯ mac é½æè¿ä¸ªé®é¢ãçèµ·æ¥åä¸ªä¾ï¼ææ²¡åºç°è¿ä¸ªé®é¢çã~~

  å¨ issue ææªå¾æè§æ¯ usb ç¸å³çé®é¢ï¼æç§ä¸é¢ç bios è®¾ç½®æ²¡æåºé®é¢äºã

## é¨åç³»ç»æªå¾

<img src="./assets/iShot_2023-02-15_14.52.14.webp" style="zoom:25%;" />

ç¨åºå

<img src="./assets/iShot_2023-02-15_14.48.39.webp" style="zoom:25%;" />

| Describe | screenshot                                                               |
| -------- | ------------------------------------------------------------------------ |
| Nvme     | <img src="./assets/iShot_2023-02-15_14.55.15.webp" style="zoom: 50%;" /> |
| USB      | <img src="./assets/iShot_2023-02-15_14.55.00.webp" style="zoom:50%;" />  |
| ä»¥å¤ªç½   | <img src="./assets/iShot_2023-02-15_14.54.41.webp" style="zoom:50%;" />  |
| åå­     | <img src="./assets/iShot_2023-02-15_14.54.35.webp" style="zoom:50%;" />  |
| æ¾å¡     | <img src="./assets/iShot_2023-02-15_14.54.28.webp" style="zoom:50%;" />  |
| çµæº     | <img src="./assets/iShot_2023-02-15_14.54.14.webp" style="zoom:50%;" />  |
| èç     | <img src="./assets/iShot_2023-02-15_14.54.10.webp" style="zoom:50%;" />  |
| é³é¢     | <img src="./assets/iShot_2023-02-15_14.54.02.webp" style="zoom:50%;" />  |
| WIFI     | <img src="./assets/iShot_2023-02-15_14.53.54.webp" style="zoom:50%;" />  |

## é¨å efi æªå¾

| Describe | screenshot                                                                                              |
| :------: | ------------------------------------------------------------------------------------------------------- |
|   ACPI   | <img src="./assets/iShot_2023-02-15_14.43.29.webp" alt="iShot_2023-02-07_20.09.44" style="zoom:25%;" /> |
|    Dp    | <img src="./assets/iShot_2023-02-15_14.44.35.webp" alt="iShot_2023-02-07_20.09.53" style="zoom:25%;" /> |
|  Kernel  | <img src="./assets/iShot_2023-02-15_14.45.03.webp" alt="iShot_2023-02-07_20.09.44" style="zoom:25%;" /> |

## æ´æ°æ¥å¿

### 2023-03-10

- å°è¯ä½¿ç¨ mod çæ¬ç oc

### 2023-02-24

- å¢å äº CFGLock æ¥çå·¥å·ï¼éè¦æä½ç©ºæ ¼æ¾ç¤ºè¾å©å·¥å·
- é»è®¤éèè¾å©å·¥å·ï¼æä½ç©ºæ ¼æ¾ç¤º

## åè

- [[OpenCore] NUC8 ææ° OC EFI æç»­æ´æ°ï¼å·²æ´æ°è³ 0.8.7+13.1ï¼](https://bbs.pcbeta.com/viewthread-1935097-1-1.html) by yippeeghost
