# VPS VPN Manager

This repository contains a simple WireGuard-based VPN manager that runs from a menu on the VPS.

## Usage

1. Copy the script to your VPS:
   ```bash
   chmod +x menu
   cp menu /usr/local/bin/menu
   ```
2. Run it:
   ```bash
   menu
   ```
3. Use the interactive menu to:
   - install and set up WireGuard
   - start, stop, and check VPN status
   - add and remove client profiles
   - list connected clients
   - show QR codes for clients
   - back up config files

## Notes

- This is a simple VPN management system for Debian/Ubuntu VPS servers.
- It uses WireGuard, which is lightweight and fast.
- Client config files are stored in `/etc/wireguard/clients`.
- The server config is stored in `/etc/wireguard/wg0.conf`.

## Example

```bash
sudo cp menu /usr/local/bin/menu
sudo chmod +x /usr/local/bin/menu
menu
```
