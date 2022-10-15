# mpv-copyStuff

This script copies to clipboard the:
- Filename (With Extension)
- Full Filename Path
- Relative Filename Path (Parent Directory + Filename)
- Current Video Time (HH:MM:SS.MS)
- Current Displayed Subtitle Text

## Installation

Put the script `copyStuff.lua` in your scripts folder, usually in:
- Windows: `"C:\Users\Username\AppData\Roaming\mpv\scripts"`.
- Linux and Mac: `"~/.config/mpv/scripts/"`.

To work, the script needs:
- Windows: `Powershell`.
- Linux/X11: `xclip`.
- Linux/Wayland : `xclip` or `wl-clipboard`.
- MacOS: `pbcopy` (not tested).

## Hotkeys

| What is Copied                       | Hotkey     |
| ------------------------------------ | ---------- |
| **Filename**                         | **CTRL+f** |
| **Full Filename Path**               | **CTRL+p** |
| **Relative Filename Path**           | **CTRL+r** |
| **Current Video Time (HH:MM:SS.MS)** | **CTRL+t** |
| **Current Displayed Subtitle Text**  | **CTRL+s** |


# Screenshots

![ss1](https://raw.githubusercontent.com/0xR3V/screenshots/main/mpv-copyStuff/example_01.png)
![ss2](https://raw.githubusercontent.com/0xR3V/screenshots/main/mpv-copyStuff/example_02.png)
![ss3](https://raw.githubusercontent.com/0xR3V/screenshots/main/mpv-copyStuff/example_03.png)
![ss4](https://raw.githubusercontent.com/0xR3V/screenshots/main/mpv-copyStuff/example_04.png)
![ss5](https://raw.githubusercontent.com/0xR3V/screenshots/main/mpv-copyStuff/example_05.png)
