LLUVIA-OS
==================

Getting Started
---------------
To initialize your local repository using the our trees, use a command like this:

    repo init -u https://github.com/LLuviaOS/platform_manifest.git -b 8.1

Then to sync up:
---------------
    repo sync --force-sync --force-broken --no-clone-bundle -jxxx (ur choice dude)


Finally to build:
-----------------

```bash
  . build/envsetup.sh
  lunch llos_devicecodename-userdebug
  mka rain
```
Credits
-------
* [**GZOSP (Base)**](https://github.com/gzosp)
* [**LineageOS**](https://github.com/LineageOS)
* [**DirtyUnicorns**](https://github.com/DirtyUnicorns)
* [**TeamSubstratum (Theme Engine)**](https://github.com/Substratum)

