<h1 align=center>
  ArchLinux-WSL<br />
</h1>

Arch Linux for the Windows Subsystem for Linux (WSL) based on the official root filesystem without any modifications.

## Quick Start

1. Enable WSL if you haven't done already:

- ```powershell
  wsl --install --no-distribution
  ```

2. Download `ArchLinux-wsl.tar.gz` from [the latest release](https://github.com/mengshengwu/ArchLinux-WSL/releases/latest).

3. Import the tarball into WSL:

- ```powershell
  wsl --import ArchLinux $env:USERPROFILE\ArchLinux\ ArchLinux-wsl.tar.gz --version 2
  ```

4. You can now run ArchLinux:

- ```powershell
  wsl -d ArchLinux
  ```

For more WSL detailed instructions, [refer to the documentation](https://learn.microsoft.com/en-us/windows/wsl/).

For more detailed instructions on using Arch Linux, [refer to the documentation](https://wiki.archlinux.org/title/Main_page).

## License

Apache License, Version 2.0. See `LICENSE` or <http://www.apache.org/licenses/LICENSE-2.0.html> for details.