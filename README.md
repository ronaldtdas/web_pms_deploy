# web_pms_deploy

## Creating a Release

### 1. Create release with files

```bash
gh release create v1.0.7 --title "pms v1.0.7" --notes "release notes" ./file1 ./file2
```

### 2. Upload additional files

```bash
gh release upload v1.0.7 ./path/to/file
```

### 3. View releases

```bash
gh release list
```
