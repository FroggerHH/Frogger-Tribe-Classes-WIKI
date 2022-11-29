You must have BepInEx installed correctly! I can not stress this enough.

Windows (Steam)
Locate your game folder manually or start Steam client and :
Right click the Valheim game in your steam library
"Go to Manage" -> "Browse local files"
Steam should open your game folder
Extract the contents of the archive. Put the DLL into BepInEx\plugins the other files are needed for the thunderstore upload and can be ignored.

Server
Must be installed on both the client and the server for syncing to work properly.

Locate your main folder manually and :
Extract the contents of the archive into BepInEx\plugins.
Launch your game at least once to generate the config file needed if you haven't already done so.
Reboot your server. All clients will now sync to the server's config file even if theirs differs. Config Manager mod changes will only change the client config, not what the server is enforcing.
