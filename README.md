## Hi guys, it's my niri setup which i daily use.

#### I am setting this up to break down how to create dotfiles and use them on my laptop. Niri is my first window manager, and I love using it. I want to switch to labwc, but for now, I'm still using Niri.

*i think i will never switch to labwc, there now some i realy need to use. maybe i will use gnome or etc*

I translated some comments in the Niri config to my language (Russian).

I’m using a custom version of Niri. My version includes blur effects, but I’ve disabled them in the config. If you want to use blur, you can download the Niri version with blur from [there](https://www.reddit.com/r/niri/comments/1l8mj0k/for_those_who_cant_wait_anymore_for_blur_here_is/?share_id=fQoS3EHcK6C6ETD85KhyW&utm_content=2&utm_medium=android_app&utm_name=androidcss&utm_source=share&utm_term=1).
## I have 2 variants of setup
---

| Waybar setup                | DankMaterialShell setup         |
| --------------------------- | ------------------------------- |
| ![330](/images/preview.png) | ![330](/images/preview_dms.png) |
## In waybar rice, i used
---
- **bar** - waybar 
- **osd** - swayosd
- **notification** - swaync
- **lock screen** - gtklock - you need to edit config, to add your walppaer
- **fastfetch**
- **shell** - fish
- **terminal** - ghostty
- **app launcher** - vicinae 
	*in vicinae i have cliboard manager too*
- **qt and gtk theme** - gruvbox 
	*in apps i use material gruvbox or soft gruvbox*
- **wallpaper manager** - swww for background and swaybg for overview 
- **nmgui and blueberry** for setup wifi and bluetooth
- **image viewver** - loupe
#### package dependencies
***installed on arch***
```
yay -S qt6ct qt5ct swww swaybg gtklock vicinae waybar swayosd swaync swayidle mate-polkit xdg-desktop-portal xdg-desktop-portal-gnome xdg-desktop-portal-gtk xdg-desktop-portal-wlr nwg-look zed nautilus blueberry nmgui kvantum loupe waypaper
```

*maybe it's not all*

------------------------------------------
## Gallery 

| ![330](/images/ghostty_ff.png)ghostty | ![330](/images/osd_sound.png)swayosd |
| ------------------------------------- | ------------------------------------ |
| ![330](/images/vicinae.png)vicinae    | ![330](/images/overview.png)overview |
| ![330](/images/ghostty_small_ff.png)  | ![330](/images/firefox_blur.png)     |

-------------------------------
## For DankMaterialShell rice, i used

- **dankmaterialshell** - for all i used before))
- **fastfetch**
- **shell** - fish
- **terminal** - kitty 
- **qt and gtk theme** - gruvbox and mutagen  
	*in apps i use material gruvbox or soft gruvbox*
- **image viewver** - loupe
#### package dependencies
***installed on arch***
```
yay -S qt6ct qt5ct swayidle mate-polkit xdg-desktop-portal xdg-desktop-portal-gnome xdg-desktop-portal-gtk xdg-desktop-portal-wlr nwg-look zed nautilus blueberry nmgui kvantum loupe waypaper dms
```

