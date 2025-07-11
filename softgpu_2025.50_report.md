# Games Testreport for **_SoftGPU 2025.50_**

Last Update: **2025-07-11**

## Host

- AMD Ryzen 7950X
- ASUS TUF Gaming X670E-Plus
- G.Skill Trident Z5 Neo EXPO 2x32 GB DDR5-6000
- ASUS Rog Strix RTX 3090, 24 GB
- Creative Soundblaster AE-7
- Main Storage: Samsung 990 Pro, 2TB
- VM Storage: Samsung 990 Pro, 2TB


## Software


- Windows 11 Pro 24H2
- NVIDIA 572.16 Studio Driver
- VMWare Workstation 17.5.2

# VMWare / GPUv9

All games uses default settings with **640x480**.

All virtual machines have the following base configuration:

- VMware hardware compability: 9.x
- Memory: 2 GB
- CPU: 1:1 (Virtualize Intel VT-x/EPT or AMD_V/RVI)
- Harddisk: 40 GB IDE
- CD/DVD
- Floppy
- USB: 1.1
- Sound Card (sound.virtualDev = "es1371")
- Display, 256 MB, Stretch Mode: Keep aspect ratio stretch, Accelerate 3D graphics
- Windows 98 SE (patch9x, patchmem)
- Desktop: 800x600 32-bit
- SoftGPU 2025.50

## Games/Demos

