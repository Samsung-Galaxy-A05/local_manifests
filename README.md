## How to use

1. Clone local manifest
```sh
git clone https://github.com/Samsung-Galaxy-A05/local_manifests.git -b lineage-24.0 .repo/local_manifests
```

2. Start sync
```sh
repo sync -c --no-clone-bundle --no-tags --optimized-fetch --prune --force-sync
```
