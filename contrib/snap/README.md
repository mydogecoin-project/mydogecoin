# Mydogecoin Snap Packaging

Commands for building and uploading a Mydogecoin Core Snap to the Snap Store. Anyone on amd64 (x86_64), arm64 (aarch64), or i386 (i686) should be able to build it themselves with these instructions. This would pull the official Mydogecoin binaries from the releases page, verify them, and install them on a user's machine.

## Building Locally
```
sudo apt install snapd
sudo snap install --classic snapcraft
sudo snapcraft
```

### Installing Locally
```
snap install \*.snap --devmode
```

### To Upload to the Snap Store
```
snapcraft login
snapcraft register mydogecoin-core
snapcraft upload \*.snap
sudo snap install mydogecoin-core
```

### Usage
```
mydogecoin-unofficial.cli # for mydogecoin-cli
mydogecoin-unofficial.d # for mydogecoind
mydogecoin-unofficial.qt # for mydogecoin-qt
mydogecoin-unofficial.test # for test_mydogecoin
mydogecoin-unofficial.tx # for mydogecoin-tx
```

### Uninstalling
```
sudo snap remove mydogecoin-unofficial
```