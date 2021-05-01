# Soni UI #

## This org will be abandoned when Android 12 Comes. We'll make a new org by then. ## 

```bash

# Initialize local repository
repo init -u git://github.com/XOSP-Reborn/manifest.git -b eleven

# Sync
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

### Build ###

```bash

# Set up environment
$ . build/envsetup.sh

# Choose a target
$ lunch soni_$device-userdebug

# Build the code
$ mka bacon -jX
```

### Credits and thanks ### 

- PixelExperience

- TenX OS

- Rick Astley

- Curtana bois

ROM proudly made with gitpod :)


### Applying Maintainership ###

soon not now
