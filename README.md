Getting started with NusantaraProject
====================

![NusantaraProject](https://github.com/NusantaraProject-ROM/Nusantara/blob/master/goodies/banner.png?raw=true)

Initialize Local Repository
-------------
```bash
  repo init -u https://github.com/unkl933/android_manifest -b 12
```

Syncing Repository
-------------
```bash
  repo sync -c --force-sync --no-tags --no-clone-bundle -j$(nproc --all)
```

Lunch Command
-------------
```bash
  . build/envsetup.sh
  lunch nad_<device_codename>-buildtype
  make nad
```
