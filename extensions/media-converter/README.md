<div align="center">
  <h1>Media Converter</h1>
  <p>Convert any media file with just a few keystrokes</p>
</div>

## Features

- Convert videos, images, and audio files with a simple interface
- Support for all popular media formats
- Customise the quality of the output image
- Preserve original quality during conversion for video and audio
- Smart file naming to prevent conflicts
- Automatic FFmpeg installation and management

## Supported Formats

| Media Type | Supported Input Formats                          | Supported Output Formats                 |
| ---------- | ------------------------------------------------ | ---------------------------------------- |
| Video      | MP4, AVI, MKV, MOV, MPG, WEBM                    | MP4, AVI, MKV, MOV, MPG, WEBM            |
| Image      | JPG, JPEG, PNG, WEBP, HEIC, TIFF, TIF, AVIF, BMP | JPG, PNG, WEBP, HEIC (MacOS), TIFF, AVIF |
| Audio      | MP3, AAC, WAV, FLAC                              | MP3, AAC, WAV, FLAC                      |

## Usage

### Convert Media

1. Open Raycast and search for "Convert Media"
2. Select files to convert (⌘ + click for multiple) OR select files in Finder before opening the extension
3. Choose your desired output format (and quality settings for images, defaults are fine)
4. Press &#8984;↵ to start conversion

### ✨ Ask Media Converter

1. Get started by typing @ in Raycast AI
2. Example prompts:
   - Convert the last mp3 file in @finder downloads to wav
   - Convert all png files on my @finder desktop to webp
   - Convert my last screen recording in @finder downloads to webm
   - Convert the heic photos in @finder desktop to png

### Requirements

- FFmpeg:
  - **RECOMMENDED:** If no FFmpeg is auto-detected, the extension will install a correct binary executable. That binary will only be available for the extension (not system-wide), and will be uninstalled when the extension is uninstalled. On MacOS, that weights about 45.6 MB.
  - If FFmpeg is already installed (and auto-detected) and is of version 6.0+, that will be used
  - If you have a 6.0+ FFmpeg binary executable but the extension didn't auto-detect it, you can specify the path to that binary on the Welcome page under actions, &#9881; Specify Local FFmpeg Path (Advanced)
- macOS 10.15 or later

## License

MIT License

## Author

Created by [@leandro.maia](https://raycast.com/leandro.maia)
