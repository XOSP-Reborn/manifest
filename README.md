# XOSP but reborn #

<p align="center">
 <img src="https://github.com/XOSP-Reborn/manifest/blob/eleven/banner.jpg" > 
</p>

## source is basically unbootable so keep your dirty hands away ##

### Sync ###

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
$ lunch xosp_$device-userdebug

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
