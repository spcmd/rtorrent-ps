My modified & patched version of the [rtorrent-pyro-git](https://aur.archlinux.org/packages/rtorrent-pyro-git/) package from the AUR.

I included the PKGBUILD for Arch Linux, however this is **not** intended to be a git package, currently works with rtorrent *20160310* version (commit: 9abcea84c7f7594ef9cc99f151467cf8b718a9c0). Maybe works (will be working) with newer commits. By default the package name is set to **rtorrent-ps-spcmd** in the PKGBUILD to avoid confusion with other packages.

#### Changed


- **ui_pyroscope.cc**: changed some icons (line 470, and a few others). The original file (ui_pyroscope.css.orig) is included, you can diff them.

#### Added

- **vi_keybindings-spcmd.patch**: ported the *rtorrent-0.9.6_vi_keybinding_tjwoosta.patch* to work with this version.

#### Thanks
Thanks to pyroscope for the [rtorrent-ps patches](https://github.com/pyroscope/rtorrent-ps).
