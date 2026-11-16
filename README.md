# Konwerter: release binaries

Portable Windows 11 converter of video files, folders, images and DVD images (.iso, .nrg) to MP4 (H.264 + AAC), with NVIDIA NVENC/NVDEC when available.
This repository holds only the released `Konwerter-X.Y.Z-win64.exe` files. The source code is private.

The program checks this repository at start for a newer release and, after you confirm, downloads it, verifies its SHA-256 and replaces itself.
Every release asset carries its SHA-256 (shown by GitHub next to the file); compare it before running a downloaded copy by hand.

(c) 2026 JI Engineering. All rights reserved. https://iwanus.eu

## Third-party software inside the exe

| Component | License | Source |
|---|---|---|
| ffmpeg (BtbN GPL build) | GNU GPL v3 | https://github.com/BtbN/FFmpeg-Builds (build scripts, exact versions), https://ffmpeg.org/download.html |
| Python runtime, Tcl/Tk | PSF License, Tcl/Tk license | https://www.python.org, https://www.tcl-lang.org |
| Pillow | HPND | https://github.com/python-pillow/Pillow |
| psutil | BSD-3-Clause | https://github.com/giampaolo/psutil |
| PyInstaller bootloader | GPL-2.0 with the exception for built programs | https://github.com/pyinstaller/pyinstaller |

ffmpeg runs as a separate process. GPL v3 text: https://www.gnu.org/licenses/gpl-3.0.txt. If you cannot get the ffmpeg source from the links above,
write via https://iwanus.eu and the source of the bundled build will be provided.
