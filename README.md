To get started with the building process, you'll need to get familiar with [Git and Repo](http://source.android.com/source/using-repo.html).

# Requirements:

- Around 400G disk space.
- A computer with at least 16GB RAM running Linux (recommended) or MacOS.
- Build environment [setup](https://github.com/akhilnarang/scripts).

# Sync Source:-

```bash
repo init -u https://github.com/LineVall/linevall_manifest.git -b ucup --git-lfs
```

```bash
repo sync --no-tags --prune --optimized-fetch --no-clone-bundle
```

# Start the build:-

```bash
  . build/envsetup.sh
  lunch linevall_<devicecodename>-userdebug
  m bacon
```

---


# Credits:

- [**AOSP**](https://android.googlesource.com)
- [**LineageOS**](https://github.com/LineageOS)
- [**SuperiorOS**](https://github.com/SuperiorOS)
- [**BananaDroidOS**](https://github.com/bananadroid)
- [**PixelExperience**](https://github.com/PixelExperience)
- [**ProtonAOSP**](https://github.com/ProtonAOSP)
- [**ArrowOS**](https://github.com/ArrowOS)
- [**Pixys OS**](https://github.com/PixysOS)
- [**Crdroid Android**](https://github.com/crdroidandroid)
- [**AfterlifeOS**](https://github.com/AfterLifePrjkt13)
- [**Patungan Team**]
- [**Atiga Prjk**]