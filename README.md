# 7: The Observer — releases

Signed builds of **7: The Observer** (Windows x64; plays on Steam Deck through Proton).

**New players:** open the newest release that has a `Seven-Starter-*.zip` asset, download that ZIP, extract the whole
`Seven` folder somewhere you can write (e.g. `Documents\Games`), and start `SevenLauncher.exe`. The launcher installs
every later update by itself. Steam Deck: add `SevenLauncher.exe` as a non-Steam game and force Proton.

**Everything else here is for the launcher.** Each `game-<build>` release holds `update-catalog.json`,
`game-manifest.json` (both signed by the publisher key pinned in the launcher) and `game.zip`. The launcher reads
`releases/latest/download/update-catalog.json`, checks the signatures and SHA-256 of every file, and refuses anything
not signed with that key. Your saves are backed up before each update; the previous version stays installed so you can
go back from the launcher's menu.

There is no source code in this repository.
