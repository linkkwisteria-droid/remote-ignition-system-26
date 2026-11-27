# remote-ignition-system-26/hardware

### 1. Summary
hardware存放硬體相關檔案，目前只有電路原理圖，使用Kicad10.0。

### 2. Contents
1. File Structure
2. Hardware Overview
3. Edit History


## 1. File Structure  
```text=
avionics-small-1151            
├─hardware
│  ├─libraries              # 符號庫
│  └─ris26
│     ├─ris26.kicad_pro     # 從此檔案開啟電路原理圖
│     └─ris26.pdf           # 電路原理圖PDF檔案
└─...
```

## 2. Hardware Overview

- 使用Kicad 10.0。
- 符號庫都統一存放在一個庫，放在./libraries中。
- 只有一個Kicad專案，叫做ris26，編輯時只要開啟./ris26/ris26.kicad_pro這個工程檔案。
- 繪製原理圖到PDF檔案，存放在./ris26/ris26.pdf。
- 此Kicad專案不需要考慮PCB和Footprint，純粹只用原理圖。
- 採用模組化概念。

## 3. Edit History

2026-11-18 07:46 林冠宏的設計部分80%完成，等待ignition和power後整合，以及電路板設計。
2026-11-27 12:13 將電池電壓從7.5v改成3.4v，標籤從+7.5V改成+BATT。
