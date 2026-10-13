# 边播边译 Navo Player

**任何视频，边播边出母语字幕。** 本机 AI 一边识别台词、一边翻译，提前缓冲约 3 分钟，不上传、不订阅、断网可用。

**Navo Player — the player that generates subtitles in real time.** On-device speech recognition and translation while the video plays — no uploads, no subscription, works offline.

🌐 **官网 / Website:** https://thundom.github.io/subtitle-studio/
⬇️ **下载 / Download:** [Releases](../../releases/latest)

| | |
|---|---|
| 🪟 Windows 桌面版 / desktop app | `SubtitleStudio-Setup.exe` |
| 📺 Emby 插件 / plugin | `Emby.AISubtitles.zip` |

## 主要功能 / Highlights

- 边播边译：进度条显示已识别 / 已翻译的区段 · Translate while playing, with recognized/translated ranges on the progress bar
- 本机运行：whisper.cpp 语音识别（显卡 Vulkan 或 CPU）+ 腾讯混元 Hy-MT2 离线翻译，也支持 DeepSeek · Runs locally: whisper.cpp + offline Hunyuan Hy-MT2, DeepSeek optional
- 双语 / 译文 / 原文切换，字幕可复用（.srt）· Dual / translated / original, reusable .srt files
- 文件夹批量生成、断点续做、资源管理器右键菜单 · Folder batch with resume, Explorer context menu
- 仿 PotPlayer 的极简界面，秒播；字幕字体 / 颜色 / 位置随心调 · Clean PotPlayer-style UI with instant play; subtitle font / color / position
- 播放列表、播放历史、收藏；画质模板、智能高清、去黑边、画面比例、变速、对白增强 · Playlists, history, favorites; picture presets, Smart HD, black-bar removal, aspect ratios, speed, dialogue boost
- Emby 插件：新片入库按规则自动生成字幕 · Emby plugin: auto-subtitles new library items by rules
- 界面：简体 / 繁體 / English / 日本語 · UI in Simplified/Traditional Chinese, English, Japanese

## 系统要求 / Requirements

Windows 10 / 11 64 位 / 64-bit. 有独立显卡更快，没有也能用 · A dedicated GPU (NVIDIA / AMD / Intel) is faster but not required.

## 许可 / License

**个人免费使用，禁止商业用途。** 详见 [LICENSE.md](LICENSE.md)。
**Free for personal use; commercial use is prohibited.** See [LICENSE.md](LICENSE.md).

随附的开源组件遵循各自的许可证 · Bundled open-source components remain under their own licenses.
