# archlinux-appstream-data-libre
Arch Linux application database for AppStream based software centers without nonfree suggestions and without support for services that are unsafe and dangerous for privacy

***! this is work in progress (see task.txt), and information presented are based on author research, im also apologize if my engliz is bad, thank you for all your interest and participation !***

archlinux-appstream-data (aadl for short) provided local metadata necessary for appstream based software center to build software and plugin catalogues presented to user, then it talks to package manager to install, remove, or upgrade program of user choice.

aadl acts as supplementary metadata over package manager repos, e.g. aside from package version and description that already provided by distro package repos it supplement it with program icons, details, and some extra info.

some note taking:
-aadl only listing gui programs and plugins (can be disabled)
-aadl doesnt ship screenshot, review, and plugins as they are frequently changed. they are synced separately trough online repos configured in software center

whereas (in archlinux)
-the screenshot synced trough debian web
-review are synced trough open desktop org review web
-plugins are synced trough their source web ex. shell extension -> gnome shell extension web
(see respective software center source codes)
