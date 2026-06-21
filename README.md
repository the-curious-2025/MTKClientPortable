# MTKClient Portable

## What is this?

A portable version of MTKClient that can be transferred to any computer without needing to download Python, pip, requirements, or any dependencies. Everything you need is already included in this folder.

## How does it work?

The complete Python environment is bundled inside, including all necessary requirements and libraries. No external installations needed.

## Quick Start

1. **Extract the ZIP file** to your desired location
2. **Install usbdk.exe** (included in the ZIP)
   - This is required for USB drivers to function properly
   - Without it, MTKClient won't be able to connect to your device
3. **Run the tool**
   - Command line: Run `mtk.bat`
   - GUI mode: Run `mtk_gui.bat`

## Important Requirements

⚠️ **You MUST install usbdk.exe before using MTKClient Portable** ⚠️

The usbdk driver is essential and is included in the ZIP file. Install it first, then you can run MTKClient.

## Testing Status

This version has been tested and validated to work properly. While not tested on every system, it performs well based on our checks.

## Troubleshooting

If you encounter issues:
- Ensure usbdk.exe was installed correctly
- Try running as Administrator
- Check USB ction
- Verify device drivers are properly installed

## Credit

Created by [@iosi-poli](https://github.com/iosi-poli)

## About MTKClient

MTKClient is a versatile tool for working with MediaTek devices. For more information about the original project, visit the [MTKClient GitHub repository](https://github.com/bkerler/mtkclient).

---

**License**: See LICENSE file for details.
