# DesktopWidgets

Desktop widgets for Windows and Linux. This repository only holds releases;
the source lives in [desktopwidgets-core](https://github.com/cdro/desktopwidgets-core).

Every widget can be installed on its own. The **Library** app lists all
widgets and installs or updates them for you, but you don't need it.

Latest release: **v0.1.0-rc.3**. Machine-readable index: [catalog.json](catalog.json)

| Widget | Version | Description | Downloads |
| --- | --- | --- | --- |
| **Clock** | 1.0.0 | Analog or digital clock with date, optional seconds and time zone. | [debian-12 deb](https://github.com/cdro/DesktopWidgets/releases/download/v0.1.0-rc.3/dw-clock_1.0.0_debian-12-amd64.deb) · [debian-13 deb](https://github.com/cdro/DesktopWidgets/releases/download/v0.1.0-rc.3/dw-clock_1.0.0_debian-13-amd64.deb) · [fedora-43 rpm](https://github.com/cdro/DesktopWidgets/releases/download/v0.1.0-rc.3/dw-clock_1.0.0_fedora-43-amd64.rpm) · [fedora-44 rpm](https://github.com/cdro/DesktopWidgets/releases/download/v0.1.0-rc.3/dw-clock_1.0.0_fedora-44-amd64.rpm) · [flatpak](https://github.com/cdro/DesktopWidgets/releases/download/v0.1.0-rc.3/dw-clock_1.0.0_flatpak-amd64.flatpak) · [tar.gz](https://github.com/cdro/DesktopWidgets/releases/download/v0.1.0-rc.3/dw-clock_1.0.0_linux-amd64.tar.gz) · [ubuntu-24.04 deb](https://github.com/cdro/DesktopWidgets/releases/download/v0.1.0-rc.3/dw-clock_1.0.0_ubuntu-24.04-amd64.deb) · [Windows msi](https://github.com/cdro/DesktopWidgets/releases/download/v0.1.0-rc.3/dw-clock_1.0.0_windows-amd64.msi) · [Windows zip](https://github.com/cdro/DesktopWidgets/releases/download/v0.1.0-rc.3/dw-clock_1.0.0_windows-amd64.zip) |
| **Widget Library** | 1.0.0 | Browse, install and update DesktopWidgets. Optional; every widget also installs on its own. | [debian-12 deb](https://github.com/cdro/DesktopWidgets/releases/download/v0.1.0-rc.3/dw-library_1.0.0_debian-12-amd64.deb) · [debian-13 deb](https://github.com/cdro/DesktopWidgets/releases/download/v0.1.0-rc.3/dw-library_1.0.0_debian-13-amd64.deb) · [fedora-43 rpm](https://github.com/cdro/DesktopWidgets/releases/download/v0.1.0-rc.3/dw-library_1.0.0_fedora-43-amd64.rpm) · [fedora-44 rpm](https://github.com/cdro/DesktopWidgets/releases/download/v0.1.0-rc.3/dw-library_1.0.0_fedora-44-amd64.rpm) · [flatpak](https://github.com/cdro/DesktopWidgets/releases/download/v0.1.0-rc.3/dw-library_1.0.0_flatpak-amd64.flatpak) · [tar.gz](https://github.com/cdro/DesktopWidgets/releases/download/v0.1.0-rc.3/dw-library_1.0.0_linux-amd64.tar.gz) · [ubuntu-24.04 deb](https://github.com/cdro/DesktopWidgets/releases/download/v0.1.0-rc.3/dw-library_1.0.0_ubuntu-24.04-amd64.deb) · [Windows msi](https://github.com/cdro/DesktopWidgets/releases/download/v0.1.0-rc.3/dw-library_1.0.0_windows-amd64.msi) · [Windows zip](https://github.com/cdro/DesktopWidgets/releases/download/v0.1.0-rc.3/dw-library_1.0.0_windows-amd64.zip) |
| **Stock Ticker** | 1.0.0 | Live quotes with intraday sparkline for a list of symbols. | [debian-12 deb](https://github.com/cdro/DesktopWidgets/releases/download/v0.1.0-rc.3/dw-stock-ticker_1.0.0_debian-12-amd64.deb) · [debian-13 deb](https://github.com/cdro/DesktopWidgets/releases/download/v0.1.0-rc.3/dw-stock-ticker_1.0.0_debian-13-amd64.deb) · [fedora-43 rpm](https://github.com/cdro/DesktopWidgets/releases/download/v0.1.0-rc.3/dw-stock-ticker_1.0.0_fedora-43-amd64.rpm) · [fedora-44 rpm](https://github.com/cdro/DesktopWidgets/releases/download/v0.1.0-rc.3/dw-stock-ticker_1.0.0_fedora-44-amd64.rpm) · [flatpak](https://github.com/cdro/DesktopWidgets/releases/download/v0.1.0-rc.3/dw-stock-ticker_1.0.0_flatpak-amd64.flatpak) · [tar.gz](https://github.com/cdro/DesktopWidgets/releases/download/v0.1.0-rc.3/dw-stock-ticker_1.0.0_linux-amd64.tar.gz) · [ubuntu-24.04 deb](https://github.com/cdro/DesktopWidgets/releases/download/v0.1.0-rc.3/dw-stock-ticker_1.0.0_ubuntu-24.04-amd64.deb) · [Windows msi](https://github.com/cdro/DesktopWidgets/releases/download/v0.1.0-rc.3/dw-stock-ticker_1.0.0_windows-amd64.msi) · [Windows zip](https://github.com/cdro/DesktopWidgets/releases/download/v0.1.0-rc.3/dw-stock-ticker_1.0.0_windows-amd64.zip) |

## Which file do I need?

- **Windows:** `.msi` installs for your user, no admin rights needed. `.zip` is portable.
  Widgets need the Microsoft Edge WebView2 runtime, which ships with Windows 10 and 11.
- **Debian / Ubuntu:** `.deb` for your distribution: `sudo apt install ./file.deb`
- **Fedora:** `.rpm`: `sudo dnf install ./file.rpm`
- **Any distribution:** `.flatpak`: `flatpak install --user ./file.flatpak`, or the
  `.tar.gz` (extract, then run `./install.sh`; it needs GTK 3 and WebKitGTK 4.1).

Linux widgets currently target X11. On Wayland they run through XWayland.

Verify downloads with the `SHA256SUMS` file attached to each release.
