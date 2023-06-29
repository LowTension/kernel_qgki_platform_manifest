## How to build the kernel
1. Intitalize your local repository using this manifest:
```
repo init -u https://github.com/LowTension/kernel_qgki_platform_manifest.git -b main
```
2. Then to sync up:
```
repo sync

```
3. Build GKI kernel:
```
BUILD_CONFIG=common/build.config.gki.aarch64 build/build.sh
