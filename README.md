#RambleOn Navigator

## Installing

### macOS

Download the latest [RambleOn Navigator release](https://github.com/dhfbk/rambleon-navigator/releases).

RambleOn will automatically update when a new release is available.

### Windows

Download the latest [RambleOn installer](https://github.com/dhfbk/rambleon-navigator/releases). RambleOn.Navigator.Setup.x.x.x.exe for 64-bit systems.

RambleOn will automatically update when a new release is available.

You can also download `RambleOn Navigator-x.x.x-win.zip` (64-bit) from the [releases page](https://github.com/dhfbk/rambleon-navigator/releases).
The `.zip` version will not automatically update.


### Debian Linux (Ubuntu)

RambleOn Navigator is only available for 64-bit Linux systems.

1. Download `RambleOn_Navigator_x.x.x-linux-amd64.deb` from the [RambleOn Navigator releases page](https://github.com/dhfbk/rambleon-navigator/releases).
2. Run `sudo dpkg --install RambleOn_Navigator_x.x.x-linux-amd64.deb` on the downloaded package.
3. Launch RambleOn Navigator using the installed `rambleon_navigator` command.

The Linux version does not currently automatically update so you will need to
repeat these steps to upgrade to future releases.

### Red Hat Linux (Fedora, CentOS, Red Hat)

RambleOn Navigator is only available for 64-bit Linux systems.

1. Download `RambleOn_Navigator-x.x.x-linux.rpm` from the [RambleOn Navigator releases Navigator page](https://github.com/dhfbk/rambleon-navigator/releases).
2. Run `sudo yum localinstall RambleOn_Navigator-x.x.x-linux.rpm` on the downloaded package.
3. Launch RambleOn Navigator using the installed `rambleon_navigator` command.

The Linux version does not currently automatically update so you will need to
repeat these steps to upgrade to future releases.

If you have problem with fedora try this:   
```
sudo dnf --assumeyes install libXScrnSaver
sudo dnf --assumeyes install libX11-devel
```

last version: 1.0.61
