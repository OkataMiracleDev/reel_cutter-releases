# Third-party notices

ReelCutter is proprietary software (see `EULA.txt`). It is built on, ships with, or downloads
the open-source components and open AI models listed below. Each one stays under its own
license, set by its authors; ReelCutter's license does not apply to them and does not
limit the rights their licenses give you.

Copies of the bundled licenses are installed with ReelCutter:

- `editor/web/licenses/` — the FilmCraft video editor, its NOTICE and the fonts it bundles
- `ui/fonts/` and the desktop app's `fonts/` — the SIL Open Font License for Gabarito and Onest
- `models/` — a model's license file, where its download includes one
- the Python environment (`.venv/Lib/site-packages/*.dist-info/`) — the license of every
  Python package

## Bundled with the installer

| Component | License | Source |
|---|---|---|
| Electron | MIT | https://github.com/electron/electron |
| electron-updater | MIT | https://github.com/electron-userland/electron-builder |
| uv (package installer) | MIT or Apache-2.0 | https://github.com/astral-sh/uv |
| FilmCraft 0.4.0 (video editor, rebranded) | MIT or Apache-2.0 | https://github.com/storytold/filmcraft |
| Inter, JetBrains Mono, Noto Serif, Noto Sans Arabic, Noto Sans CJK SC, BIZ UDMincho, BIZ UDPGothic, Shippori Mincho (editor fonts) | SIL Open Font License 1.1 | see `editor/web/licenses/` |
| Gabarito (font) | SIL Open Font License 1.1 | https://fonts.google.com/specimen/Gabarito |
| Onest (font) | SIL Open Font License 1.1 | https://fonts.google.com/specimen/Onest |

## Installed during setup

ReelCutter's setup downloads these from their official sources. ReelCutter calls FFmpeg
as a separate program and does not link to it.

| Component | License | Source |
|---|---|---|
| Python 3.11 (python-build-standalone, via uv) | PSF License | https://www.python.org · https://github.com/astral-sh/python-build-standalone |
| FFmpeg (gyan.dev "essentials" build) | GPL-3.0 (this build) | https://www.gyan.dev/ffmpeg/builds/ · source: https://ffmpeg.org |
| faster-whisper | MIT | https://github.com/SYSTRAN/faster-whisper |
| CTranslate2 | MIT | https://github.com/OpenNMT/CTranslate2 |
| sentence-transformers | Apache-2.0 | https://github.com/UKPLab/sentence-transformers |
| Transformers, Tokenizers, Diffusers, huggingface_hub | Apache-2.0 | https://github.com/huggingface |
| PyTorch | BSD-3-Clause (and others, see its package) | https://github.com/pytorch/pytorch |
| scikit-learn | BSD-3-Clause | https://github.com/scikit-learn/scikit-learn |
| NumPy | BSD-3-Clause (and others, see its package) | https://github.com/numpy/numpy |
| SciPy | BSD-3-Clause | https://github.com/scipy/scipy |
| Gradio | Apache-2.0 | https://github.com/gradio-app/gradio |
| yt-dlp | Unlicense | https://github.com/yt-dlp/yt-dlp |
| yt-dlp-ejs | Unlicense, MIT, ISC | https://github.com/yt-dlp/ejs |
| Deno | MIT | https://github.com/denoland/deno |
| psutil | BSD-3-Clause | https://github.com/giampaolo/psutil |
| llama-cpp-python (Deep scan) | MIT | https://github.com/abetlen/llama-cpp-python |
| ONNX Runtime | MIT | https://github.com/microsoft/onnxruntime |
| PyAV | BSD-3-Clause | https://github.com/PyAV-Org/PyAV |
| NVIDIA cuBLAS and cuDNN (optional, GPU only) | NVIDIA Software License Agreement | https://developer.nvidia.com |

Other Python packages that these depend on are installed with them; each one's license is
in its `.dist-info` folder.

## AI models, downloaded on first use

| Model | Used for | License | Source |
|---|---|---|---|
| Whisper (CTranslate2 conversions: small, medium, large-v3) | Speech-to-text | MIT | https://huggingface.co/Systran |
| all-MiniLM-L6-v2 | Finding where thoughts start and end | Apache-2.0 | https://huggingface.co/sentence-transformers/all-MiniLM-L6-v2 |
| Qwen3-4B-Instruct-2507 (GGUF) | Deep scan | Apache-2.0 | https://huggingface.co/unsloth/Qwen3-4B-Instruct-2507-GGUF |
| Supertonic 3 | Script to video voiceover | OpenRAIL | https://huggingface.co/Supertone/supertonic-3 |
| SDXS-512-DreamShaper | Script to video pictures | OpenRAIL++ | https://huggingface.co/IDKiro/sdxs-512-dreamshaper |

The OpenRAIL and OpenRAIL++ licenses include use-based restrictions: things the model may
not be used for, such as harming people, deceiving people or breaking the law. Read them
on the model pages above. By using Script to video you agree to follow them.
