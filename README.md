# HQ CuePlayer

**Seamless CUE & disc-image playback console for HQPlayer Embedded**
Drop in CUE sheets or CD/SACD images — play instantly, bit-perfect, no extraction.

---

## What is this

HQPlayer sounds world-class, but it officially supports neither CUE sheets nor disc images. HQ CuePlayer is a dedicated front-end that sits in front of HQPlayer Embedded and removes that pain for good:

- **Drag & play**: drop a `.cue` (with its WAV/FLAC/APE/WV image) or a CD/SACD image (`.iso .nrg .bin .ccd .img`) into the window — auto-parsed, losslessly sliced in memory, playing in seconds
- **Bit-perfect pipeline**: in-memory slicing, zero resampling, zero DSP, zero volume processing — your data reaches the HQPlayer engine untouched
- **NAS zero-copy**: when dropped files match a path mapping, the Linux player reads the NAS directly — instant start, nothing uploaded
- **Full engine control**: output rate, filters, modulators and DSP scene presets, one click away
- **Mobile remote**: control playback from any phone browser on your LAN
- **Playlists / favorites / history / lyrics / cover art**: everything the official client never gave you

## Requirements

- A Linux box running **HQPlayer Embedded 5.x** (or an NAA bridge setup)
- A Windows PC for the client (portable — unzip and run)
- Music library on a NAS (SMB share) or local to the player

## Download & Install

1. Grab the latest `hqcueplayer-x.x.x-windows.zip` from [Releases](../../releases)
2. Unzip anywhere, run `hqcueplayer.exe`
3. Enter your player IP, hit **Scan / Connect** — the Linux daemon (hqpd) **deploys itself automatically**, nothing to install by hand
4. Full illustrated guide: see the bundled *User Manual* (PDF)

## License

- **Free tier**: first 5 tracks of each album + basic DSP switching — no time limit, no noise, no watermark
- **Pro**: DSP scene presets, direct rate selection, image track-splitting, cross-album gapless, playlists, mobile remote
- Activate online with a license key, or import a license file (works fully offline)
- Reinstalling the OS or changing hardware alters the machine ID — contact the seller for reactivation

## Disclaimer

HQ CuePlayer is an independent third-party front-end, not affiliated with Signalyst or HQPlayer.
