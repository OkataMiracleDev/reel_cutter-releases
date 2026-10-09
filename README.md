# ReelCutter for Windows

ReelCutter turns long talking videos into short reels for TikTok, Instagram Reels, YouTube
Shorts and X. It finds the **complete thoughts** in a talk, interview or podcast and exports
the best ones as clean clips, ready to drop into CapCut or Premiere Pro.

Everything runs on your own PC. Your videos never leave your computer, and there are no
API keys or cloud accounts to set up.

**[Download the latest version](https://github.com/OkataMiracleDev/reel_cutter-releases/releases/latest)**

> This repository holds ReelCutter's installers and update files only. ReelCutter is
> proprietary software and is not open source; its source code is not published. See
> [License](#license).

---

## What it does

- **Find reels.** Drop in video files, or paste links to videos you have permission to use.
  ReelCutter transcribes the speech, finds where each thought starts and ends, and exports
  the best ones (5 by default, up to 20) as clips between 30 seconds and 3 minutes long,
  at the original quality.
- **Styles.** Pick what you're after: complete thoughts, or the moments most likely to
  perform (*Clips*, *Hot takes*, *Story*, *Value*, *Soundbites*).
- **Deep scan.** An optional local AI re-ranks the best candidates and explains each pick.
- **Script to video.** Paste a script and get a faceless video with a voiceover, a picture
  for every scene and word-by-word captions.
- **Built-in editor.** Trim and arrange your clips without leaving the app.
- **Clipping gigs.** A gallery of sites that pay clippers per view.
- **Batch processing.** Queue as many videos as you like; they run in the background.

## System requirements

- Windows 10 or 11, 64-bit
- An internet connection for the first setup and for each AI model's first download
- Free disk space for the Python environment and AI models (several GB if you use every
  feature)
- Optional: an NVIDIA graphics card for faster transcription

## Install

1. Download `ReelCutter-<version>-windows.zip` from the
   [latest release](https://github.com/OkataMiracleDev/reel_cutter-releases/releases/latest)
   and unzip it.
2. Run `ReelCutter-Setup-<version>.exe`.
   The installer isn't code-signed yet, so Windows may say "Windows protected your PC".
   Click **More info**, then **Run anyway**.
3. Read and accept the license agreement.
4. Choose the program folder, then the folder where ReelCutter keeps its files (your
   clips, downloaded videos and AI models).
5. The installer sets up everything else. The first setup takes several minutes.

Each AI model downloads the first time you use it. After that ReelCutter works offline,
except for downloading videos from links.

## Updates

ReelCutter checks this page for new versions when it starts and every few hours. When an
update is out, it shows what changed and offers **Download and install**. Updating
replaces only the program: your clips, downloads and models are kept.

## Privacy

ReelCutter processes your videos on your PC. It does not send your videos, transcripts or
clips anywhere, and it does not collect analytics or telemetry. It only goes online to
check for updates, set itself up, download AI models, download the links you paste, and
open websites you choose.

## Your responsibility

Only download, clip and publish videos you have the rights or permission to use, and
follow the rules of the platforms and clipping programs you post to. AI voices and
pictures must not be used to impersonate or deceive people. See the
[license agreement](LICENSE) for the full terms.

## Help and feedback

Found a bug or have a question? [Open an issue](https://github.com/OkataMiracleDev/reel_cutter-releases/issues).
Please include your ReelCutter version and, for errors, the `logs\reelcutter.log` file
from your ReelCutter files folder.

## License

Copyright © 2026 Miracle Okata. All rights reserved.

ReelCutter is **proprietary software. It is not open source.** It is currently free to
use; pricing will be announced later. Your use of ReelCutter is governed by the
[End User License Agreement](LICENSE), which you accept when you install it. In short,
you may install and use ReelCutter to make your own content, but you may not
redistribute, resell, modify or reverse engineer it.

ReelCutter uses open-source components and open AI models, each under its own license.
They are listed in [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md), which is also included in
every download.
