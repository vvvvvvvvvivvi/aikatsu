## Aikatsu (cab)

https://vvvvvvvvvivvi.github.io/aikatsu/ 

A small web page that imitates the feel of playing the *Aikatsu!* arcade cabinet. A YouTube gameplay video plays on the "screen" at the top, and a set of pressable buttons sits below it. The catch is nothing is scored or judged. You watch the video and press along with it.

It is a single file (`index.html`) with no build step and no dependencies.

## Features

- **Video screen:** paste any YouTube link and the video plays inside a cabinet-style screen.
- **Song select screen:** a menu styled after the cabinet's stage-select screen. Pick a song with the left and right buttons and confirm with the red one. The song list lives in the `SONGS` array near the bottom of `index.html`, where you can change titles, start times and difficulty.
- **Two control layouts:** a three-panel pad (up, left and right arrows) and a set of six arcade buttons in two clusters. A switch above the pad changes between them.
- **Button feel:** buttons sink and light up when pressed, play a synthesised cymbal-style sound, and give a short vibration on devices that support it.
- **Multi-touch:** several buttons can be pressed at once on a touchscreen.
- **Responsive layout:** the video sits above the controls on phones and tablets in portrait. On laptops and landscape screens the video is on the left and the controls are on the right.

## Controls

| Layout | Input |
| --- | --- |
| 3DS pad | Arrow keys (up, left, right), or tap the panels |
| Arcade buttons | red `A` / `J`, green `D` / `K`, yellow `S` / `L`, or tap the buttons |

Click or tap the page once first so it can receive keyboard input. Browsers also only allow sound after the first interaction, so the first press on some devices (Safari in particular) may be silent.

## Using it

1. Open the page.
2. Paste a YouTube link into the box under the screen and press **Play**.
3. Press along with the buttons.

The **Find videos** button opens a YouTube search for Aikatsu cabinet gameplay. If a video shows an error in the player, the uploader has probably disabled embedding. Use the **Open on YouTube** button or try another video.

Supported link formats: standard watch links, `youtu.be` short links, mobile links, embed links and Shorts links.

## Technical notes

- Plain HTML, CSS and JavaScript in one file.
- Button sounds are generated in the browser with the Web Audio API. No audio files are included.
- The button pads are drawn with CSS and inline SVG. No image files are included.
- The video is a standard YouTube embed. The page does not download, copy or host any video.

## Disclaimer
 
This is an unofficial, non-commercial fan project made for personal use and learning. It is **not** affiliated with, endorsed by or connected to Bandai, Bandai Namco, Sunrise, BN Pictures, TV Tokyo, Dentsu or any other rights holder of the *Aikatsu!* franchise.
 
This project is an imitation of the general look and feel of an arcade machine. It is not a game, does not run any *Aikatsu!* software, and does not contain, reproduce or distribute any of the franchise's game data.
 
## Copyright and trademarks
 
- *Aikatsu!*, *Data Carddass*, and all related names, logos, characters, music and artwork are the property of their respective owners and are used here only to identify the subject of this fan project. All rights belong to those owners.
- Song thumbnails in the menu are loaded live from YouTube and are not stored in this repository.
- This repository contains no characters, card art, screenshots, music or voice recordings from the franchise. The one exception is the star emblem used as the browser tab icon. It is franchise artwork that belongs to its rights holders, it is included only as a fan tribute, and it will be removed on request.
- Videos shown in the player are embedded from YouTube and remain the property of the people who uploaded them and of any rights holders. This project does not host them, and embedding depends on each uploader's settings and YouTube's terms of service.
- The cabinet design and layout are original CSS and SVG artwork made to resemble the general arrangement of the real machine's controls.
If you are a rights holder and would like something changed or removed, please open an issue on this repository or contact the owner, and it will be dealt with promptly.
 
## Using this project 
```
MIT License Vivian Lee
 
Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:
 
The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
 
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
 
The MIT License covers only the original code. It does not give anyone rights to the *Aikatsu!* name or any franchise material, and it does not cover any videos played through the embed.
 