| Game Name | Publisher/Developer | Version | Compability | Issues | DirectDraw | Direct3D | OpenGL | Glide | Software |
| --------- | ------------------- | ------- | ----------- | ------ | ---------- | -------- | ------ | ----- | -------- |
| Alien vs Predator 2 | Fox Interactive | 096 | 🟢 Fully working | Not great performance | ⚫ | 🟠 | ⚫ | ⚫ | ⚫ |
| American Mc'Gees Alice | Electronic Arts | 1.0 | 🟢 Fully working | - | ⚫ | ⚫ | 🟢 | ⚫ | ⚫ |
| Autobahn Raser |  Davilex | 1.0 | 🟠 Partially working | Error Message / 2D rendering only / Buffer broken | 🟡 | ⚫ | ⚫ | ⚪ | ⚫ |
| Blood 2 | Monolith | 1.0 | 🔵 Too fast | Mouse / Game is too fast | ⚫ | 🟢 | ⚫ | ⚫ | ⚫ |
| Croc | Fox Interactive | 1.0 | 🔴 Not working | Crashes on startup | ⚫ | ⚫ | ⚫ | ⚫ | ⚫ |
| Croc 2 | Argonaut Software | 1.0.0.1 | 🟢 Fully working | Feels a bit too fast | ⚫ | 🟢 | ⚫ | ⚫ | ⚫ |
| Descent 3 | Outrage | 1.0 | 🔵 Rendering bugs | Glide and OpenGL crashes with a error message, direct draw has rendering bugs | 🟠 | ⚫ | ⚪ | ⚪ | ⚫ |
| Drakan - Order of the Flame | Psygnosis | Build 375/445 | 🔵 Too slow | Extremely slow, unable to play | ⚫ | 🔴 | ⚫ | ⚫ | ⚫ |
| Expendable | Rage Entertainment | 1.0 | 🔵 Slide show | Absolute slide show, but menu feels very responsive | 🔴 | ⚫ | ⚫ | ⚫ | ⚫ |
| FIFA 98 | Electronic Arts | 1.0 | 🔴 Not working | Won't startup | ⚫ | ⚫ | ⚫ | ⚫ | ⚫ |
| Forsaken | Acclaim Entertainment | 1.0.1 | ⚪ No rendering | Copyright shows but no error message or game won't start up | ⚫ | ⚪ | ⚫ | ⚪ | ⚪ |
| Half-Life | Sierra/Valve | 1.1.1.0 | 🟢 Fully working | 3Dfx a bit slower | ⚫ | 🟡 | 🟡 | 🟡 | 🟢 |
| Heavy Metal FAKK 2 | Ritual Entertainment | 1.0.2 | 🟢 Fully working | - | ⚫ | ⚫ | 🟢 | ⚫ | ⚫ |
| Heretic 2 | Activision | 1.0 | 🟠 Partially working | 3Dfx not working | ⚫ | ⚫ | 🟡 | ⚫ | ⚫ |
| Max Payne | Remedy Entertainment | 1.05 | 🟢 Fully working | Requires rlmfc.dll fix for ryzen based cpu's | ⚫ | 🟢 | ⚫ | ⚫ | ⚫ |
| Motorhead | Digital Illusions CE | 1.0 | 🟠 Partially working | Graphical bugs in glide (blue colors), Slideshow in direct draw | 🔴 | ⚫ | ⚫ | 🟡 | 🟢 |
| Need for Speed II Special Edition | Electronic Arts | 1.0 | 🟠 Not working | Crashes on startup | ⚫ | ⚫ | ⚫ | ⚫ | ⚫ |
| Need for Speed III | Electronic Arts | 1.0 | 🟠 Not working | Menu not working, Game not working | ⚫ | ⚫ | ⚫ | ⚫ | ⚫ |
| No One Lives Forever | Fox Interactive | 1.0 | 🟢 Fully working | Performance is okay, but not great | ⚫ | 🟡 | ⚫ | ⚫ | ⚫ |
| Oni | Bungie | 1.0 | 🟢 Fully working | - | ⚫ | 🟢 | ⚫ | ⚫ | ⚫ |
| Pitfall: The Mayan Adventure | Activision | 1.0 | 🟢 Fully working | Micro stuttering | 🟠 | ⚫ | ⚫ | ⚫ | ⚫ |
| POD | Ubisoft | 1.0 | 🟢 Fully working | Glide has tons of graphic bugs, Crashes on exit | ⚫ | ⚫ | ⚫ | ⚪ | ⚫ |
| Prince of Persia: Sands of Time | Ubisoft | 1.0 | 🔵 Partially working | Characters are not rendered properly | ⚫ | 🟡 | ⚫ | ⚫ | ⚫ |
| Quake II | ID Software | 1.0 | 🟢 Fully working | - | ⚫ | ⚫ | 🟢 | 🟢 | ⚫ |
| Quake III Arena | ID Software | 1.0 | 🟢 Fully working | Intro level performance is kind of slow, but the rest of the game is just fine | ⚫ | ⚫ | 🟡 | ⚪ | ⚫ |
| Red Faction | Volition Inc | 1.00 | 🟢 Fully working | - | ⚫ | 🟢 | ⚫ | ⚫ | ⚫ |
| Return To Castle Wolfenstein | ID Software | 1.0.0 | 🟢 Fully working | - | ⚫ | ⚫ | 🟢 | ⚫ | ⚫ |
| Rollcage | Psygnosis | 1.00 | 🟢 Fully working | Performance on glide okay, direct draw is a slide show | 🔴 | ⚫ | ⚫ | 🟡 | ⚫ |
| Septerra Core | Valkyrie Studios/TopWare | 1.02 | 🟢 Fully working | 3Dfx not working  | 🟢 | ⚫ |⚫ | ⚫ | ⚫ |
| Star Trek: Voyager Elite Force | Activision | 1.10 | 🟢 Fully working | 3Dfx not working  | ⚫ | ⚫ |🟡 | ⚪ | ⚫ |
| Star Wars Jedi Knight II | Lucasarts | 1.0 | 🟢 Fully working | - | ⚫ | ⚫ | 🟢 | ⚫ | ⚫ |
| Tomb Raider II | Eidos | 1.0 | ⚫ Not working | Crashes on the setup tool | ⚫ | ⚫ | ⚫ | ⚫ | ⚫ |
| Tomb Raider III | Eidos | 1.0 | ⚫ Not working | Crashes on the setup tool | ⚫ | ⚫ | ⚫ | ⚫ | ⚫ |
| Turok | Acclaim Entertainment | 1.0 | 🟢 Fully working | Cut scens runs rather slow | ⚫ | ⚫ | ⚫ | 🟡 | ⚫ |
| Unreal Gold | Epic | 226 | 🟢 Fully working | Glide is a slideshow | ⚫ | 🟢 | 🟢 | 🔴 | ⚫ |
| Unreal Tournament | Epic | 432 | 🟢 Fully working | Glide is kind of slow, 32-bit OpenGL not working | ⚫ | 🟢 | 🟢 | 🟠 | ⚫ |

## Demos/Benchmarks

