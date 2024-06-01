# K30 Spatial Audio Module

[Download](https://github.com/Flyfish233/k30-spatial-audio-magisk/releases) | [中文](#k30-空间音效模块)

Magisk module to enable spatial audio on Redmi K30 (picasso). Spatial audio allows you to get a more immersive audio
experience while wearing headphones.

## How to use

1. Check if your system supports spatial audio.
    - Only support AOSP-based custom ROMs - MIUI/HyperOS is not supported. Tested on CherishOS 5.3.
    - Make sure your system is Android 13 or above. Spatial audio was added in Android 13.

- Download the module.
    - Download from [Releases](https://github.com/Flyfish233/k30-spatial-audio-magisk/releases).
    - Install this module on any Root manager that supports Magisk modules.
    - Ensure you know how to recover if module causes a bootloop.
    - Reboot your phone.
- Enable spatial audio.
    - Go to "Sounds & vibration" in Settings.
    - Find "Spatial Audio", enable 'em all. In most cases, it is automatically enabled after flashing the module.
    - If you are using any earbuds, connect and enable spatial audio in the earbuds' Bluetooth settings.
    - Enjoy the immersive audio experience.

  Spatial audio is designed to convert multi-channel audio to stereo audio. It will not convert stereo audio to
  multi-channel audio. Therefore, if you are not listening to multi-channel audio while listening to music, spatial
  audio will not work.

## Troubleshooting

If Spatial Audio is not visible in the Settings after reboot, try rebooting again. This may be due to permission
issues. If spatial audio still doesn't work, consider submitting an Issue with:

- Full logcat from boot.
- Full DMESG log.
- Full Magisk/Ksu log.
- Run `adb shell dumpsys audio` and paste the full output in the Issue.

## License

DOLBY ATMOS is a registered trademark of Dolby Laboratories. This module is not affiliated with Dolby Laboratories.

# K30 空间音效模块

此模块用于在红米 K30 (picasso) 上启用空间音频 (Spatial Audio)。空间音频可以让您在佩戴耳机的情况下获得更加立体的音频体验。

## 如何使用

1. 检查您的系统是否支持空间音频。
    - 确认系统是原生。基于 MIUI/HyperOS 的系统，即使能正常运行，也只能用于小米某真无线耳机。在部分移植的 Origin OS
      上可能可用，不打包票。模块在 CherishOS 5.3 上测试。
    - 确认系统版本为 Android 13 或更新版本。空间音频在 Android 13 才被添加。
    - 确认手机基于 MIUI 最新底包。它使用最新底包来启用空间音频。
2. 下载模块。
    - 从 [Releases](https://github.com/Flyfish233/k30-spatial-audio-magisk/releases) 页面下载最新版本。
    - 在适配 Magisk 模块的任何 Root 管理器上安装模块。
    - 安装后备措施以确保在模块导致卡第二屏时，您知道如何恢复它。
    - 重启手机。
3. 启用空间音频。
    - 在设置中找到“提示音和振动”。
    - 找到“空间音频”。启用它。在大部分情况下，刷入了模块以后是自动打开的。
    - 如果您使用蓝牙耳机，连接到蓝牙耳机，在耳机对应设置里启用空间音频。
4. 享受立体音频体验。

   空间音频旨在将多声道音频转换为立体声音频。它不会将立体声音频转换为多声道音频。因此，如果您在听音乐时没有多声道音频，空间音频就不会生效。
   尝试在 QQ 音乐或网易云音乐等应用中播放“沉浸音”，这些音频通常是立体声音频。

## 遇到问题

如果手机在重启以后没看到设置里面有空间音频，尝试重启一次。这可能是因为权限原因造成的。如果空间音频还是无效，请考虑提交
Issue。

### 注意

**由于本人罹患智力发育障碍 (DiD)，对于您的问题可能难以解答。**

本人在*上海市徐汇区宛平南路 600 号*确诊**智力障碍**。
医嘱表示，只有采取下列行动，我才能够正常交流相关内容，否则将会忽视此 Issue，很抱歉：

1. 您拥有自手机开机后的、完整的 Logcat 日志。AudioManager 通常在开机动画前就已经初始化了。
2. 您拥有有完整的 DMESG 日志。
3. 您拥有完整的 Magisk/Ksu 日志。
4. 运行 `adb shell dumpsys audio` 并将完整输出粘贴到 Issue 中。

## License

DOLBY ATMOS is a registered trademark of Dolby Laboratories. This module is not affiliated with Dolby Laboratories.

