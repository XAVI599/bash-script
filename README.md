# Thumbnail Generator (Bash + ImageMagick)

A simple Bash script to automate thumbnail generation for images (`.jpg` and `.png`).  
The script checks if a thumbnail already exists and only resizes images when necessary, optimizing processing time.

---

## Features

- Automatically generates thumbnails for images in the current directory.
- Skips images that already have thumbnails of the correct dimensions.
- Ensures thumbnails respect maximum width/height constraints.
- Supports `.jpg` and `.png` images.
- Safe handling of filenames with spaces.

---

## Requirements

- Bash (tested on Linux)
- [ImageMagick](https://imagemagick.org/) installed (`identify` command)

---

## Usage

1. Make the script executable (if not already):

```bash
chmod +x thumbnail_generate

./thumbnail_generate
