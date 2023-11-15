# GS201 Kernel Manifest

## How to sync?
`repo init -u https://github.com/Google-Exynos/kernel_manifest.git -b fourteen`

 `repo sync -c --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune -j$(nproc --all)`

 ## How to build?
 `BUILD_CONFIG=private/gs-google/build.config.cloudripper build/build.sh`
