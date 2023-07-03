![banner](https://raw.githubusercontent.com/xdroid-oss/.github/55654e4a1b88977f60e2116d7cbeed17e87f450b/banner.png)

# xdroidOSS

### Sync source ###
```bash
repo init -u https://github.com/xDroid-OS/manifest -b thirteen
```
```bash
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

### Build source ###
```
. build/envsetup.sh
lunch xdroid_$devicecodename-userdebug
make xd -j$(nproc --all)
```
### Full Credits ###
 * [**xdroidOSS**](https://github.com/xdroid-oss)
