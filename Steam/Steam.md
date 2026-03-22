# ➤ Steam Themes Guide 🎮

To make Steam look great and match your theme, we’ll use **Adwaita-for-Steam** skin. This allows you to apply certain themes to your Steam client.

All resources and detailed documentation can be found at the official site

- **Adwaita for steam:** https://github.com/tkashkin/Adwaita-for-Steam

## ➜ Installation

1. Clone or download the repository:
```bash
git clone https://github.com/tkashkin/Adwaita-for-Steam
cd Adwaita-for-Steam
./install.py
```

2. List Options
```bash
./install.py -l
```

3. Install Customizations (Example)
```bash
./install.py -c vgui2 -e library/hide_whats_new
```

## ➜ Preview

![Steam](/Preview/Steam.png)

---

## ➜ Tip

One important thing to note when using Niri, which is a window manager, is that, at least for me, it launches games in a window, and this causes the game to crash. Fixing it is very simple:

1. Open settings
2. Go to System > Window Rules
3. Create window rules for your games, using the Steam Game ID, for example, and set them to open in `full-screen mode`, `maximised`, and at your `resolution`.
