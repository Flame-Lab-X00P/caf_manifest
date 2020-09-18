# CAF_manifest #

### Sync ###

```bash

# Initialize local repository
repo init -u https://github.com/Flame-Lab-X00P/caf_manifest -b ten

# Sync
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```