| Demo Name | Publisher/Developer | Version | Compability | Issues | DirectDraw | Direct3D | OpenGL | Glide | Software |
| --------- | ------------------- | ------- | ----------- | ------ | ---------- | -------- | ------ | ----- | -------- |
| kkrieger Demo | Farbrausch | 1.0 | 🟢 Fully working | Performance very poor | ⚫ | 🟠 | ⚫ | ⚫ | ⚫ |

## Legend

### Compability

Describes how the game works, independent of the performance.

| Symbol | Description |
| ------ | ----------- |
| ⚫ | Game failed to start |
| ⚪ | Game starts up, but does not render anything |
| 🔴 | Game is not working, but menu starts up just fine |
| 🔵 | Game is working, but has issues that makes it unplayable |
| 🟠 | Game is partially working and is playable |
| 🟢 | Game is fully working |

### Performance

Describes the performance of the rendering backend.

| Symbol | Description |
| ------ | ----------- |
| ⚫ | Not supported |
| ⚪ | Not working or unable to measure |
| 🔴 | Runs extremely poorly, 0-15 fps |
| 🟠 | Runs okay, 15-30 fps |
| 🟡 | Runs good, 30-60 fps |
| 🟢 | Runs butter smooth, 60+ fps |

---

## Details

This contain only titles that have issues and requires further details/screenshots.

### Alien vs Predator 2 (Not great performance)

#### Direct3D HAL / 640x480 32-bit

- Performance is not great, but it is playable

---

### American Mc'Gees Alice

#### OpenGL / 640x480 16-bit

- Runs very well

---

### Autobahn Raser (Graphic errors)

#### 320x240 or 640x480

- Shows a error messagebox and does not start any race
- Menu fully works
- Sound & music is playing just fine

#### 3D (Glide)

- Only 2D is working
- Does not render any 3D

