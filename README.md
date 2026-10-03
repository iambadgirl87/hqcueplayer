# HQ CuePlayer

**HQPlayer Embedded 的无缝 CUE 与光盘镜像播放控制台**
直接插入 CUE 表或 CD/SACD 镜像——即时播放，比特完美，无需提取。

---

## 这是什么

HQPlayer 的音质堪称世界级，但它官方不支持 CUE 列表或光盘镜像。HQ CuePlayer 是一款专用的前端程序，它位于 HQPlayer Embedded 前端，彻底解决了这一痛点：

- **拖放**：拖放一个`.cue`（及其WAV/FLAC/APE/WV镜像）或CD/SACD镜像（`.iso .nrg .bin .ccd .img`）到窗口中——自动解析，在内存中无损切片，数秒内即可播放
- **位完美流水线**：内存切片、零重采样、零DSP、零音量处理——您的数据在未被触碰的情况下直接到达HQPlayer引擎
- **NAS零拷贝**：当丢弃的文件匹配路径映射时，Linux播放器直接读取NAS——即时启动，无需上传
- **完整引擎控制**：输出速率、滤波器、调制器和 DSP 场景预设，一键即可
- **移动远程**: 从局域网内的任何手机浏览器控制播放
- **播放列表 / 收藏 / 历史 / 歌词 / 封面**: 官方客户端从未给你的所有内容

## 要求

- 运行的 Linux 系统**HQPlayer Embedded 5.x** (或 NAA 桥接设置)
- 客户端的 Windows PC（便携版——解压后运行）
- 存储在 NAS（SMB 共享）或本地播放器上的音乐库

## 下载与安装

1. 获取最新 `hqcueplayer-x.x.x-windows.zip` 来自 [发布](../../releases)
2. 随处解压，运行 `hqcueplayer.exe`
3. 输入您的玩家IP，按下 **扫描 / 连接** — Linux守护进程（hqpd） **会自动部署**，无需手动安装
4. 完整图文指南：请参阅随附的 *用户手册* (PDF)

## 许可证

- **Public beta**: all Pro features unlocked for testers — free test keys, just ask in the forum thread. Bug reports welcome!
- **Free tier**: first 5 tracks of each album + basic DSP switching — no time limit, no noise, no watermark
- **Pro**: DSP scene presets, direct rate selection, image track-splitting, cross-album gapless, playlists, mobile remote

**Instant activation** — paste your key (`HQCP-XXXX-XXXX`), hit **Activate**. Done in seconds: the software binds the key to your player hardware **automatically** — no machine IDs to copy, no email round-trips, no waiting.

- Once activated it runs **100% offline forever** — no phone-home, no telemetry
- Air-gapped player? Offline license-file import is available as a fallback
- One key = one player. OS reinstall or hardware change alters the machine ID — just contact the author for a transfer

## Disclaimer

HQ CuePlayer is an independent third-party front-end, not affiliated with Signalyst or HQPlayer.
