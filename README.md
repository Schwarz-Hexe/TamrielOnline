# README #

Tamriel Online (https://www.nexusmods.com/skyrim/mods/67038/?) - An online multiplayer mod for Skyrim.
This fork is a tentative exploration of how this mod functions aiming to provide documentation and determine feasability of refactoring to ease future updates to achieve compatability with other modules and modifications.

### Build Dependencies ###

* Photon Realtime C++ Windows SDK v4.1.5.1 (https://www.photonengine.com/en-US/sdks#realtimewindows) - The latest version should also work, but may require updates the mod's source.
	* All the photon references under "Configuration Properties" -> "Linker" -> "Input" -> "Additional Dependencies", and "Configuration Properties" -> "C/C++" -> "General" -> "Additional Include Directories" in VS need to have their directories changed to your local SDK's directory.
* SKSE v1.7.3 (http://skse.silverlock.org/)

### Connection Requirements ###

* Create a free exitgames account at https://www.photonengine.com/en-US/Account/Signup
	* Replace the example app id in "TamrielOnline.ini" under "LanSettings" -> "appid" with your app id.
