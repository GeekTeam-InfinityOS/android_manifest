# Infinity OS #

### Sync | 同步 ###

```bash

# Initialize local repository
repo init -u https://github.com/GeekTeam-InfinityOS/manifest -b infinity-10

# Sync
repo sync
```

### Build | 编译 ###

```bash

# Set up environment
$ . build/envsetup.sh

# Choose a target
$ lunch aosp_$device-userdebug

# Build the code
$ mka bacon -jX
```
