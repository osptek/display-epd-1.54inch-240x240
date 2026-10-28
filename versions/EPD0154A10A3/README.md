<p align="left"><img alt="OSPTEK" src="../../images/logo.png" width="200" /></p>

<h1 align="center">OSPTEK 1.54″ EPD 显示屏 240×240（EPD0154A10A3）</h1>

<p align="center"><b>EPD 模组 · SPI · IST7513</b></p>

<p align="center"><a href="./README_EN.md">English</a> | 简体中文 · <a href="../../README.md">规格族索引</a></p>

<p align="center">
  <img alt="Interface: SPI" src="https://img.shields.io/badge/Interface-SPI-27AE60?style=flat-square" />
  <img alt="Driver: IST7513" src="https://img.shields.io/badge/Driver-IST7513-E7352C?style=flat-square" />
</p>

<p align="center"><img alt="OSPTEK 1.54 寸 240×240 EPD 模组宣传图" src="./images/PNG-1.png" width="640" /></p>

## 目录

- [规格参数](#规格参数)
- [相关资料](#相关资料)
- [仓库结构](#仓库结构)
- [购买链接](#购买链接)
- [技术支持](#技术支持)

---

## 规格参数

| 项目 | 规格 |
| ---- | ---- |
| 尺寸 | 1.54 英寸 |
| 类型 | EPD |
| 分辨率 | 240×240 |
| 外形尺寸 | 31.8 x 37.32 x 0.85 mm |
| 有效显示区域 | 27 x 27 mm |
| 接口 | SPI |
| 驱动 IC | IST7513 |
| 触摸驱动 | — |

> 完整外形尺寸、FPC 定义、供电与时序以产品规格书 / 驱动手册为准。

## 相关资料

| 分类 | 文件 |
| ---- | ---- |
| 规格文档 | [`EPD0154A10A3.pdf`](./datasheets/EPD0154A10A3.pdf) |
| CAD 图纸 | [`EPD0154A10A3.dwg`](./cad/EPD0154A10A3.dwg) |
| 转接板资料 | [`PNG-1.jpg`](./adapter/PNG-1.jpg) |
| 转接板资料 | [`1.54寸6色墨水屏底板原理图V0.1.pdf`](./adapter/1.54%E5%AF%B86%E8%89%B2%E5%A2%A8%E6%B0%B4%E5%B1%8F%E5%BA%95%E6%9D%BF%E5%8E%9F%E7%90%86%E5%9B%BEV0.1.pdf) |

## 仓库结构

```text
display-epd-1.54inch-240x240/ # 仓库根（导航见 ../../README.md，示例工程见根目录 examples/）
└── versions/
    └── EPD0154A10A3/        # 本料号完整资料
        ├── README.md
        ├── README_EN.md
        ├── osptek.yml
        ├── images/
        ├── datasheets/       # 产品规格书 + 驱动/触摸 IC 数据手册
        ├── cad/              # 外形/盖板 CAD
        └── adapter/          # 转接板资料 + 转接板图片
```

## 购买链接

见[仓库首页](../../README.md#购买链接)。

## 技术支持

见[仓库首页](../../README.md#技术支持)。

---

<p align="center"><sub>© 2026 OSPTEK 鱼鹰光电 · 本仓库资料采用 CC BY 4.0 许可</sub></p>
