# waybar-macos-sequoia

A sleek Waybar configuration inspired by macOS 15 Sequoia design language

![macOS Sequoia Waybar Preview](/preview/preview.png)

## 🚀 Features

- macOS 15 Sequoia-inspired design
- Clean, minimal interface with subtle animations
- Dark/Light mode support (matches system theme)
- Custom modules:
  - macOS-style application menu
  - Workspace switcher with macOS Mission Control aesthetic
  - System status icons (WiFi, Bluetooth, Volume)
  - Battery indicator with Sonoma-style percentage
  - Dynamic date/time panel
  - Custom power menu
- Optimized for 2K/4K displays
- Built-in support for:
  - WLR/Workspaces (Hyprland/Sway)
  - PulseAudio/PipeWire
  - NetworkManager
  - BlueZ (Bluetooth)
  - Brightness control

## 📥 Installation

1. Clone the repository:

```bash
git clone https://github.com/kamlendras/waybar-macos-sequoia.git
```

2. Backup existing config (if any):

```bash
mv ~/.config/waybar ~/.config/waybar.bak
```

3. Copy configuration files:

```bash
cp -r waybar-macos-sequoia ~/.config/waybar
```

4. Install required dependencies:

- [Waybar](https://github.com/Alexays/Waybar) (v0.9.17+ recommended)

## ⚙️ Configuration

### File Structure

~/waybar-macos-sequoia

```text
~/
├── config
├── style.css
├── wallpapers
│   ├── wallpaper-light.png
│   └── wallpaper-dark.png
├── preview
│   ├── preview.png
|   ├──top_preview.png
│   └── bottom_preview.png
├── README

```

### Customization

1. **Style**: Modify `style.css` to adjust:

   - Color scheme (matches macOS Sequoia palette)
   - Bar height (default 41px)
   - Spacing and padding

2. **Modules**: Edit `config.json` to:
   - Rearrange module positions
   - Adjust animation durations
   - Configure workspace numbers

## 🌈 Theme Colors

| Role               | Dark Mode | Light Mode |
| ------------------ | --------- | ---------- |
| Primary Background | #1C1C1E   | #F5F5F7    |
| Secondary Elements | #2C2C2E   | #E5E5EA    |
| Accent Color       | #0A84FF   | #007AFF    |
| Text Primary       | #FFFFFF   | #1D1D1F    |
| Text Secondary     | #86868B   | #636366    |

## 📦 Dependencies

- Required:
  - `waybar` (>= 0.9.17)
  - `rofi`/`wofi` (for menus)
- Recommended:
  - `pulseaudio` (audio control)
  - `brightnessctl` (brightness control)
  - `networkmanager` (network status)
  - `bluez-utils` (bluetooth management)

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first.

## 📄 License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

---

**Disclaimer**: This project is not affiliated with Apple Inc. macOS is a registered trademark of Apple Inc.
