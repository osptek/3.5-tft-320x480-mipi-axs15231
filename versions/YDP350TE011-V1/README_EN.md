<p align="left"><img alt="OSPTEK" src="./images/logo.png" width="200" /></p>

<h1 align="center">OSPTEK 3.5″ TFT 320×480 (AXS15231E · MIPI)</h1>

<p align="center"><b>TFT In-Cell module · MIPI · AXS15231E</b></p>

<p align="center"><a href="./README.md">简体中文</a> | English · <a href="../../README_EN.md">Family index</a></p>

<p align="center">
  <img alt="Size: 3.5 inch" src="https://img.shields.io/badge/Size-3.5%22-3498DB?style=flat-square" />
  <img alt="Resolution: 320x480" src="https://img.shields.io/badge/Resolution-320%C3%97480-8E44AD?style=flat-square" />
  <img alt="Interface: MIPI" src="https://img.shields.io/badge/Interface-MIPI-27AE60?style=flat-square" />
  <img alt="Driver: AXS15231E" src="https://img.shields.io/badge/Driver-AXS15231E-E7352C?style=flat-square" />
</p>

## Contents

- [Overview](#overview)
- [Specifications](#specifications)
- [Repository layout](#repository-layout)
- [Resources](#resources)
- [Buy](#buy)
- [Support](#support)

---

## Overview

OSPTEK **3.5″ 320×480 TFT** is a **MIPI** color display module driven by **AXS15231E**, with In-Cell capacitive touch over I2C. Suited to handheld terminals, industrial HMI, and compact interactive panels.

Spec ID (repository name): `3.5-tft-320x480-mipi-axs15231`

Current module version: **YDP350TE011-V1**. Electrical and mechanical details follow [`docs/YDP350TE011-V1.pdf`](./docs/YDP350TE011-V1.pdf).

## Specifications

| Item | Spec |
| ---- | ---- |
| Size | 3.5 inch |
| Type | TFT / IPS (In-Cell color) |
| Resolution | 320×480 |
| Interface | MIPI (1-lane DSI) |
| Driver IC | AXS15231E |
| Touch driver | In-Cell (capacitive; I2C; datasheet does not name the IC) |

> Full outline, FPC definition, power, and timing follow the product datasheet / driver IC datasheet.

## Repository layout

```text
3.5-tft-320x480-mipi-axs15231/                                # repo root (nav: ../../README_EN.md)
└── versions/
    └── YDP350TE011-V1/                                # full materials for this part number
        ├── README.md
        ├── README_EN.md
        ├── images/
        ├── docs/
        └── examples/
```

## Resources

### Product files

| Resource | Link |
| ---- | ---- |
| Product datasheet (YDP350TE011-V1) | [`docs/YDP350TE011-V1.pdf`](./docs/YDP350TE011-V1.pdf) |
| 3D drawing (YDP350TE011-V1) | [`docs/YDP350TE011-V1.dwg`](./docs/YDP350TE011-V1.dwg) |
| Driver IC datasheet (AXS15231E) | [`docs/AXS15231E_Datasheet_V0.3.pdf`](./docs/AXS15231E_Datasheet_V0.3.pdf) |
| Init sequence (text) | [`docs/TM3.5_OSC48MHZ-mipi-888-Video-60HZ.txt`](./docs/TM3.5_OSC48MHZ-mipi-888-Video-60HZ.txt) |
| RGB timing reference | [`docs/rgb-timing-320x480.png`](./docs/rgb-timing-320x480.png) |

## Buy

<p align="center">
  <a href="https://www.aliexpress.com/store/1105701619"><img alt="AliExpress store" src="https://img.shields.io/badge/AliExpress-Official_Store-FF6A00?style=for-the-badge" /></a>
  &nbsp;&nbsp;
  <a href="https://shop110742373.taobao.com/"><img alt="Taobao store" src="https://img.shields.io/badge/Taobao-Official_Store-FF6A00?style=for-the-badge" /></a>
</p>

**Overseas (AliExpress)**

- Store: [OSPTEK Official Store](https://www.aliexpress.com/store/1105701619)

**China (Taobao)**

- Store: [鱼鹰光电工厂店](https://shop110742373.taobao.com/)

## Support

- Technical support / product inquiry: <luyu@osptek.com>
- QQ group: **985881096**
- Website: <https://osptek.com/>
- Feel free to open an Issue in this repository with any questions

---

<p align="center"><sub>© 2026 OSPTEK · Materials in this repository are licensed under CC BY 4.0</sub></p>
