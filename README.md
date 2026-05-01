# Visual - a free, open source, cross-platform video editor

<div align="center">
<img src="https://www.shotcut.org/assets/img/screenshots/Shotcut-18.11.18.png" alt="screenshot" />
</div>

Visual is a heavily modified fork of Shotcut with significantly improved features and workflow enhancements.

## Install
Releases available at [github.com/YoYoStudios/Visual/releases](https://github.com/YoYoStudios/Visual/releases).

## Dependencies
- [MLT](https://www.mltframework.org/): multimedia authoring framework
- [Qt 6 (6.4 minimum)](https://www.qt.io/): application and UI framework
- [FFTW](https://fftw.org/)
- [FFmpeg](https://www.ffmpeg.org/): multimedia format and codec libraries
- [Frei0r](https://www.dyne.org/software/frei0r/): video plugins
- [SDL](http://www.libsdl.org/): cross-platform audio playback

## License
GPLv3. See [COPYING](COPYING).

## How to build
### Qt Creator
The fastest way to build is through [Qt Creator](https://www.qt.io/download#qt-creator).

### From command line
```
cmake -DCMAKE_INSTALL_PREFIX=/usr/local/ /path/to/visual
cmake --build .
cmake --install .
```
