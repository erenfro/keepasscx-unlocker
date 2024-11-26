# KeePassXC-Unlocker

KeePassXC Unlocker is a took designed to utilize your system's keyring to
unlock your KeePassXC database(s) on login and session unlocking.

Currently this only works on Linux, but the aim is to get this working
on macOS as well, and maybe Windows, if someone's willing to help write the
Windows portions and test, but I don't run Windows.

## Command Help:

```
Usage: keepassxc-unlocker <command> [arguments]
Commands:
  add <db>      - Add an entry to the keyring
  remove <db>   - Remove an entry from the keyring
  service <opt> - Add or Remove user service for automation
  unlock        - Unlock all KeePassXC databases from keyring
  watch         - Monitor screensaver lock/unlock events
  help          - Show this help message

Service Options:
  add           - Add systemd user service to automate unlock
  remove        - Remove systemd user service and automation
  status        - Status of service
```
