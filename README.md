<p align="center">
<img src="https://github.com/user-attachments/assets/ed59c139-0818-4200-b39c-b8798c30dac6" />
</p>

---

# Credits:

- [**AOSP**](https://android.googlesource.com)
- [**LineageOS**](https://github.com/LineageOS)
- [**Crdroid Android**](https://github.com/crdroidandroid)

To get started with the building process, you'll need to get familiar with [Git and Repo](http://source.android.com/source/using-repo.html).

# Requirements:

- Around 400G disk space.
- A computer with at least 16GB RAM running Linux (recommended) or MacOS.
- Build environment [setup](https://github.com/akhilnarang/scripts).

# Sync Source:-

```bash
    repo init -u https://github.com/SuperiorOS/manifest.git -b sixteen-los --git-lfs
```

```bash
    repo sync --force-sync
```

# Start the build:-

```bash
./build-superior.sh <devicecodename> [options]
```
```bash
Options:
  -h, --help            Display this help message
  -c, --clean           Wipe the tree before building
  -i, --installclean    Dirty build - Use 'installclean'
  -t, --build-type      Specify build type
  -j, --jobs            Specify jobs/threads to use
  -m, --module          Build a specific module
  -s, --sign-keys       Specify path to sign key mappings
  -p, --pwfile          Specify path to sign key password file
  -d, --delta           Generate a delta ota from the specified target_files zip
  -z, --imgzip          Generate fastboot flashable image zip from signed target_files

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

