---
<p align="center">
<img src="https://user-images.githubusercontent.com/66232233/185937884-8363abfa-570a-482a-b911-26ded6d7e01c.jpg" />
</p>

# Credits:

- [**AOSP**](https://android.googlesource.com)
- [**LineageOS**](https://github.com/LineageOS)
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
    repo init -u https://github.com/SuperiorOS/manifest.git -b thirteen-aosp-qpr3
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

# Download Stats

[![Download Superior](https://img.shields.io/sourceforge/dd/superioros.svg)](https://sourceforge.net/projects/superioros/files/latest/download)

[![Download Superior](https://img.shields.io/sourceforge/dw/superioros.svg)](https://sourceforge.net/projects/superioros/files/latest/download)

[![Download Superior](https://img.shields.io/sourceforge/dm/superioros.svg)](https://sourceforge.net/projects/superioros/files/latest/download)

[![Download Superior](https://img.shields.io/sourceforge/dt/superioros.svg)](https://sourceforge.net/projects/superioros/files/latest/download)

