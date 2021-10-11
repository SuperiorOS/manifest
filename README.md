<p align="center">
<img src="https://github.com/SuperiorOS/manifest/assets/29405483/4186221f-e198-43bf-a2d4-d1046a0db269" />
</p>

---

# Credits:

- [**AOSP**](https://android.googlesource.com)
- [**LineageOS**](https://github.com/LineageOS)
- [**PixelExperience**](https://github.com/PixelExperience)
- [**ProtonAOSP**](https://github.com/ProtonAOSP)
- [**ArrowOS**](https://github.com/ArrowOS)
- [**Pixys OS**](https://github.com/PixysOS)
- [**Crdroid Android**](https://github.com/crdroidandroid)

To get started with the building process, you'll need to get familiar with [Git and Repo](http://source.android.com/source/using-repo.html).

# Requirements:

- Around 400G disk space.
- A computer with at least 16GB RAM running Linux (recommended) or MacOS.
- Build environment [setup](https://github.com/akhilnarang/scripts).

# Sync Source:-

```bash
    repo init -u https://github.com/SuperiorOS/manifest.git -b fourteen
```

```bash
    repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

# Start the build:-

```bash
  . build/envsetup.sh
  lunch superior_<devicecodename>-userdebug
  m bacon -j$(nproc --all)
```

---

# Some Links:-

- [**Telegram Public Chat**](https://t.me/superioros)
- [**Telegram Channel**](https://t.me/superior_os)
- [**Crowdin**](https://crowdin.com/project/superior-os)

---

# Download Stats:-

| Download Source | Total                                                                                                                                                |
| --------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------- |
| GitHub Releases | ![GitHub all releases](https://img.shields.io/github/downloads/SuperiorOS-Devices/official_devices/total?logo=GitHub&style=for-the-badge&color=blue) |

| Download Source | Daily                                                                                                                              | Weekly                                                                                                                             | Monthly                                                                                                                            | Total                                                                                                                              |
| --------------- | ---------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- |
| SourceForge     | ![SourceForge](https://img.shields.io/sourceforge/dd/superioros?color=8827ed&logo=sourceforge&logoColor=black&style=for-the-badge) | ![SourceForge](https://img.shields.io/sourceforge/dw/superioros?color=6d1cf6&logo=sourceforge&logoColor=black&style=for-the-badge) | ![SourceForge](https://img.shields.io/sourceforge/dm/superioros?color=4b02a4&logo=sourceforge&logoColor=black&style=for-the-badge) | ![SourceForge](https://img.shields.io/sourceforge/dt/superioros?color=ff4d4d&logo=sourceforge&logoColor=black&style=for-the-badge) |
