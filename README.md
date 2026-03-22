# ➤ NIRI GREEN RICE 🐸

If you like Niri and light-coloured themes, this guide is for you. I’ve been looking for themes, fonts, backgrounds… All this to achieve a sleek, fluid and polished look for a functional desktop. If you like a blend of style and practicality, this layout could serve as a starting point for creating your own.

## ➜ Features

- Detailed step-by-step customisation guide
- Configuration files
- Wallpapers
- Some tips

## ➜ Preview

**Desktop:**
![NIRI](./Preview/Desktop.png)

**Terminal:**
![NIRI](./Preview/Kitty.png)

**Firefox:**
![NIRI](./Preview/Firefox.png)

**App Launcher:**
![NIRI](./Preview/Menus.png)

To see more, go to the Preview folder

## ➜ Installation

My recommendation is to install everything from scratch and start without a desktop environment; however, you can use the Niri dotfiles that come pre-installed with your distro (in my case, CachyOS comes pre-configured, but I did a fresh install). Now, if you use that preset, it will likely come with Waybar or another alternative other than the one we’re going to use here, so you’ll simply need to change which you want to use in your Niri settings.

What we’ll be using is Dank Material Shell, a full-featured desktop environment that uses Quickshell. It has a modern interface, allowing you to configure a wide range of settings, apply themes, and synchronise colors. It also includes all the standard desktop features such as notifications, the control centre, and the lock screen... To ensure you install everything correctly, I recommend using the official DMS guide, as if I were to write it here myself, I might leave things out, include something incorrect, and ultimately an official guide is always much better.

**Guide:** https://danklinux.com/

I found this video helpful too, so I'm sharing the link in case anyone else finds it useful: 

**Video:** https://www.youtube.com/watch?v=1wHBUihASWU

**Note:** I know that even though the title says ‘installation’, it doesn't actually mention installing the components, but I should point out that it's very easy to follow the official guide or, if you prefer, the video. Have a look and you’ll see that it really is simple to follow the step-by-step instructions. And finally, the best thing, at least for me, was to read the whole wiki and then watch the video alongside it.

---

Right then, once you’ve installed DMS and checked that everything is working, we can move on to customisation

## ➜ Customization

Right, I think personalisation is a personal and unique thing; everyone has their own style, and obviously, many of us may share the same one. But that doesn’t mean you can’t ‘copy’, or rather, take ideas from other users. Personally, I spend hours browsing Reddit for ideas. That’s why I want to share mine too, to help others, like me, who want to personalise their desktop.

### › Themes

Let’s start with the basics: themes. DMS comes with a graphical settings interface that allows you to download themes from its repository. 

1. Press the `Super + Space` keys to open the app launcher
2. Open the Settings app
3. Go to the Theme and colors section
4. In the Explore section, look for the themes you like best (I use Petrichor)

#### ★ My Theme Configuration

- **Theme:** Petrichor
- **Accent Color:** Green 🐸
- **Automatic Color Mode:** Off
- **Color Mode**: Light Mode On

#### ★ My Widgets Styles Configuration

- **Widget Style:** Base
- **Control Center Tile Color:** Primary
- **Button Color:** Primary
- **Popups Transparency**: 100%
- **Corner Radius:** 12 px

#### ★ Niri design cancellations

- **Close Loopholes:** On
- **Window Spacing:** 8 px
- **Clear Corner Radius:** Off
- **Override Border Size**: On
- **Edge thickness:** 3 px

*(Options not listed are left at default)*

---

### › Cursor Theme

Another key feature is the cursor. Personally, I think the default one is a bit ugly, so I swapped it for the Material Cursor, which looks really nice, and the hand when you hover over clickable items is really cool. Still, just use whichever one you like best.

Installing them is very simple:

1. Create a folder called `icons` in `/.local/share/`
2. Extract the downloaded files inside
3. In the same themes window, look for the cursor and replace it with your own. You can change its size and make it disappear when you type

- **Material Cursor:** https://www.opendesktop.org/p/1346778
- **Website for Cursors:** https://www.opendesktop.org/browse?cat=107&ord=latest

---

### › Custom Matugen Templates

The Custom Matugen Templates section is designed to apply themes to specific applications; in my case, I’ve left it at the default settings, except for Kitty, which is my terminal, and where I use Kitten themes.

---

### › Icon Theme

For the icons, I recommend Papirus and Papirus Gruvbox folders, but you can use whichever ones you prefer. Save the files to the folder you created earlier for the cursors. To change the theme, simply look at the bottom of the same window where you’ll find the icons section.

- **Papirus:** https://github.com/PapirusDevelopmentTeam/papirus-icon-theme
- **Papirus Folders:** https://github.com/xelser/gruvbox-papirus-folders
- **Website for Icons:** https://www.opendesktop.org/browse?cat=132&ord=latest

---

### › Fonts

Let’s move on to the fonts; I generally use Comic Neue, and then JetBrains for Kitty. To install new fonts, you need to create a folder, named `fonts` in the directory `/.local/share/`.


- **Comic Neue:** https://fonts.google.com/specimen/Comic+Neue?preview.script=Latn
- **JetBrains:** https://fonts.google.com/specimen/JetBrains+Mono

---

### › Dank Bar

Now for another key feature: the Dank Bar. Personally, I only have it visible in empty workspaces or when I have floating apps open, and when I hover the cursor over it. That way, I have the whole screen to myself for my main app, with no distractions or anything like that. 

