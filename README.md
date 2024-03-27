# 铭瑄电竞之心 Z690ITX Hickintosh

## 配置详情

**主板**：MS-iCraft Z690ITX WIFI  
**CPU**：英特尔 ® 酷睿 ™ i5-13600KF 处理器  
**GPU**：RX580/RX6600xt/RX6800xt(其他显卡自测)
**网卡**：AX211  
**声卡**：ALC897

## 性能

![GeekBench6-CPU](SceenShot/GeekBench6-CPU.png "I5 13600KF")
![GeekBench6-GPU](SceenShot/GeekBench6-RX6600xt.png "RX6600xt")

## 细节

**OpenCore**：0.99

## 问题

- 开机音频问题
- 隔空投送无法找到设备

## 提示

- 此 EFI 适用于`ventura`，`monterey`, `sonoma`，不同系统需不同 `wifi` 驱动（AirportItlwm - intel）。
- Sonoma 14 与 Sonoma 14.4 `wifi` 驱动也不相同。
- 更新 14.4 之前，建议更新 OpenCore 和主要 Kext 到最新版本，且强烈建议关闭 SecureBootModel，否则可能更新失败，该选项位于 config.plist → Misc → Security，更新完成后可再次开启。

## 相关文档

- [OpenCore](https://dortania.github.io/OpenCore-Install-Guide/)官方
- [Opencore](https://oc.skk.moe/)参考手册
- [国光黑苹果](https://apple.sqlsec.com/)
- [itlwm](https://github.com/OpenIntelWireless/itlwm) - intel 网卡驱动

## 最后

**觉得有用的点个star吧**
