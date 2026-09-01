<p align="left"><img alt="OSPTEK" src="./images/logo.png" width="200" /></p>

<h1 align="center">OSPTEK 3.5″ TFT 320×480（AXS15231E · MIPI）</h1>

<p align="center"><b>TFT In-Cell 模组 · MIPI · AXS15231E</b></p>

<p align="center"><a href="./README_EN.md">English</a> | 简体中文 · <a href="../../README.md">规格族索引</a></p>

<p align="center">
  <img alt="Size: 3.5 inch" src="https://img.shields.io/badge/Size-3.5%22-3498DB?style=flat-square" />
  <img alt="Resolution: 320x480" src="https://img.shields.io/badge/Resolution-320%C3%97480-8E44AD?style=flat-square" />
  <img alt="Interface: MIPI" src="https://img.shields.io/badge/Interface-MIPI-27AE60?style=flat-square" />
  <img alt="Driver: AXS15231E" src="https://img.shields.io/badge/Driver-AXS15231E-E7352C?style=flat-square" />
</p>

## 目录

- [产品简介](#产品简介)
- [规格参数](#规格参数)
- [示例工程](#示例工程)
- [仓库结构](#仓库结构)
- [相关资料](#相关资料)
- [购买链接](#购买链接)
- [技术支持](#技术支持)

---

## 产品简介

OSPTEK **3.5 寸 320×480 TFT** 是一款 **MIPI** 接口彩色显示模组，驱动为 **AXS15231E**。In-Cell 电容触摸经 I2C。适合手持终端、工控 HMI 与小型交互面板等场景。

规格标识（仓库名）：`3.5-tft-320x480-mipi-axs15231`

当前模组版本：**YDP350TE011-V1**。电气与外形细节以 [`docs/YDP350TE011-V1.pdf`](./docs/YDP350TE011-V1.pdf) 为准。

## 规格参数

| 项目 | 规格 |
| ---- | ---- |
| 尺寸 | 3.5 英寸 |
| 类型 | TFT / IPS（In-Cell 彩色） |
| 分辨率 | 320×480 |
| 接口 | MIPI（1-lane DSI） |
| 驱动 IC | AXS15231E |
| 触摸驱动 | In-Cell（电容；I2C；规格书未标明具体 IC） |

> 完整外形尺寸、FPC 定义、供电与时序以产品规格书 / 驱动手册为准。

## 示例工程

| 说明 | 路径 |
| ---- | ---- |
| ESP32-P4 · AXS15231E MIPI + LVGL9 | [`examples/esp32p4-idf5_axs15231e-mipi_esp-lvgl-port_lvgl9/`](./examples/esp32p4-idf5_axs15231e-mipi_esp-lvgl-port_lvgl9/) |
| Raspberry Pi 5 · AXS15231E 320×480 面板驱动 / DT overlay（仅显示） | [`examples/rpi5-panel-axs15231e-320x480/`](./examples/rpi5-panel-axs15231e-320x480/) |
| Raspberry Pi 5 · AXS15231E 320×480 面板驱动 + 触摸 / DT overlay | [`examples/rpi5-panel-axs15231e-touch-320x480/`](./examples/rpi5-panel-axs15231e-touch-320x480/) |
| Raspberry Pi 5 · AXS15231E 320×480 LVGL 演示 | [`examples/rpi5-lvgl-axs15231e-320x480/`](./examples/rpi5-lvgl-axs15231e-320x480/) |

## 仓库结构

```text
3.5-tft-320x480-mipi-axs15231/                                # 仓库根（导航见 ../../README.md）
└── versions/
    └── YDP350TE011-V1/                                # 本料号完整资料
        ├── README.md
        ├── README_EN.md
        ├── images/
        ├── docs/
        └── examples/
```

## 相关资料

### 本产品资料

| 资料 | 链接 |
| ---- | ---- |
| 产品规格书（YDP350TE011-V1） | [`docs/YDP350TE011-V1.pdf`](./docs/YDP350TE011-V1.pdf) |
| 驱动 IC 数据手册（AXS15231E） | [`docs/AXS15231E_Datasheet_V0.3.pdf`](./docs/AXS15231E_Datasheet_V0.3.pdf) |
| 初始化序列（文本） | [`docs/TM3.5_OSC48MHZ-mipi-888-Video-60HZ.txt`](./docs/TM3.5_OSC48MHZ-mipi-888-Video-60HZ.txt) |
| RGB 时序参考图 | [`docs/rgb-timing-320x480.png`](./docs/rgb-timing-320x480.png) |

### 示例工程

- [ESP32-P4 AXS15231E MIPI + LVGL9](./examples/esp32p4-idf5_axs15231e-mipi_esp-lvgl-port_lvgl9/)
- [Raspberry Pi 5 面板驱动（仅显示）](./examples/rpi5-panel-axs15231e-320x480/)
- [Raspberry Pi 5 面板驱动 + 触摸](./examples/rpi5-panel-axs15231e-touch-320x480/)
- [Raspberry Pi 5 LVGL 演示](./examples/rpi5-lvgl-axs15231e-320x480/)

## 购买链接

<p align="center">
  <a href="https://shop110742373.taobao.com/"><img alt="淘宝官方店铺" src="https://img.shields.io/badge/淘宝-官方店铺-FF6A00?style=for-the-badge" /></a>
  &nbsp;&nbsp;
  <a href="https://www.aliexpress.com/store/1105701619"><img alt="速卖通官方店铺" src="https://img.shields.io/badge/速卖通-官方店铺-E62E04?style=for-the-badge&logo=aliexpress&logoColor=white" /></a>
</p>

**国内（淘宝）**

- 店铺：[鱼鹰光电工厂店](https://shop110742373.taobao.com/)

**海外（AliExpress）**

- 店铺：[OSPTEK Official Store](https://www.aliexpress.com/store/1105701619)

## 技术支持

- 技术支持 / 产品咨询：<luyu@osptek.com>
- QQ 技术交流群：**985881096**
- 公司官网：<https://osptek.com/>
- 有任何问题，都可以在本仓库 Issues 中提问

---

<p align="center"><sub>© 2026 OSPTEK 鱼鹰光电 · 本仓库资料采用 CC BY 4.0 许可</sub></p>
