

![sc-desktop](https://github.com/Memoyu/msi-z490m-edge-oc-efi/blob/main/images/sc-desktop.png)

## 基本信息

OpenCore：0.7.8

MacOS：12.1 Monterey

## 配置信息

| 组件     | 型号                                                        |
| -------- | ----------------------------------------------------------- |
| **CPU**  | Intel 10代 酷睿 i7-10700K  8核16线程                        |
| **主板** | 微星(MSI)MPG Z490M GAMING EDGE WiFi刀锋板                   |
| **内存** | 美商海盗船 16GB(8G×2)套装 DDR4 3600                         |
| **显卡** | 迪兰 RX 5700 XT 8G X战神 1730-1870/14Gbps 8GB/256-bit GDDR6 |
| **硬盘** | 西部数据 1T SSD固态硬盘 M.2接口 WD_BLACK SN750 游           |
| **网卡** | Fenvi T919 BCM94360CD 2 天线版本                            |
| **电源** | 华硕（ASUS） ROG 雷鹰650W电源 电竞电源                      |
| **散热** | 九州风神 堡垒240CPU水冷散热器EX白色版                       |
| **机箱** | 恩杰 NZXT H510 白色 DIY中塔ATX机箱                          |

## BISO 设置

**仅适用于MSI Z490M EDGE**

- Above 4G memory/Crypto Currency mining：**Enabled**

  > Settings \ Advanced \ PCIe/PCI Sub-system Settings \

- Fast Boot：**Disabled**

  > Settings \ Boot \ 

- Secure Boot Mode：**Standard**

  > Settings \ Security \ Secure Boot \ 

- Wake Up Event By： **OS**

  > Settings \ Advanced \ Wake Up Event Setup \

- IGD Multi-Monitor：**Enabled**

  > Settings \ Advanced \ Integrated Graphics Configuration \

- Extreme Memory Profile(XMP)：**Enabled**

  > Overclocking \

- Intel Virtualization Tech：**Disabled**

  > Overclocking \ CPU Features \

- CFG Lock：**Disabled**

  > Overclocking \ CPU Features \



## 正常功能

- [x] 核显（如果用核显，需要自己调整DP，实际证明可正常工作）

- [x] 独显

- [x] 声卡

- [x] 有线网卡 (大佬都说需要网络设置1000m的模式，可是我的直接可以使用)

- [x] WIFI 、隔空投送(BCM94360CD 免驱，原生的没尝试，听说无解，还是免驱舒服)

- [x] 蓝牙 (BCM94360CD 免驱，原生的没尝试，听说无解，还是免驱舒服)

- [x] USB 

- [x] 睡眠唤醒 

- [x] 原生 NVRAM 



## 参考

[国光的黑苹果安装教程 (sqlsec.com)](https://apple.sqlsec.com/)

[黑果小兵hackintosh教程](https://blog.daliansky.net/macOS-Mojave-10.14.5-18F132-official-version-with-Clover-4928-original-image.html#more)
