# hoppscotch-app

This is a simple desktop version of [hoppscotch](https://github.com/hoppscotch/hoppscotch) which build with [Tauri](https://tauri.studio/).

It support windows (x86, x64, arm64) and linux (amd64, i386, arm64, armhf) and macos (x64, aarch64, universal). One single portable executable file or bundles/installers (msi/nsis for windows, deb/AppImage for linux, app.zip/dmg for macos) are provided.

[![build](https://github.com/xzeldon/hoppscotch-app/actions/workflows/build.yml/badge.svg)](https://github.com/xzeldon/hoppscotch-app/actions/workflows/build.yml)

## Downloads

Current version: 23.8.4.

<table class="is-fullwidth">
</thead>
<tbody>
</tbody>
  <tr>
    <td align="center">
      <img src="./.github/images/windows.png" width="24"><br />
      Windows
    </td>
    <td>
      <span>64-bit</span>
      <a href="https://github.com/xzeldon/hoppscotch-app/releases/latest/download/hoppscotch-app-windows-23.8.4_x64.exe">
        📦 Executable
      </a> |
      <a href="https://github.com/xzeldon/hoppscotch-app/releases/latest/download/hoppscotch-app-windows-23.8.4_x64.msi">
        💿 MSI Installer
      </a> |
      <a href="https://github.com/xzeldon/hoppscotch-app/releases/latest/download/hoppscotch-app-windows-23.8.4_x64-setup.exe">
        💿 NSIS Installer
      </a><br />
      <span>32-bit</span>
      <a href="https://github.com/xzeldon/hoppscotch-app/releases/latest/download/hoppscotch-app-windows-23.8.4_x86.exe">
        📦 Executable
      </a> |
      <a href="https://github.com/xzeldon/hoppscotch-app/releases/latest/download/hoppscotch-app-windows-23.8.4_x86.msi">
        💿 MSI Installer
      </a> |
      <a href="https://github.com/xzeldon/hoppscotch-app/releases/latest/download/hoppscotch-app-windows-23.8.4_x86-setup.exe">
        💿 NSIS Installer
      </a><br />
      <span>arm64</span>
      <a href="https://github.com/xzeldon/hoppscotch-app/releases/latest/download/hoppscotch-app-windows-23.8.4_arm64.exe">
        📦 Executable
      </a> |
      <a href="https://github.com/xzeldon/hoppscotch-app/releases/latest/download/hoppscotch-app-windows-23.8.4_arm64-setup.exe">
        💿 NSIS Installer
      </a><br />
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="./.github/images/macos.png" width="24"><br />
      macOS
    </td>
    <td>
      <span>Universal</span>
      <a href="https://github.com/xzeldon/hoppscotch-app/releases/latest/download/hoppscotch-app-macos-23.8.4_universal">
        📦 Executable
      </a> |
      <a href="https://github.com/xzeldon/hoppscotch-app/releases/latest/download/hoppscotch-app-macos-23.8.4_universal.dmg">
        💿 DMG bundle
      </a> |
      <a href="https://github.com/xzeldon/hoppscotch-app/releases/latest/download/hoppscotch-app-macos-23.8.4_universal.app.zip">
        💿 APP bundle
      </a><br />
  </tr>
  <tr>
    <td align="center">
      <img src="./.github/images/linux.png" width="24"><br />
      Linux
    </td>
    <td>
      <span>64-bit</span>
      <a href="https://github.com/xzeldon/hoppscotch-app/releases/latest/download/hoppscotch-app-linux-23.8.4_amd64">
        📦 Executable
      </a> |
      <a href="https://github.com/xzeldon/hoppscotch-app/releases/latest/download/hoppscotch-app-linux-23.8.4_amd64.AppImage">
        💿 AppImage bundle
      </a> |
      <a href="https://github.com/xzeldon/hoppscotch-app/releases/latest/download/hoppscotch-app-linux-23.8.4_amd64.deb">
        💿 DEB bundle
      </a><br />
      <span>
        ❓ Don't know which architecture of OS you installed? Execute <code>uname -i</code> or <code>dpkg --print-architecture</code> or <a href="https://www.man7.org/linux/man-pages/man1/arch.1.html">arch</a> command.
      </span>
    </td>
  </tr>
</table>

<hr />

![Screenshot](./.github/images/preview.png)

## Does it work?

Yes! Quite well, actually - on macOS, Windows, and Linux.

## Credits

99% of the work was done over at [hoppscotch](https://github.com/hoppscotch/hoppscotch).

## License

MIT License

Copyright (c) 2023 liudonghua