It might sound funny, but to check the time I’ve got a €2 clock from IKEA that fits onto the stand of my monitor; it looks pretty cool, and that way I can check the time whenever I want, haha. Here’s the link so you can see what it looks like and how it fits onto the monitor stand, haha.

**IKEA Clock:** https://www.ikea.com/es/es/p/kupong-despertador-negro-90621811/

#### Settings

Right, although I don’t see the taskbar most of the time, it’s useful to have a few things, like the workspaces, the clock and weather, and the menu for Wi-Fi, sound, etc... Not to mention the colour palette, which works really well for customising and picking colours.

So here are my settings:

#### Visibility:

  - **Hide automatically:** On
  - **Hide options when windows are open:** On
  - **Show/Hide manually:** On
  - **Click Through:** Off
  - **Show overview:** Off

#### Space:

  - **Gap between edges:** 0%

#### Font size:

- **Font size:** 150%

#### Bar transparency:

- **Bar transparency:** 90%

#### Corners and backgrounds

  - **Square corners:** On
  - **No Background:** On
  - **Maximize Widget Icons:** On
  - **Maximize Widget Text:** Off
  - **Remove Widget Padding:** Off
  - **Gothic corners:** Off

#### Border

  - **Color:** Primary
  - **Opacity:** 100%
  - **Thickness:** 3 px

*(Options not listed are left at default)*

#### Widgets

The widgets are arranged in order.

1. **Left section**
- **Spacer:** 5
- **Workspaces**
---
2. **Central Section**
- **Clock**
- **Separator**
- **Spacer:** 15
- **Apps Launcher**
- **Spacer:** 15
- **Separator**
- **Weather**
---
1. **Right section**
- **Control Centre** 
- **Separator**
- **Colour Picker**
- **Separator**

---

### App Launcher

The app launcher is pretty cool; to open it, press Super + Space. Another way is from the bar if you have the widget. I’ve got it, but just for the look of it (I know I don’t always have the bar visible, but the frog adds a nice touch). So, let’s get on with my settings:

I can’t say much about the settings here; you can change the size, add a border, etc. But I do recommend the following plugins, which you can install from the ‘Add-ons’ section in the settings.

#### Plugins

- **Calculator:** Allows you to perform mathematical operations in the launcher
- **Dank Launcher Keys:** This shows you the DMS keybinds

---

### Wallpaper Carousel

Esto es otro plugin que permite cambiar de fondos de manera dinamica como un carrusel, como bien indica el nombre, y es bastante bonito.

---

## Additional Customization

- **Steam:** [Steam Guide](./Steam/Steam.md)
- **Kitty:** [Kitty Guide](./Kitty/Kitty.md)
- **Fastfetch:** [Fastfetch](./Fastfetch)
- **Wallpapers:** [Wallpapers](./Wallpapers/Wallpapers.md)

---

## Special thanks and Links

I’ve decided to add this at the end to acknowledge everything that has helped me use Niri and create this Rice:

- **Atareo:** https://www.youtube.com/watch?v=2DRfehYH2U8&t=4s and https://www.youtube.com/watch?v=UWhn_LPWwn4&t=764s
- **TheBlackDon:** https://www.youtube.com/watch?v=1wHBUihASWU&t=1s
- **Reddit forums:**
1. https://www.reddit.com/r/LinuxPorn/
2. https://www.reddit.com/r/unixporn/
3. https://www.reddit.com/r/niri/

And of course, here are the links to the resources I use:

- **CachyOS:** https://cachyos.org/
- **Niri:** https://niri-wm.github.io/niri/
- **Dank Linux:** https://danklinux.com
- **Papirus:** https://github.com/PapirusDevelopmentTeam/papirus-icon-theme
- **Papirus Folders:** https://github.com/xelser/gruvbox-papirus-folders
- **Material Cursor:** https://www.opendesktop.org/p/1346778

---

## Conclusion & Feedback

So far, I’ve loved using Linux. I started with **GNOME** 20 days ago and am now trying out **Niri**. I am really enjoying it so far; I’ve only been using it for about two days, but it’s been pretty good. It feels smooth, and it’s great for working as it lets you have lots of windows open and switch between them really easily. To be honest, I don’t know why I didn’t try Niri sooner. Another thing is that with DMS, a lot of things are much easier to set up and so on.

In Gaming; in my case, I get slightly better FPS than on Windows (Maybe +5%), and what I like and find most surprising are the temperatures, as they’ve dropped quite a bit compared to Windows. For example, with RDR2 and the graphics set to high, the temperatures are around 55°C (CPU) and 68°C (GPU), which is very good. (On Windows, we’re talking about 65 and 76 respectively). Here are the PC specs as well:

- Intel I7 12700KF
- Nvidia RTX 4060 8gb
- 32 gb RAM DDR4
- 2 tb ssd

And I use a 1920x1080, 165Hz monitor

So I’ll probably stick with Linux for a loooong time. There’s no reason to go back to Windows. I can play all the games I want, and better still, I have everything I use on a daily basis at my fingertips without any unnecessary tracking by… Microsoft, for example. And honestly, everything runs much more smoothly, faster, and so on…

Another thing is the community, which is always ready to lend a hand, and that makes you want to keep learning about this world. So a big thank you to everyone who helps out the Linux Noobs, haha.

---

That's all for now, I hope you like my Rice in Niri.

If there's anything odd, something that won't load, or any errors, please leave a comment or something so I can sort it out.

Happy ricing! :)

![Linux](./Preview/Linux.gif)
