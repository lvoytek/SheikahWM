# SheikahWM
A Linux window manager that resembles a Sheikah slate


## Building
### Install Dependencies

* rustup
* glib-2.0
* cairo
* pango
* xcb-randr

Ubuntu / Debian:

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
sudo apt install libglib2.0-dev libcairo2-dev libpango1.0-dev libxcb-randr0-dev
```

### Build with Cargo

```bash
cargo build --release
```
