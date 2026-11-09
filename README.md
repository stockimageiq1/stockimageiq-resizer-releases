# ImageIQ Resizer for Mac

Free Mac app from [Stock ImageIQ](https://stockimageiq.com). It makes small upload copies of your photos and videos so you can send a whole shoot to Stock ImageIQ in minutes — your originals are never changed.

## Download

- **Apple Silicon (M1–M4):** [ImageIQ-Resizer-mac-arm64.dmg](https://github.com/stockimageiq1/stockimageiq-resizer-releases/releases/latest/download/ImageIQ-Resizer-mac-arm64.dmg)
- **Intel:** [ImageIQ-Resizer-mac-x64.dmg](https://github.com/stockimageiq1/stockimageiq-resizer-releases/releases/latest/download/ImageIQ-Resizer-mac-x64.dmg)

Not sure which Mac you have? Apple menu → About This Mac: "Chip Apple M…" means Apple Silicon, "Processor Intel…" means Intel.

Open the .dmg and drag **ImageIQ Resizer** into Applications. The app is signed and notarized by Apple; the only prompt you should see is "downloaded from the Internet". If macOS says it cannot verify the app, do not bypass the warning — download it again from this page and tell us.

## What it does

- Drop a folder. You get a `<folder>_lowres` copy next to it (or where you choose) with the same file names.
- Photos: at most 1280 px on the long side, same format as the original (JPEG, PNG, TIFF, WebP; HEIC becomes JPEG). Capture date is kept, everything else (GPS, camera data) is removed.
- Videos: 720p H.264, no audio.
- Upload the copy folder to Stock ImageIQ. Because the names match, the CSV export and the Mac app's write-to-files work on your originals.
- Updates: the app checks here on launch and offers new versions.

Requires macOS 12 or later. Windows: coming later. Code lives in a private repo; this repository holds releases only.
