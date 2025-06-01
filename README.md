# MiSTer-handheld-mgls

Just a collection of mgl files for handcores on the MiSTer. This will give you
an extra `Handheld` menu on the OSD.

This will give you menu items for the following cores:

* Atari Lynx
* Game & Watch
* Game Boy
* Game Boy Advance
* Game Boy color
* Game Gear
* Mega Duck
* Neo Geo Pocket
* Neo Geo Pocket Color
* Pocket Challenge V2
* Pokemon Mini
* TurboExpress
* WonderSwan
* WonderSwan Color


## Installation Instructions

1. Add the following to `/media/fat/downloader.ini`

```ini
[handheld_mgls]
db_url = https://raw.githubusercontent.com/davewongillies/MiSTer-handheld-mgls/db/db.json.zip
```

2. Run `update_all` from the `Scripts` menu
3. For Neo Geo Pocket & Neo Geo Pocket Color you'll need to either symlink or copy `NeoGeoPocket.rbf` and `jtngpc.rbf` to `/media/fat/_Handheld/cores`
