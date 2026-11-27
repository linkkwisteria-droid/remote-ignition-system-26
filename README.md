# remote-ignition-system-26

> ### Info  
> - Author: 國立成功大學太空推進研究社（Institue of Space Propulsion, NCKKU, Taiwan）
> - Built Date: *2026-10-27*
> - Summary: 2026年底的點火器

### 1. Summary
這個專案是點火器。這裡有電路原理圖和韌體。


### 2. Links
- [Google Drive](https://drive.google.com/drive/folders/1G8a108MtAovM8rBFZNGf4ynVhSYMgkvS?usp=sharing)

### 3. Contents
1. File Structure
2. System Overview
3. Contributers


## 1. File Structure  
```text=
avionics-small-1151            
└─hardware             # 原理圖
```

## 2. System Overview

點火器用於地面推力測試、火箭發射等點火場景，此裝置有四種模式，點火、遙控、點火+遙控和wifi。其中點火和遙控兩種需要兩個裝置共同配合。

![image](./doc/image/RIS26%20Chart.drawio.svg)
圖2-1. 系統架構方塊圖（非最終版）

目前系統架構如上圖，部分控制元件還會再更改，尚未定案。（2026-11-27）


## 3. Contributers

|Name|Responsibility|Email|
|:-|:-|:-|
|林冠宏|Design, System|[linkk.wisteria@gmail.com](linkk.wisteria@gmail.com)|
|龍昊|Design||
|蘇立原|Firmware||
|夏良樂|Power CCT, Ignition CCT, and Firmware||
|許菀琍|Ignition CCT, Soldering||
|劉緯珊|Panel Design||