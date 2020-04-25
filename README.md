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
 
## Fix QT's awful (large) scaling
- put in your  .zshrc (.bashrc)
- Tweak `QT_SCALE_FACTOR` as needed.

`export QT_SCALE_FACTOR=1.4`

`export QT_AUTO_SCREEN_SCALE_FACTOR=0`

`export QT_SCREEN_SCALE_FACTORS=2`
