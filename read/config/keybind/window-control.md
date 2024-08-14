---
title: 視窗基本操作
nav_order: 5020
has_children: false
parent: 按鍵綁定
grand_parent: 設定
---


# 視窗基本操作

* [關閉視窗](#關閉視窗)
* [最大化](#最大化)
* [最小化](#最小化)




## 關閉視窗

| 按鍵組合          | 功能     | 執行指令         |
| ----------------- | -------- | ---------------- |
| `Win + q`         | 關閉視窗 | `Close` (cosmic 內建) |


> 一般「關閉視窗」的按鍵綁定是在「`Alt + F4`」。




* 設定片段：[~/.config/cosmic/com.system76.CosmicSettings.Shortcuts/v1/custom](https://github.com/samwhelp/popos-cosmic-adjustment/blob/main/prototype/main/cosmic-config/Main/asset/overlay/etc/skel/.config/cosmic/com.system76.CosmicSettings.Shortcuts/v1/custom#L67-L78)

```
    (
        modifiers: [
            Alt,
        ],
        key: "F4",
    ): Close,
    (
        modifiers: [
            Super,
        ],
        key: "q",
    ): Close,
```




## 最大化

| 按鍵組合  | 功能       | 執行指令                      |
| --------- | ---------- | ----------------------------- |
| `Win + w` | 最大化 | `Maximize` (cosmic 內建) |


> 也可以在「視窗標題列」，使用「滑鼠左鍵」，點選兩下，切換視窗最大化。




* 設定片段：[~/.config/cosmic/com.system76.CosmicSettings.Shortcuts/v1/custom](https://github.com/samwhelp/popos-cosmic-adjustment/blob/main/prototype/main/cosmic-config/Main/asset/overlay/etc/skel/.config/cosmic/com.system76.CosmicSettings.Shortcuts/v1/custom#L79-L84)

```
    (
        modifiers: [
            Super,
        ],
        key: "w",
    ): Maximize,
```




## 最小化

| 按鍵組合  | 功能       | 執行指令                      |
| --------- | ---------- | ----------------------------- |
| `Win + x` | 最大化 | `Minimize` (cosmic 內建) |


> 也可以在「視窗標題列」，找到「最小化」按鈕。




* 設定片段：[~/.config/cosmic/com.system76.CosmicSettings.Shortcuts/v1/custom](https://github.com/samwhelp/popos-cosmic-adjustment/blob/main/prototype/main/cosmic-config/Main/asset/overlay/etc/skel/.config/cosmic/com.system76.CosmicSettings.Shortcuts/v1/custom#L85-L90)

```
    (
        modifiers: [
            Super,
        ],
        key: "x",
    ): Minimize,
```
