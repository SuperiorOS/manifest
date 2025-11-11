<p align="center">
  <img src="https://github.com/user-attachments/assets/744ff7e8-cd87-48c8-bd8c-13a3025f012d" alt="SuperiorOS Logo" />
</p>

<h1 align="center">SuperiorOS</h1>
<p align="center">A clean, stable, and performance-focused Android ROM.</p>

---

## 🧠 Credits

- [**AOSP**](https://android.googlesource.com)
- [**LineageOS**](https://github.com/LineageOS)
- [**crDroid Android**](https://github.com/crdroidandroid)

Before building, make sure you’re familiar with [Git and Repo](https://source.android.com/setup/develop/repo).


## ⚙️ Requirements

| Resource | Recommended |
|-----------|--------------|
| **Disk Space** | ~400 GB |
| **RAM** | 16 GB or higher |
| **OS** | Linux (preferred) or macOS |
| **Build Environment** | [Setup using Akhil Narang’s scripts](https://github.com/akhilnarang/scripts) |


## 🧩 Sync Source

```bash
repo init -u https://github.com/SuperiorOS/manifest.git -b sixteen-los --git-lfs
repo sync --force-sync
```


## 🏗️ Building SuperiorOS

Run the build script:

```bash
./build-superior.sh <devicecodename> [options]
```

### Available Options

| Option               | Description                              |
| -------------------- | ---------------------------------------- |
| `-h, --help`         | Display this help message                |
| `-c, --clean`        | Clean the entire tree before building    |
| `-i, --installclean` | Dirty build with *installclean*          |
| `-t, --build-type`   | Specify build type                       |
| `-j, --jobs`         | Number of threads to use                 |
| `-m, --module`       | Build a specific module                  |
| `-s, --sign-keys`    | Specify path to sign key mappings        |
| `-p, --pwfile`       | Path to sign key password file           |
| `-d, --delta`        | Generate delta OTA from target_files zip |
| `-z, --imgzip`       | Generate fastboot flashable image zip    |


## 📦 Downloads

| Platform               | Link                                                                                |
| ---------------------- | ----------------------------------------------------------------------------------- |
| 📦 **SourceForge**     | [Download Builds](https://sourceforge.net/projects/superioros/files/)               |
| 🧭 **GitHub Releases** | [Official Devices](https://github.com/SuperiorOS/OTA/releases) |


## 🌍 Translations

Want to help translate SuperiorOS?
Join us on [**Crowdin**](https://crowdin.com/project/superior-os).


## 🪲 Reporting Issues

When reporting bugs or crashes:

* Ensure you’re on the **latest official build**.
* Include a **logcat** or relevant logs.
* Mention your **device codename** and **build version**.

Join our [**Telegram Chat**](https://t.me/superioros) for support.


## 📊 Download Statistics

### 🧭 GitHub

![GitHub all releases](https://img.shields.io/github/downloads/SuperiorOS-Devices/official_devices/total?logo=GitHub\&style=for-the-badge\&color=blue)

### 🚀 SourceForge

| Period      | Badge                                                                                                               |
| ----------- | ------------------------------------------------------------------------------------------------------------------- |
| **Daily**   | ![SF Daily](https://img.shields.io/sourceforge/dd/superioros?color=8827ed\&logo=sourceforge\&style=for-the-badge)   |
| **Weekly**  | ![SF Weekly](https://img.shields.io/sourceforge/dw/superioros?color=6d1cf6\&logo=sourceforge\&style=for-the-badge)  |
| **Monthly** | ![SF Monthly](https://img.shields.io/sourceforge/dm/superioros?color=4b02a4\&logo=sourceforge\&style=for-the-badge) |
| **Total**   | ![SF Total](https://img.shields.io/sourceforge/dt/superioros?color=ff4d4d\&logo=sourceforge\&style=for-the-badge)   |


## 🔗 Community Links

* 💬 [**Telegram Chat**](https://t.me/superioros)
* 📢 [**Telegram Channel**](https://t.me/superior_os)


<p align="center">
  <sub>Built with ❤️ by the <a href="https://github.com/SuperiorOS">SuperiorOS Team</a> & Community</sub>
</p>