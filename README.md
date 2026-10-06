# HQ CuePlayer

**The CUE & disc-image front-end HQPlayer Embedded never had**
Drag in cue sheets or CD images — split-track or whole-disc — and just play. Bit-perfect, in-memory, no extraction.

---

## What is this

HQPlayer sounds world-class, but it has no native CUE support and no playlist workflow to speak of. HQ CuePlayer is a dedicated front-end for HQPlayer Embedded, built by a foobar2000 native who wanted one simple thing back: drag music in, see every track, double-click to play.

- **Drag & play anything**: cue + whole-disc WAV/FLAC, cue + split-track WAV/FLAC (every track matched from the cue's FILE lines), loose track folders without a cue, and CD images (`.iso .bin .nrg .ccd .img`)
- **Bit-perfect pipeline**: lossless in-memory slicing or native whole-file passthrough — zero resampling, zero DSP, your data reaches the HQPlayer engine untouched
- **Real playlists**: multi-album queues, gapless cross-album advance, favorites, history, lyrics, cover art
- **Mobile remote**: full multi-album queue on your phone — collapsible albums, tap any track in any album to play it instantly
- **Full engine control**: output rate, filters, modulators, and one-click DSP scene presets
- **NAS zero-copy**: files on a mapped NAS path are read by the player directly — instant start, nothing uploaded

## Requirements

- A Linux box running **HQPlayer Embedded 5.x** (or an NAA bridge setup)
- A Windows PC for the client (portable — unzip and run)
- Music library on a NAS (SMB share) or local to the player

## Download & Install

1. Grab the latest `hqcueplayer-x.x.x-windows.zip` from [Releases](../../releases)
2. Unzip anywhere, run `hqcueplayer.exe`
3. Enter your player IP, hit **Scan / Connect** — the Linux daemon (hqpd) **deploys itself automatically**
4. Full illustrated guide: see the bundled *User Manual* (PDF)

## License

- **Public beta**: report bugs in the forum thread to get a free Pro test key
- **Free tier**: first 5 tracks of each album + basic DSP switching — no time limit, no noise, no watermark
- **Pro**: DSP scene presets, direct rate selection, image track-splitting, cross-album gapless, unlimited playlists, mobile remote

**Instant activation** — paste your key (`HQCP-XXXX-XXXX`), hit **Activate**. The software binds the key to your player hardware automatically — no machine IDs to copy, no email round-trips.

- Runs **100% offline forever** once activated — no phone-home, no telemetry
- Air-gapped player? Offline license-file import is available as a fallback
- One key = one player. OS reinstall or hardware change alters the machine ID — just contact the author for a transfer

## Disclaimer

HQ CuePlayer is an independent third-party front-end, not affiliated with Signalyst or HQPlayer. It talks to HQPlayer Embedded through its documented network control interface — nothing is disassembled, modified, or reverse-engineered.
