## Command

#### compression and decompression

```
tar czvf models.tar models  # for compression
tar -xvf py36.tar  # for decompression
```

#### sending files between Linux machine

```
python -m http.server [p]  # from, [p] is port code, such as 8001
wget ip[:p]/py36.tar  # to, get files
```