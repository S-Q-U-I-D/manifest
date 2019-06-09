# SQUID #

### Sync ###

```bash

# Initialize local repository
repo init -u https://github.com/S-Q-U-I-D/manifest -b pie

# Sync
repo sync -c -jx --force-sync --no-clone-bundle --no-tags
```

### Build ###

```bash

# Set up environment
$ . build/envsetup.sh

# Choose a target
$ lunch squid_$device-userdebug

# Build the code
$ mka squid 
```
