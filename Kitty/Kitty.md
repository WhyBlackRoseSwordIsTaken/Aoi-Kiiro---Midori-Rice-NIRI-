# ➤ Kitty Terminal Customization 🐱

To give your terminal a nice touch and make sure it’s not just a black screen for typing commands, here’s a guide to make it look really cool:

## ➜ KITTY

Kitty is the terminal I use, as it lets me add images to my Fastfetch configuration and give it an amazing look.

### › Kitty Installation

| Package | Ubuntu/Debian | Arch/Manjaro | Fedora |
|---------|---------------|--------------|--------|
| **Kitty** | `sudo apt install kitty` | `sudo pacman -S kitty` | `sudo dnf install kitty` |

---

### › Kitty Themes Installation

**Themes:** https://github.com/dexpota/kitty-themes

#### ★ Steps:

1. Clone or download the repository:
```bash
git clone --depth 1 https://github.com/dexpota/kitty-themes.git ~/.config/kitty/kitty-themes
```
This will download a collection of themes to your configuration folder

2. Choose your theme. Run the following command:
```bash
kitten themes
```
I recommend using a theme that fits in with your overall theme to ensure consistency throughout the Rice.

3. Apply the changes:
- Navigate through the list using the arrow keys.
- Once you find your theme, press `Enter` to select it.
- Then press `M` to modify the configuration.

---

## ➜ OH MY ZSH

This allows you to add some plugins for autocomplete, command highlighting and so on.

### › OH-MY-ZSH Installation

**Oh My Zsh Wiki:** https://github.com/ohmyzsh/ohmyzsh

#### ★ Installation:

- Clone or download the repository:
```bash
wget https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh
sh install.sh
```

#### ★ Themes:

1.  Find your favorite theme (I use robbyrussell). You can browse the huge list of available themes with previews on the Official Oh My Zsh Wiki

2.  Edit your configuration file: Open the `.zshrc` file using `nano`:
```bash
nano ~/.zshrc
```

3. Apply the theme. Search for the line that starts with `ZSH_THEME`. Change the name inside the quotes to your chosen theme:
```bash
ZSH_THEME="robbyrussell"
```

4. Save and Exit. Press `Ctrl + O` then `Enter` to save
- Press `Ctrl + X` to exit the editor.

5. Restart your terminal

#### ★ Plugins:

This tool also lets you add plugins, and there are some really useful ones. The ones I use are:

- **zsh-autosuggestions:** This plugin lets you enter commands more quickly, as it suggests them to you and saves the ones you use.
- **zsh-syntax-highlighting:** This one highlights the commands in different colours.
- **fzf:** This allows you to search the history of commands you have used with `ctrl + R`

To activate them, Edit your configuration file: Open the `.zshrc` file and add them where it says `plugins`.

- **Plugins:** https://github.com/ohmyzsh/ohmyzsh/wiki/Plugins

---

## ➜ FASTFETCH

Fastfetch lets you customise your terminal interface and add information about your PC.

### › Fastfetch Installation

**Fastfetch Wiki:** https://github.com/fastfetch-cli/fastfetch

| Package | Ubuntu/Debian | Arch/Manjaro | Fedora |
|---------|---------------|--------------|--------|
| **Fastfetch** | `sudo apt install fastfetch` | `sudo pacman -S fastfetch` | `sudo dnf install fastfetch` |

To get that cool system overview every time you open your terminal, you need to add it to your configuration.

1. Open the `.zshrc` file using `nano`:
```bash
nano ~/.zshrc
```

2. Add the command. Scroll to the very bottom of the file and add:
```bash
# Show system info
fastfetch
```

#### ★ Custom Fastfetch

I have shared my personal configuration to achieve a clean, boxed look with specific categories for System, Terminal, and Hardware.

**How to apply it:**

1. Create the config file:
```bash
mkdir -p ~/.config/fastfetch
nano ~/.config/fastfetch/config.jsonc
```

2. Paste the content: Copy the code from my `config.jsonc` and paste it into your file.

3. Configure your image:
Look for the logo section at the top and replace "Your File Path" with the absolute path to your desired image or logo.
```bash
{
    "$schema": "https://github.com/fastfetch-cli/fastfetch/raw/master/doc/json_schema.json",
    "logo": {
    "source": "Your File Path",
    "width": 35,
    "height": 18,
    "padding": {
        "top": 1,   
        "left": 0,  
        "right": 2  
  }   
```
You should also adjust the width and height to match your specific image's proportions so it doesn't look distorted
