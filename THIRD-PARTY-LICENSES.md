# Third-party licences

LapZero uses the software below.  Each part keeps its own licence.

## Qt 6

LapZero uses the Qt 6 libraries (Qt Core, Qt GUI and Qt Widgets) from The Qt Company and contributors, under the GNU Lesser General Public License version 3 (LGPL-3.0).

- LapZero links to Qt dynamically.  It uses the Qt libraries your distribution provides, and Qt is not changed in any way.
- You can replace those libraries with your own build of Qt, and LapZero will use it.
- Qt source code: https://download.qt.io/official_releases/qt/ or from your distribution's source packages.
- The full LGPL-3.0 text, and the GPL-3.0 text it builds on, are included with LapZero (`licenses/LGPL-3.0.txt` and `licenses/GPL-3.0.txt`).

## Programs LapZero runs

LapZero runs these as separate programs.  They are not part of LapZero and are installed by your distribution or by Steam, under their own licences:

- Steam (Valve Corporation)
- protontricks and winetricks
- bubblewrap (`bwrap`)
- polkit (`pkexec`)

## LapZero Proton build

The LapZero Proton build is downloaded separately from its own repository, where its source code is published:
https://github.com/DanFraserUK/proton-cachyos
