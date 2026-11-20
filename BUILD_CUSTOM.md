# Normal Version

## Custom Build Instructions

Execute the “make” command.

```
make clean
make EMOJI_SRC_DIR=2D/png/128 BYPASS_SEQUENCE_CHECK='True'
```

```
make clean
make EMOJI_SRC_DIR=3D/png/128 BYPASS_SEQUENCE_CHECK='True'
```

# Blob Version

## Custom Build Instructions

### Provisional build

provisional build with the “make” command.

### Overwrite images

1. Copy the image files under `/C1710-blobmoji/compressed_pngs/` to `/build/compressed_pngs/` and overwrite them.

### Modify “Makefile"

Modify the “Makefile” to look like this branch. (comment out lines 191 and 192)

### Final Build

Build again with the “make” command.

```
make BYPASS_SEQUENCE_CHECK='True'
```

Ended.
Good job.

# Old Blob Version

## Custom Build Instructions

### Provisional build

provisional build with the “make” command.

### Overwrite images

1. Copy the image files under `/C1710-blobmoji/compressed_pngs/` to `/build/compressed_pngs/` and overwrite them.
2. Copy the image files under `/noto-emoji-f7abf9645ce10d923fb5e8bccf62e0ffae47b999/compressed_pngs/` to `/build/compressed_pngs/` and overwrite them.

### Modify “Makefile"

Modify the “Makefile” to look like this branch. (comment out lines 191 and 192)

### Final Build

Build again with the “make” command.

```
make BYPASS_SEQUENCE_CHECK='True'
```

Ended.
Good job.
