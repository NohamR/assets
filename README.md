# Compression
Files are compressed using xz with the –best flag and the extreme preset
```shell
tar -cvf archive.tar folder_or_file
xz -9e archive.tar
```

# Decompression

```shell
xz -d Nightly_aarch64.tar.xz
tar -xvf archive.tar
```