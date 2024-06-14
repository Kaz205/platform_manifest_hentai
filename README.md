## Building Android ##
Your one-stop destination for all the documentation about building Android can be found [here](https://source.android.com/setup/build/building).

## Repo Init ##
```bash
repo init -u https://github.com/Kaz205/platform_manifest_hentai.git -b Ursamoon 
```
## Sync Source ##
```bash
repo sync --force-sync --no-clone-bundle --current-branch --no-tags -j$(nproc --all)
```
## Build Time (Linux x86_64 ONLY) ##
```bash
. build/envsetup.sh
make dist
```

