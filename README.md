# nixNotes

## Get nextcloud to store your credientials
- We need to enable a keyring daemon:

`services.gnome3.gnome-keyring.enable = true;`

## Print to (wireless) printer
- Install drivers
- Add printer through system-config-printer
- Change device URI (to your IP)
 `ipp://192.168.0.171`
