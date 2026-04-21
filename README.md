<h1 align="center">✨ My Windows 11 Setup ✨</h1>

<p align="center">
  A complete guide to my Windows 11 customization — from the YASB status bar to every little tweak that makes it clean, aesthetic, and productive.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/OS-Windows%2011-0078D4?style=for-the-badge&logo=windows11&logoColor=white" />
  <img src="https://img.shields.io/badge/Theme-Catppuccin%20Mocha-CBA6F7?style=for-the-badge&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/Font-JetBrainsMono%20NF-000000?style=for-the-badge&logo=jetbrains&logoColor=white" />
</p>

---

## 🖼️ Screenshot

> _Screenshot coming soon._

---

## 📑 Table of Contents

| Category | App |
|---|---|
| 📊 Status Bar | [YASB](#-yasb) |
| 🪟 Window Manager | [GlazeWM](#-glazewm) |
| 🔍 App Launcher | [Flow Launcher](#-flow-launcher) |
| 🖥️ Taskbar | [Windhawk](#-windhawk) |
| 📝 Text Editor | [VSCode](#-vscode) |
| 💻 Terminal | [Windows Terminal + Fastfetch](#-windows-terminal--fastfetch) |
| 🌐 Browser | [Brave](#-brave) |
| 🐚 Shell Prompt | [Oh My Posh](#-oh-my-posh) |
| 🎵 Audio Visualizer | [Cava](#-cava) |
| 🎧 Music Player | [Spotify](#-spotify) |
| 📒 Note Taking | [Notesnook](#-notesnook) |
| 🎥 Screen Recording | [OBS Studio](#-obs-studio) |
| 📁 File Explorer Mod | [ExplorerBlurMica](#-explorerblurmica) |
| 🔧 Other Tools | [Extras](#-extras) |

### 🎨 Base

| Category | Choice |
|---|---|
| Colorscheme | [Catppuccin Mocha](https://catppuccin.com) |
| Font | [JetBrainsMono Nerd Font](https://github.com/ryanoasis/nerd-fonts/releases/latest/download/JetBrainsMono.zip) |

---

# ⚡ Details

## 📊 YASB

> [!NOTE]
> Some things in my config may not work if you copy-paste them directly. Make sure to add your own API key for the weather widget and update the wallpaper folder path for the wallpapers widget.

A highly configurable Windows status bar written in Python.

**⚙️ Installation:**

You can follow the steps below, or watch the [**setup video**](https://www.youtube.com/watch?v=your-video-id).

1. Install [**YASB**](https://github.com/amnweb/yasb).
2. Copy the config files from [**this repo**](https://github.com/SleepyCatHey/Ultimate-Win11-Setup/tree/main/YASB).
3. Replace the contents of your existing YASB config with the one you just copied.
4. Restart **YASB** for the changes to take effect.

---

## 🪟 GlazeWM

> [!NOTE]
> If you're using my config, Zebar won't work since I use GlazeWM with YASB instead. If you want to use Zebar, add back the two lines I removed from the default config.

GlazeWM lets you easily organize windows and adjust their layout on the fly using keyboard-driven commands.

**⚙️ Installation:**

You can follow the steps below, or watch the [**setup video**](https://youtu.be/b57zFm3nVxA).

1. Install [**GlazeWM**](https://github.com/glzr-io/glazewm).
2. Copy the config file from [**this repo**](https://github.com/SleepyCatHey/Ultimate-Win11-Setup/tree/main/GlazeWM).
3. Replace the contents of your existing GlazeWM config with the one you just copied.
4. Restart **GlazeWM** for the changes to take effect.

---

## 🦅 Windhawk

> [!NOTE]
> My taskbar config removes the Start menu and network icons. To restore them, follow [**this guide**](https://github.com/ramensoftware/windows-11-taskbar-styling-guide).

Windhawk makes it easier to customize Windows programs with community-made mods.

**⚙️ Installation:**

You can follow the steps below, or watch the [**setup video**](https://youtu.be/b57zFm3nVxA) for more detail on taskbar customization.

1. Install [**Windhawk**](https://windhawk.net/).
2. Copy the config file from [**this repo**](https://github.com/SleepyCatHey/Ultimate-Win11-Setup/tree/main/Windhawk).
3. Paste the config into the **Advanced** section of the relevant Windhawk mod.
4. Click **Save settings** for the changes to take effect.

---

## 🔍 Flow Launcher

A fast file search and app launcher for Windows.

**⚙️ Installation:**

1. Install [**Flow Launcher**](https://www.flowlauncher.com/).
2. Download the theme file from [**this repo**](https://github.com/SleepyCatHey/Ultimate-Win11-Setup/tree/main/Flow%20Launcher).
3. Open Flow Launcher's **Settings → Appearance**, then click **Open Theme Folder**.
4. Move the downloaded theme file into that folder and restart Flow Launcher.
5. Back in **Settings → Appearance**, select your Catppuccin flavor from the theme list.

> Installation steps adapted from the [**Catppuccin Flow Launcher**](https://github.com/catppuccin/flow-launcher) repo.

---

## 💻 Windows Terminal + Fastfetch

> [!NOTE]
> **For a 1:1 match with my setup**, watch the setup video — it covers everything in one go.
>
> If you only want the Fastfetch config, just paste it where your existing Fastfetch config is located.
>
> If you have an existing PowerShell profile, manually add your own paths and preferences rather than overwriting it entirely.
>
> **"Execution of scripts is disabled on this system"** — Don't panic. Open PowerShell as Administrator and run:
> ```powershell
> Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser -Force
> ```
>
> **ASCII art not showing?** Try changing `"source": "C:/Users/%USERPROFILE%/.config/fastfetch/ascii.txt"` to `"source": "%USERPROFILE%/.config/fastfetch/ascii.txt"`. ([credit](https://github.com/SleepyCatHey/Ultimate-Win11-Setup/issues/1#issue-3498937609))
>
> **Want Fastfetch in CMD too?** Check out [this issue](https://github.com/SleepyCatHey/Ultimate-Win11-Setup/issues/9#issue-3958846174). Thanks to [**Augtive85YT**](https://github.com/Augtive85YT)!

Fastfetch is a neofetch-like system information tool written in C, focused on performance and customizability.

**⚙️ Installation:**

You can follow the steps below, or watch the [**setup video**](https://youtu.be/z3NpVq-y6jU) for a full walkthrough.

1. Install [**Fastfetch**](https://github.com/fastfetch-cli/fastfetch/releases). Windows Terminal should already be installed.
2. Download configs from this repo:
   - Terminal config → [Terminal](https://github.com/SleepyCatHey/Ultimate-Win11-Setup/tree/main/Terminal)
   - PowerShell profile → [PowerShell](https://github.com/SleepyCatHey/Ultimate-Win11-Setup/tree/main/PowerShell)
   - Fastfetch config → [Fastfetch](https://github.com/SleepyCatHey/Ultimate-Win11-Setup/tree/main/Fastfetch)
3. Replace the contents of `settings.json` in your terminal and your PowerShell profile with the downloaded configs.
4. Create a hidden `.config` folder at `C:\Users\%USERPROFILE%\` and a `fastfetch` subfolder inside it. Paste the Fastfetch config and ASCII art file there.
5. Replace `%USERPROFILE%` in both the Fastfetch config and your PowerShell profile with your actual username.
6. Restart your terminal — you're done!

---

## 📝 VSCode

> [!NOTE]
> This is just my base VSCode settings. Your setup may look different since I also use a number of extensions alongside it. I'll try to keep the extensions list up to date.

Visual Studio Code is a free, open-source code editor by Microsoft for building and debugging modern web and cloud applications.

**⚙️ Installation:**

1. Install [**VSCode**](https://code.visualstudio.com/).
2. Copy the config: `VSCode/Settings/settings.json` → `%APPDATA%\Code\User\settings.json`.
3. Restart **VSCode** for the changes to take effect.

**🔧 Extensions:**

| Extension | Description |
|---|---|
| [Catppuccin for VSCode](https://marketplace.visualstudio.com/items?itemName=Catppuccin.catppuccin-vsc) | Soothing pastel theme |
| [Catppuccin Icons for VSCode](https://marketplace.visualstudio.com/items?itemName=Catppuccin.catppuccin-vsc-icons) | Matching pastel icon theme |
| [VSCode Pets](https://marketplace.visualstudio.com/items?itemName=tonybaloney.vscode-pets) | Puts a little pet in your editor 🐱 |

---

## 🌐 Brave

A privacy-focused browser based on Chromium.

**Features:**
- Built-in ad and tracker blocking
- Minimal, clean UI
- Chromium extension support
- Good performance and low memory usage

**⚙️ Installation:**

1. Install [**Brave**](https://brave.com/download/).
2. Apply the Catppuccin theme from the [Chrome Web Store](https://chrome.google.com/webstore/detail/catppuccin-chrome-theme-m/bkkmolkhemgaeaeggcmfbghljjjoofoh).

---

## 🐚 Oh My Posh

A prompt theme engine for any shell.

**⚙️ Installation:**

1. Install [**Oh My Posh**](https://ohmyposh.dev/docs/installation/windows) via winget:
   ```powershell
   winget install JanDeDobbeleer.OhMyPosh -s winget
   ```
2. Copy the theme config from [**this repo**](https://github.com/SleepyCatHey/Ultimate-Win11-Setup/tree/main/OhMyPosh) to your preferred location.
3. Add the following to your PowerShell profile, updating the path to match where you saved the theme:
   ```powershell
   oh-my-posh init pwsh --config "C:\path\to\your\theme.omp.json" | Invoke-Expression
   ```
4. Restart your terminal.

---

## 🎵 Audio Visualizer — Cava

A cross-platform terminal-based audio visualizer.

**⚙️ Installation:**

1. Install [**Cava**](https://github.com/nicowillis/cava-windows) (Windows port).
2. Copy the config from [**this repo**](https://github.com/SleepyCatHey/Ultimate-Win11-Setup/tree/main/Cava) to `%USERPROFILE%\.config\cava\config`.
3. Run `cava` in your terminal.

---

## 🎧 Spotify

Spotify with [**Spicetify**](https://spicetify.app/) for theming support.

**⚙️ Installation:**

1. Install [**Spotify**](https://www.spotify.com/download/windows/) and [**Spicetify**](https://spicetify.app/docs/getting-started).
2. Install the Catppuccin theme:
   ```powershell
   spicetify config current_theme catppuccin
   spicetify apply
   ```
   Full theme instructions: [catppuccin/spicetify](https://github.com/catppuccin/spicetify)

---

## 📒 Notesnook

A free, open-source, end-to-end encrypted note-taking app.

**⚙️ Installation:**

1. Install [**Notesnook**](https://notesnook.com/).
2. No custom config needed — works great out of the box.

---

## 🎥 OBS Studio

Free and open-source software for video recording and live streaming.

**⚙️ Installation:**

1. Install [**OBS Studio**](https://obsproject.com/).
2. No custom config in this repo — using mostly default settings with a few scene tweaks.

---

## 📁 ExplorerBlurMica

> [!WARNING]
> Several users have reported bugs and crashes with this tool. I now recommend using the **Windhawk method** instead (video coming soon).

Adds Blur, Acrylic, or Mica background effects to File Explorer on Windows 10 and 11.

**⚙️ Installation:**

You can follow the steps below, or watch the [**setup video**](https://youtu.be/gpGeCZXXsbs).

1. Install [**ExplorerBlurMica**](https://github.com/Maplespe/ExplorerBlurMica/releases).
2. Copy the config from [**this repo**](https://github.com/SleepyCatHey/Ultimate-Win11-Setup/tree/main/File%20Explorer).
3. Follow the official [**installation instructions**](https://github.com/Maplespe/ExplorerBlurMica?tab=readme-ov-file#install) for the rest.

---

## 🔧 Extras

Other small tools and tweaks I use to round everything out.

| Tool | Purpose |
|---|---|
| [Wallpaper Engine](https://www.wallpaperengine.io/) | Animated and interactive wallpapers |
| [AutoHotKey](https://www.autohotkey.com/) | Custom keyboard shortcuts and automation scripts |
| [RoundedTB](https://github.com/torchgm/RoundedTB) | Adds margins and rounded corners to the taskbar |

---

<p align="center">
  <sub>Made with 💜 on Windows 11 · Themed with <a href="https://catppuccin.com">Catppuccin Mocha</a></sub>
</p>
