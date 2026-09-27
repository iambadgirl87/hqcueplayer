# HQ CuePlayer

**让 HQPlayer Embedded 直接播放 CUE 整轨 / CD·SACD 镜像的专用控制台**
Seamless CUE & disc-image playback console for HQPlayer Embedded.

---

## 这是什么

HQPlayer 声音顶尖，但官方不支持 CUE 整轨和光盘镜像。HQ CuePlayer 是架在 HQPlayer Embedded 前面的专用前端：

- **拖入即播**：把 `.cue`（连同整轨 WAV/FLAC/APE/WV）或 CD / SACD 镜像（`.iso .nrg .bin .ccd .img`）拖进窗口，自动解析、无损切片、秒开播放
- **Bit-Perfect 直通**：内存切片、零重采样、零 DSP、零音量处理，数据原封不动交给 HQPlayer 引擎
- **NAS 零上传**：拖入的文件命中路径映射时，Linux 播放机直接读 NAS，秒开不拷贝
- **全格式升频控制**：码率 / 滤波器 / 调制器 / DSP 场景预设，界面一键切换
- **手机遥控**：局域网内手机浏览器直接控制播放
- **播放列表 / 收藏 / 历史 / 歌词 / 封面刮削**：官方客户端没有的一并补齐

## 系统要求

- 一台运行 **HQPlayer Embedded 5.x** 的 Linux 播放机（或 NAA 网桥环境）
- 一台 Windows 电脑运行本客户端（绿色软件，解压即用）
- 音乐库可放在 NAS（SMB 共享）或播放机本地

## 下载与安装

1. 在右侧 [Releases](../../releases) 下载最新 `hqcueplayer-x.x.x-windows.zip`
2. 解压到任意目录，运行 `hqcueplayer.exe`
3. 首次启动输入播放机 IP，点「扫描 / 连接」——Linux 端播放服务（hqpd）会**自动部署**，无需手动装任何东西
4. 详细图文教程见随包《使用说明书》（PDF）

## 授权

- **免费版**：每张专辑限播前 5 首 + 基础 DSP 切换，不限天数、不加噪音
- **正式版**：解锁 DSP 场景预设 / 码率直选 / 镜像分轨 / 跨专辑续播 / 播放列表 / 手机遥控
- 激活方式：软件内输入激活码在线激活，或导入授权文件（离线可用）
- 换机 / 重装系统后机器码会变，请联系卖家重新激活

## English

HQ CuePlayer is a dedicated front-end for HQPlayer Embedded: drop in CUE sheets or CD/SACD disc images and play them instantly — losslessly sliced in memory, bit-perfect to the HQPlayer engine. Features NAS zero-copy playback, one-click filter/modulator/rate control, playlist & mobile remote. Free tier plays the first 5 tracks of each album; a license key unlocks everything. Download the latest zip from [Releases](../../releases), unpack and run — the Linux daemon deploys itself.

## 免责声明

HQ CuePlayer 是独立第三方控制前端，与 Signalyst / HQPlayer 官方无任何关联。
HQ CuePlayer is an independent third-party front-end, not affiliated with Signalyst or HQPlayer.