![autobahn raser track no 3d](https://github.com/user-attachments/assets/3b25d5a8-12ad-4403-962f-0571ce3690e7)

---

### Blood 2 (Mouse/Game too fast)

#### Direct3D HAL / 640x480

- Mouse is too fast
- Game is too fast
- Not able to play

- Menu fully works
- Sound & music is playing just fine
- Game rendering seems fine

---

### Croc (Not working)

- Won't boot up regardless of the settings, even with software

---

### Croc 2

#### Direct3D HAL / 640x480

- Works great, but feels a little too fast

---

### Descent 3 (Not really working)

#### Glide

- Not working, crashes a pixel format expeption

#### OpenGL

- Not working, crashes with a weird error message

#### Direct3D HAL / 640x480

- Graphic rendering bugs, blacks almost everywhere

![descent3_d3d_black](https://github.com/user-attachments/assets/f778551b-5b86-481d-b99b-e30a071fbcb4)

---

### Drakan - Order of the Flame (Too slow)

#### 640x480 16-bit

- Too slow, ~10-15 fps
- Menu has low performance
- Game has low performance

---

### Expendable (Too slow)

- After loading the game, it crashes with a messagebox, but it can be solved by executing "go.exe" and passing -nocputest

https://www.pcgamingwiki.com/wiki/Expendable

#### Direct Draw / 640x480 16-bit

- Game is not playable, performance is extremely poor, even with lowest graphic settings

---

### FIFA 98 (Not working)

- Does not startup at all and freezes windows, until the task is killed

---

### Forsaken (Not working)

- Any 3D acceleration won't work
- Software rendering won't work either
- No picture, just pure black with a menu at the top
- Invisible menu works and you could start a game, but the back buffering is fully broken and it flickers a lot
- Sound & music is playing just fine

---

### Half-Life

#### Software / 640x480

- Runs good, ~60 fps

#### OpenGL / 640x480

- Runs good, ~60 fps

#### Direct3D / 640x480

- Runs good, ~60 fps

#### 3Dfx mini driver / 640x480

- Runs good, ~50-60 fps
- UI Rendering issues

---

### Heavy Metal FAKK 2

#### OpenGL / 640x480 32-bit

- Works perfect, butterly smooth

---

### Heretic 2

#### 3Dfx / 640x480

- Not working

#### OpenGL / 640x480 32-bit

- Runs good, ~50-60 fps

---

### kkrieger (Too slow)

- Works with 20-25 fps

---

### Max Payne (Not working)

- Added rlmfc DLL fix (luigoalma) for Ryzen CPU's

#### D3D Hardware T&L / 640x480 32-bit

- Crashes the VM and failed to power off automatically
- Was working before with SoftGPU 2024.40

---

### Motorhead (Partially working)

#### 3Dfx / 640x480

- Graphics rendering issues, blue colors in some areas

![motorhead_glide_640x480_blue_issue](https://github.com/user-attachments/assets/1d6ebce6-5059-4c0c-924c-fa83edaf9e83)

#### DirectDraw HAL / 640x480

- Slide show, ~5-10 fps

#### Software / 640x480

- Works perfect, butterly smooth

---

### Need for Speed II Special Edition (Not working)

- Crashes with the typical memory access violation dialog

---

### Need for Speed III (Not working)

- Requires "Need For Speed III Modern Patch v1.6.1", otherwise it won't start on modern CPU's

#### Default Graphics Accelerator

- Intro Videos works
- Menu does not show up (black screen)
- Sound and music is working just fine

---

### No One Lives Forever

#### Direct3D HAL / 640x480 16-bit

- Runs good, almost at 60 fps

---

### Oni

#### 640x480 32-bit

- Runs perfect, butterly smooth

---

### Pitfall: The Mayan Adventure (Stuttering)

#### DirectDraw

- Game input/rendering stuttering

---

### POD (Broken rendering)

#### Glide

- Tons of graphics bugs, white textures almost everywhere

![pod_glide_broken](https://github.com/user-attachments/assets/2f0cec0e-49ca-4d50-903f-46983749daa1)

---

### Prince of Persia: Sands of Time (Broken rendering)

- Note that the minimum pixel/vertex shader version is not sufficient

#### 640x480 32-bit

- Characters are not rendered properly
- Performance is okay, but not butterly smooth

---

### Quake 2

Starting game with level 1 and looking at the glass window

#### Default OpenGL / 640x480

- Runs perfect with 65-75 fps

#### Known Issues

- Startup of level 1 sometimes just stops with a bluescreen after movie was shown

---

### Quake 3 Arena

Running timedemo with demo "four.dm_66":

#### Default OpenGL / 640x480

- Runs perfect to good, depending on the situation

---

### Red Faction

#### Direct 3D HAL /  640x480 32-bit

- Runs perfect, butterly smooth

- Previous SoftGPU releases was not working for this title at all (it was too fast)

---

### Return To Castle Wolfenstein

#### OpenGL / 640x480 32-bit

- Runs perfect, butterly smooth

---

### Rollcage

#### Glide / 640x480

- Runs good (~45-60 fps)

---

### Septerra Core

#### DirectDraw

- Runs perfect, butterly smooth

---

### Star Trek: Voyager Elite Force

#### OpenGL / 640x480

- Runs perfect, butterly smooth

---

### Star Wars Jedi Knight II

#### OpenGL / 640x480

- Runs perfect, butterly smooth

---

### Tomb Raider II (Not working)

- Won't startup
- Setup tool shows a black window, does nothing

---

### Tomb Raider III (Not working)

- Won't startup and will not show the setup tool
- Setup tool crashes the VM

---

### Turok

#### 3Dfx / 640x480

- Runs perfect, butterly smooth

---

### Unreal Gold

#### 3Dfx Glide / 640x480 16-bit

- Slow performance: ~10 fps

#### Direct3D / 640x480 32-bit

- Works perfect, butterly smooth

---

### Unreal Tournament

#### 3Dfx / 640x840 16 bit

- Low performance: ~20-30 fps

#### OpenGL / 640x840 16 bit

- Runs perfect, butterly smooth

#### OpenGL / 640x840 32 bit

- Crashes with a pixel format error

#### Direct3D / 640x840 32 bit

- Runs perfect, butterly smooth

---

# VMWare / GPUv10

All games uses default settings with **640x480**.

All virtual machines have the following base configuration:

- VMware hardware compability: 17.5.x
- Memory: 2 GB
- CPU: 1:1 (Virtualize Intel VT-x/EPT or AMD_V/RVI)
- Harddisk: 40 GB IDE
- CD/DVD
- Floppy
- USB: 1.1
- Sound Card (sound.virtualDev = "es1371")
- Display, 256 MB, Stretch Mode: Keep aspect ratio stretch, Accelerate 3D graphics
- Windows 98 SE (patch9x, patchmem)
- Desktop: 800x600 32-bit
- SoftGPU 2025.50

---
