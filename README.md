# Fix the Nix

A collection of troubleshooting steps for [NixOS](https://nixos.org/) and potentially other Linux distributions.

## Topics to Cover

- Alternate consoles (Ctrl + Alt + F1-6)
- SysReq (with Dvorak equivalents)
- Managing and restarting services with `systemctl`
- Killing processes
  - Via the CLI
  - Graphically
- Finding which program has a file open with `lsof`
- Troubleshooting keyboard events and input

### Network connectivity issues

- Important `nmcli` commands to know
- Ensuring the correct WiFi network is used
- Setting custom DNS servers
- Testing DNS
- Captive portals
- Overriding search domains for specific networks

### Nix specific issues

- Finding out who/what installed a given package/piece of software
- Finding prerequisites for packages
- Finding the real path of a piece of software
- Reclaiming space when the boot partition is full (too many generations)
- Setting bootloader font size
- Setting UI font size
