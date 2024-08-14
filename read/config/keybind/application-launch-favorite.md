---
title: 開啟應用程式 (常用的)
nav_order: 5013
has_children: false
parent: 按鍵綁定
grand_parent: 設定
---


# 開啟應用程式 (常用的)

* [常用的應用程式](#常用的應用程式)
* [常用的應用程式 (預設)](#常用的應用程式-預設)




## 常用的應用程式

| 按鍵組合          | 功能           | 執行指令                        |
| ----------------- | -------------- | ------------------------------- |
| `Alt + Shift + f` | 開啟檔案管理器 | `thunar`                        |
| `Alt + Shift + g` | 開啟檔案管理器 | `pcmanfm-qt`                    |
| `Alt + Shift + e` | 開啟文字編輯器 | `mousepad`                      |
| `Alt + Shift + b` | 開啟網頁瀏覽器 | `firefox --new-tab about:blank` |
| `Alt + Shift + s` | 開啟系統設定   | `cosmic-settings`               |




* 設定片段：[~/.config/cosmic/com.system76.CosmicSettings.Shortcuts/v1/custom](https://github.com/samwhelp/popos-cosmic-adjustment/blob/main/prototype/main/cosmic-config/Main/asset/overlay/etc/skel/.config/cosmic/com.system76.CosmicSettings.Shortcuts/v1/custom#L153-L192)

```
    (
        modifiers: [
            Alt,
            Shift,
        ],
        key: "f",
        description: Some("File_Manager_1"),
    ): Spawn("thunar"),
    (
        modifiers: [
            Alt,
            Shift,
        ],
        key: "g",
        description: Some("File_Manager_2"),
    ): Spawn("pcmanfm-qt"),
    (
        modifiers: [
            Alt,
            Shift,
        ],
        key: "e",
        description: Some("Text_Editor_1"),
    ): Spawn("mousepad"),
    (
        modifiers: [
            Alt,
            Shift,
        ],
        key: "b",
        description: Some("Web_Browser_1"),
    ): Spawn("firefox --new-tab about:blank"),
    (
        modifiers: [
            Alt,
            Shift,
        ],
        key: "s",
        description: Some("System_Settings_1"),
    ): Spawn("cosmic-settings"),
```




## 常用的應用程式 (預設)

| 按鍵組合          | 功能           | 執行指令                        |
| ----------------- | -------------- | ------------------------------- |
| `Super + f` | 開啟檔案管理器 | `xdg-open ~`                        |
| `Super + b` | 開啟網頁瀏覽器 | `xdg-open http://` |


* 設定片段：[/usr/share/cosmic/com.system76.CosmicSettings.Shortcuts/v1/system_actions](https://github.com/samwhelp/popos-cosmic-adjustment/blob/main/sample/default-schema/Main/asset/overlay/usr/share/cosmic/com.system76.CosmicSettings.Shortcuts/v1/system_actions#L9)

```
    HomeFolder: "xdg-open ~",
```




* 設定片段：[/usr/share/cosmic/com.system76.CosmicSettings.Shortcuts/v1/system_actions](https://github.com/samwhelp/popos-cosmic-adjustment/blob/main/sample/default-schema/Main/asset/overlay/usr/share/cosmic/com.system76.CosmicSettings.Shortcuts/v1/system_actions#L37)

```
    WebBrowser: "xdg-open http://",
```




* 設定片段：[/usr/share/cosmic/com.system76.CosmicSettings.Shortcuts/v1/defaults](https://github.com/samwhelp/popos-cosmic-adjustment/blob/main/sample/default-schema/Main/asset/overlay/usr/share/cosmic/com.system76.CosmicSettings.Shortcuts/v1/defaults#L72-L73)

```
    (modifiers: [Super], key: "b"): System(WebBrowser),
    (modifiers: [Super], key: "f"): System(HomeFolder),
```
