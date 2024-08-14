---
title: 系統選單
nav_order: 5002
has_children: false
parent: 按鍵綁定
grand_parent: 設定
---


# 系統選單

* [開啟「應用程式主選單」](#開啟應用程式主選單)
* [開啟「應用程式啟動選單」](#開啟應用程式啟動選單)
* [開啟「工作空間切換選單」](#開啟工作空間切換選單)




## 開啟「應用程式主選單」

| 按鍵組合  | 功能       | 執行指令                      |
| --------- | ---------- | ----------------------------- |
| `Alt + F1` | 開啟「應用程式主選單」 | `System(AppLibrary)` (cosmic 內建) |




* 設定片段：[/usr/share/cosmic/com.system76.CosmicSettings.Shortcuts/v1/system_actions](https://github.com/samwhelp/popos-cosmic-adjustment/blob/main/sample/default-schema/Main/asset/overlay/usr/share/cosmic/com.system76.CosmicSettings.Shortcuts/v1/system_actions#L3)

```
    AppLibrary: "cosmic-app-library",
```




* 設定片段：[~/.config/cosmic/com.system76.CosmicSettings.Shortcuts/v1/custom](https://github.com/samwhelp/popos-cosmic-adjustment/blob/main/prototype/main/cosmic-config/Main/asset/overlay/etc/skel/.config/cosmic/com.system76.CosmicSettings.Shortcuts/v1/custom#L79-L84)

```
    (
        modifiers: [
            Alt,
        ],
        key: "F1",
    ): System(AppLibrary),
```




## 開啟「應用程式啟動選單」

| 按鍵組合  | 功能       | 執行指令                      |
| --------- | ---------- | ----------------------------- |
| `Alt + F2` | 開啟「應用程式啟動選單」 | `System(Launcher)` (cosmic 內建) |
| `Win + grave` | 開啟「應用程式啟動選單」 | `System(Launcher)` (cosmic 內建) |


> `grave` 指的是「`」，在「~」底下。




* 設定片段：[/usr/share/cosmic/com.system76.CosmicSettings.Shortcuts/v1/system_actions](https://github.com/samwhelp/popos-cosmic-adjustment/blob/main/sample/default-schema/Main/asset/overlay/usr/share/cosmic/com.system76.CosmicSettings.Shortcuts/v1/system_actions#L15)

```
    Launcher: "cosmic-launcher",
```




* 設定片段：[~/.config/cosmic/com.system76.CosmicSettings.Shortcuts/v1/custom](https://github.com/samwhelp/popos-cosmic-adjustment/blob/main/prototype/main/cosmic-config/Main/asset/overlay/etc/skel/.config/cosmic/com.system76.CosmicSettings.Shortcuts/v1/custom#L31-L42)

```
    (
        modifiers: [
            Alt,
        ],
        key: "F2",
    ): System(Launcher),
    (
        modifiers: [
            Super,
        ],
        key: "grave",
    ): System(Launcher),
```




## 開啟「工作空間切換選單」

| 按鍵組合  | 功能       | 執行指令                      |
| --------- | ---------- | ----------------------------- |
| `Win + Tab` | 開啟「工作空間切換選單」 | `System(WorkspaceOverview)` (cosmic 內建) |




* 設定片段：[/usr/share/cosmic/com.system76.CosmicSettings.Shortcuts/v1/system_actions](https://github.com/samwhelp/popos-cosmic-adjustment/blob/main/sample/default-schema/Main/asset/overlay/usr/share/cosmic/com.system76.CosmicSettings.Shortcuts/v1/system_actions#L41)

```
    WorkspaceOverview: "cosmic-workspaces",
```




* 設定片段：[~/.config/cosmic/com.system76.CosmicSettings.Shortcuts/v1/custom](https://github.com/samwhelp/popos-cosmic-adjustment/blob/main/prototype/main/cosmic-config/Main/asset/overlay/etc/skel/.config/cosmic/com.system76.CosmicSettings.Shortcuts/v1/custom#L43-L48)

```
    (
        modifiers: [
            Super,
        ],
        key: "Tab",
    ): System(WorkspaceOverview),
```
