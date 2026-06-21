# MTKClient Portable

## What is this?

A portable build of MTKClient that can be moved to another computer without installing Python, pip, or extra packages. The required environment is already included.

## How does it work?

The folder contains a bundled Python environment together with the libraries MTKClient needs, so the tool can run without a separate setup.

## Quick Start

1. **Download or clone this repository**
2. **Extract `MTKCliantPortable.zip`** to the location you want to use
3. **Install `usbdk.exe`** from inside the ZIP
   - This is required for USB drivers to function properly
   - Without it, MTKClient may not detect or communicate with the device correctly
4. **Run MTKClient**
   - Command line: Run `mtk.bat`
   - GUI mode: Run `mtk_gui.bat`

## Important Requirements

⚠️ **You MUST install usbdk.exe before using MTKClient Portable** ⚠️

The usbdk driver is essential and is included in the ZIP file. Install it first, then you can run MTKClient.

## Testing Status

This package has not been tested on every machine, but the checks done so far were successful and the build worked well in practice.

## Troubleshooting

If you encounter issues:
- Ensure usbdk.exe was installed correctly
- Try running as Administrator
- Check the USB cable and port
- Verify device drivers are properly installed

## Credit

Portable package by [@sesese1234](https://github.com/sesese1234)

## About MTKClient

MTKClient is a versatile tool for working with MediaTek devices. For more information about the original project, visit the [MTKClient GitHub repository](https://github.com/bkerler/mtkclient).

---

**License**: See LICENSE file for details.
