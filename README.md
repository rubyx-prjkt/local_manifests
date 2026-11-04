### 📥 Clone the manifest

```bash
git clone https://github.com/rubyx-prjkt/local_manifests.git -b main .repo/local_manifests
```

### ⚡ Sync the sources

```bash
repo sync -c -j"$(nproc --all)" --no-clone-bundle --no-tags
```
