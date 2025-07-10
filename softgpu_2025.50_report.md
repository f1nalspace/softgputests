##########################

SoftGPU 2025.50 Testreport

##########################

# Host

- AMD Ryzen 7950X
- ASUS TUF Gaming X670E-Plus
- G.Skill Trident Z5 Neo EXPO 2x32 GB DDR5-6000
- ASUS Rog Strix RTX 3090, 24 GB
- Creative Soundblaster AE-7
- Main Storage: Samsung 990 Pro, 2TB
- VM Storage: Samsung 990 Pro, 2TB

- Windows 11 Pro 24H2
- NVIDIA 572.16 Studio Driver
- VMWare Workstation 17.5.2

# VMWare Workstation

All virtual machines have the following base configuration:

- Memory: 2 GB (after patchmem)
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

All games uses default settings.

## v9

- Uses VMware hardware compability 9.x

### Quake 2

Starting game with level 1 and looking at the glass window

#### Default OpenGL / 640x480

- Runs perfect with 65-75 fps

#### Known Issues

- Startup of level 1 sometimes just stops with a bluescreen after movie was shown

### Quake 3 Arena

Running timedemo with demo "four.dm_66":

#### Default OpenGL / 640x480

- Runs perfect to good, depending on the situation

### Turok

#### 3Dfx / 640x480

- Runs perfect, butterly smooth

### Expendable (Too slow)

- After loading the game, it crashes with a messagebox, but it can be solved by executing "go.exe" and passing -nocputest

https://www.pcgamingwiki.com/wiki/Expendable

#### Direct Draw / 640x480 16-bit

- Game is not playable, performance is extremely poor, even with lowest graphic settings

### Rollcage

#### Glide / 640x480

- Runs good (~45-60 fps)

### Forsaken (Not working)

- Any 3D acceleration won't work
- Software rendering won't work either
- No picture, just pure black with a menu at the top
- Invisible menu works and you could start a game, but the back buffering is fully broken and it flickers a lot
- Sound & music is playing just fine

### Autobahn Raser (Graphic errors)

#### 320x240 or 640x480

- Shows a error messagebox and does not start any race
- Menu fully works
- Sound & music is playing just fine

#### 3D

- Only 2D is working
- Does not render any 3D

### Croc (Not working)

- Won't boot up regardless of the settings, even with software

### Blood 2 (Mouse/Game too fast)

#### Direct3D HAL / 640x480

- Mouse is too fast
- Game is too fast
- Not able to play

- Menu fully works
- Sound & music is playing just fine
- Game rendering seems fine

### Croc 2

#### Direct3D HAL / 640x480

- Works great, but feels a little too fast

### Drakan - Order of the Flame (Too slow)

#### 640x480 16-bit

- Too slow, ~10-15 fps
- Menu has low performance
- Game has low performance

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

### kkrieger (Too slow)

- Works with 20-30 fps, but has no graphical issues

### Oni

### 640x480 32-bit

- Runs perfect, butterly smooth

### Red Faction

#### Direct 3D HAL /  640x480 32-bit

- Runs perfect, butterly smooth

- Previous SoftGPU releases was not working for this title at all (it was too fast)

### Unreal Tournament

#### 3Dfx / 640x840 16 bit

- Low performance: ~20-30 fps

#### OpenGL / 640x840 16 bit

- Runs perfect, butterly smooth

#### OpenGL / 640x840 32 bit

- Crashes with a pixel format error

#### Direct3D / 640x840 32 bit

- Works perfect, butterly smooth

### Unreal Gold

#### 3Dfx Glide / 640x480 16-bit

- Slow performance: +10 fps

#### Direct3D / 640x480 32-bit

- Works perfect, butterly smooth

### Tomb Raider II

- Won't startup
- Setup tool shows a black window, does nothing

### Tomb Raider III

- Won't startup and will not show the setup tool
- Setup tool crashes the VM

## v10

- Uses VMware hardware compability 17.5.x
