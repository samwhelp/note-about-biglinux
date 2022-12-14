---
title: 音量控制
nav_order: 5052
has_children: false
parent: BigLinux Adjustment
grand_parent: 設定
---


# 音量控制

## 音量控制

* [設定片段](https://github.com/samwhelp/biglinux-adjustment/blob/main/prototype/keybind/kdebiglinux/modern/kglobalshortcutsrc#L36-L43)

| 按鍵組合          | 功能             | 執行指令                                    |
| ----------------- | ---------------- | ------------------------------------------- |
| `Alt + m`         | 音量切換成靜音   | `mute=`     |
| `Alt + Shift + <` | 減小音量         | `decrease_volume=` |
| `Alt + Shift + >` | 增加音量         | `increase_volume=` |


| 按鍵組合               | 功能           | 執行指令                                    |
| ---------------------- | -------------- | ------------------------------------------- |
| `XF86AudioMute`        | 音量切換成靜音 | `mute=`     |
| `XF86AudioLowerVolume` | 減小音量       | `decrease_volume=` |
| `XF86AudioRaiseVolume` | 增加音量       | `increase_volume=` |


## 麥克風音量控制

* [設定片段](https://github.com/samwhelp/biglinux-adjustment/blob/main/prototype/keybind/kdebiglinux/modern/kglobalshortcutsrc#L36-L43)


| 按鍵組合          | 功能             | 執行指令                                    |
| ----------------- | ---------------- | ------------------------------------------- |
| `Alt + Ctrl + m`         | 麥克風音量切換成靜音   | `mic_mute`     |
| `Alt + Ctrl + <` | 麥克風減小音量         | `decrease_microphone_volume=` |
| `Alt + Ctrl + >` | 麥克風增加音量         | `increase_microphone_volume=` |
