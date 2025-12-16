# 🚀 Local Manifests

This repository contains the **local manifests** required to sync device-specific repositories for building the ROM.

👉 **This manifest will sync the _device tree_, _vendor tree_, and _kernel tree_ from the _Halcyon Device Organization_.**

---

## 📦 Sync the Local Manifests

```bash
git clone -b test https://github.com/Blazing-Forest/local_manifests.git .repo/local_manifests
```

```bash
repo sync -j"$(nproc --all)" --force-sync
```

---

## Building

```bash
source build/envsetup.sh
```

```bash
lunch halcyon_peridot-bp4a-userdebug
```

---