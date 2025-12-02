<div align="center">
  <h2>Blazingly fast TUI for managing AirPods on Linux</h2>
</div>

---

## Features

---

- Connect/disconnect AirPods
- Set AirPods as default audio device
- Show battery status (live levels for L / R / Case)
- Show pairing status
- Scan and connect to AirPods
- ANC / Transparency / Adaptive modes
- In-ear detection
- RSSI, firmware, and model info

## Prerequisites

---

- A Linux-based OS
- [bluez](http://www.bluez.org/) running
- [nerdfonts](https://www.nerdfonts.com/) (optional, for icons)

## Installation

---

### From crates.io

```bash
cargo install airpodsctl
```

### Arch Linux (AUR)

```bash
yay -S airpodsctl
```

### Build from source

```bash
git clone https://github.com/yourusername/airpodsctl.git
cd airpodsctl
cargo build --release
```

## Usage

---

### AirPods Management

- `c`: Connect/Disconnect AirPods.
- `d`: Set AirPods as default audio device.
- `b`: Show battery status.
- `p`: Show pairing status.
- `a`: Toggle ANC / Transparency / Adaptive modes.
- `i`: Toggle in-ear detection.
- `r`: Show RSSI, firmware, and model info.

### Navigation

- `Tab` or `l`: Scroll down between different sections.
- `Shift+Tab` or `h`: Scroll up between different sections.
- `j` or `Down`: Scroll down.
- `k` or `Up`: Scroll up.
- `Ctrl+C` or `q`: Quit the app.

## Configuration

---

Configuration coming soon.

## Notes

---

Uses reverse engineering insights from librepods to make AirPods management possible.

## License

---

GPLv3
