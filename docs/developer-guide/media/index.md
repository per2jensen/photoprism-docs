# Supported Media and Sidecar File Formats

| Format | Description                                              |  Type   |                                                                                                                      Extensions                                                                                                                       |
|--------|----------------------------------------------------------|---------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| BMP    | Bitmap                                                   | Image   | .bmp                                                                                                                                                                                                                                                  |
| GIF    | Graphics Interchange Format                              | Image   | .gif                                                                                                                                                                                                                                                  |
| HEIF   | High Efficiency Image File Format (HEIF)                 | Image   | .heic, .heif                                                                                                                                                                                                                                          |
| JPG    | Joint Photographic Experts Group (JPEG)                  | Image   | .jfi, .jfif, .jif, .jpe, .jpeg, .jpg, .thm                                                                                                                                                                                                            |
| MPO    | Stereoscopic (3D JPEG)                                   | Image   | .mpo                                                                                                                                                                                                                                                  |
| PNG    | Portable Network Graphics                                | Image   | .pn, .png                                                                                                                                                                                                                                             |
| TIFF   | Tag Image File Format                                    | Image   | .tif, .tiff                                                                                                                                                                                                                                           |
| WEBP   | Google WebP                                              | Image   | .webp                                                                                                                                                                                                                                                 |
| RAW    | Unprocessed Sensor Data                                  | Raw     | .3fr, .ari, .arw, .bay, .cap, .cr2, .cr3, .crw, .data, .dcr, .dcs, .dng, .drf, .eip, .erf, .fff, .gpr, .iiq, .k25, .kdc, .mdc, .mef, .mos, .mrw, .nef, .nrw, .obm, .orf, .pef, .ptx, .pxn, .r3d, .raf, .raw, .rw2, .rwl, .rwz, .sr2, .srf, .srw, .x3f |
| AAE    | Apple Image Edits                                        | Sidecar | .aae                                                                                                                                                                                                                                                  |
| JSON   | Serialized JSON Data (Exiftool, Google Photos)           | Sidecar | .json                                                                                                                                                                                                                                                 |
| MD     | Markdown Formatted Text                                  | Sidecar | .markdown, .md                                                                                                                                                                                                                                        |
| TOML   | Serialized TOML Data (Tom's Obvious, Minimal Language)   | Sidecar | .toml                                                                                                                                                                                                                                                 |
| TXT    | Plain Text                                               | Sidecar | .txt                                                                                                                                                                                                                                                  |
| XML    | Extensible Markup Language                               | Sidecar | .xml                                                                                                                                                                                                                                                  |
| XMP    | Adobe Extensible Metadata Platform                       | Sidecar | .xmp                                                                                                                                                                                                                                                  |
| YML    | Serialized YAML Data (Config, Metadata)                  | Sidecar | .yaml, .yml                                                                                                                                                                                                                                           |
| 3G2    | Mobile Multimedia Container for CDMA2000 (based on 3GP)  | Video   | .3g2                                                                                                                                                                                                                                                  |
| 3GP    | Mobile Multimedia Container (MPEG-4 Part 12)             | Video   | .3gp                                                                                                                                                                                                                                                  |
| AV1    | AOMedia Video 1 (AV1, AV01)                              | Video   | .av1                                                                                                                                                                                                                                                  |
| AVC    | Advanced Video Coding (AVC, AVC1, H.264, MPEG-4 Part 10) | Video   | .avc                                                                                                                                                                                                                                                  |
| AVI    | Microsoft Audio Video Interleave                         | Video   | .avi                                                                                                                                                                                                                                                  |
| FLV    | Flash Video                                              | Video   | .f4v, .flv                                                                                                                                                                                                                                            |
| HEVC   | High Efficiency Video Coding (HEVC, HVC1, H.265)         | Video   | .hevc                                                                                                                                                                                                                                                 |
| MJPG   | Motion JPEG (M-JPEG)                                     | Video   | .mjpeg, .mjpg                                                                                                                                                                                                                                         |
| MKV    | Matroska Multimedia Container (MKV, MCF, EBML)           | Video   | .mkv                                                                                                                                                                                                                                                  |
| MOV    | Apple QuickTime (QT)                                     | Video   | .mov, .qt                                                                                                                                                                                                                                             |
| MP2    | MPEG 2 (H.262, H.222)                                    | Video   | .mp2, .mpv                                                                                                                                                                                                                                            |
| MP4    | Multimedia Container (MPEG-4 Part 14)                    | Video   | .m4v, .mp, .mp4                                                                                                                                                                                                                                       |
| MPG    | Moving Picture Experts Group (MPEG)                      | Video   | .mpeg, .mpg                                                                                                                                                                                                                                           |
| MTS    | Advanced Video Coding High Definition (AVCHD)            | Video   | .mts                                                                                                                                                                                                                                                  |
| OGV    | Ogg Media by Xiph.Org                                    | Video   | .ogg, .ogv, .ogx                                                                                                                                                                                                                                      |
| WEBM   | Google WebM                                              | Video   | .webm                                                                                                                                                                                                                                                 |
| WMV    | Microsoft Windows Media                                  | Video   | .wmv                                                                                                                                                                                                                                                  |

## CLI Command ##

Run `photoprism show formats` to display all supported formats as a Markdown formatted table.

Command Flags:

- `-c` hides format descriptions to make the output more compact
- `-n` disables text-wrapping so [the output can be pasted into Markdown files](https://github.com/photoprism/photoprism-docs/blob/master/docs/developer-guide/media/index.md)