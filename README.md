# nixNotes

## Get nextcloud to store your credientials
- We need to enable a keyring daemon:

`services.gnome3.gnome-keyring.enable = true;`

## Get keyring to stop asking you for password on startup
- install seahorse
- Select your keyring, change password to nothing (hit enter).
- This is unsecure, but it works.

## Print to (wireless) printer
- Install drivers
- Add printer through system-config-printer
- Change device URI (to your IP)
 `ipp://192.168.0.171`
