---
title: 開啟應用程式 (Terminal)
nav_order: 5010
has_children: false
parent: 按鍵綁定
grand_parent: 設定
---


# 開啟應用程式 (Terminal)

* [開啟 Terminal](#開啟-terminal)
* [開啟 Terminal (預設)](#開啟-terminal-預設)




## 開啟 Terminal


| 按鍵組合          | 功能         | 執行指令                     |
| ----------------- | ------------- | --------------------------- |
| `Alt + Enter`     | 開啟 Terminal | `cosmic-term`                 |
| `Alt + Shift + a` | 開啟 Terminal | `sakura`                 |
| `Alt + Ctrl + a`  | 開啟 Terminal | `xfce4-terminal` |
| `Alt + Shift + t` | 開啟 Terminal | `qterminal`                     |
| `Alt + Ctrl + t`  | 開啟 Terminal | `lxterminal`                     |




* 設定片段：[/usr/share/cosmic/com.system76.CosmicSettings.Shortcuts/v1/system_actions](https://github.com/samwhelp/popos-cosmic-adjustment/blob/main/sample/default-schema/Main/asset/overlay/usr/share/cosmic/com.system76.CosmicSettings.Shortcuts/v1/system_actions#L31)

```
    Terminal: "cosmic-term",
```




* 設定片段：[~/.config/cosmic/com.system76.CosmicSettings.Shortcuts/v1/custom](https://github.com/samwhelp/popos-cosmic-adjustment/blob/main/prototype/main/cosmic-config/Main/asset/overlay/etc/skel/.config/cosmic/com.system76.CosmicSettings.Shortcuts/v1/custom#L115-L152)

```
    (
        modifiers: [
            Alt,
        ],
        key: "Return",
    ): System(Terminal),
    (
        modifiers: [
            Alt,
            Shift,
        ],
        key: "a",
        description: Some("Terminal_1"),
    ): Spawn("sakura"),
    (
        modifiers: [
            Alt,
            Ctrl,
        ],
        key: "a",
        description: Some("Terminal_2"),
    ): Spawn("xfce4-termianl"),
    (
        modifiers: [
            Alt,
            Shift,
        ],
        key: "t",
        description: Some("Terminal_3"),
    ): Spawn("qterminal"),
    (
        modifiers: [
            Alt,
            Ctrl,
        ],
        key: "t",
        description: Some("Terminal_4"),
    ): Spawn("lxterminal"),
```




## 開啟 Terminal (預設)

| 按鍵組合          | 功能         | 執行指令                     |
| ----------------- | ------------- | --------------------------- |
| `Super + t`     | 開啟 Terminal | `cosmic-term`                 |




* 設定片段：[/usr/share/cosmic/com.system76.CosmicSettings.Shortcuts/v1/defaults](https://github.com/samwhelp/popos-cosmic-adjustment/blob/main/sample/default-schema/Main/asset/overlay/usr/share/cosmic/com.system76.CosmicSettings.Shortcuts/v1/defaults#L74)

```
    (modifiers: [Super], key: "t"): System(Terminal),
```
