# WinMug User Guide

**WinMug** is a desktop application for Windows that allows you to download your entire SmugMug photo library to your local computer. This guide will walk you through the process of using WinMug to backup your precious photos.

## Table of Contents

1. [Getting Started](#getting-started)
2. [Authentication](#authentication)
3. [Browsing Your Albums](#browsing-your-albums)
4. [Selecting Albums for Download](#selecting-albums-for-download)
5. [Downloading Photos](#downloading-photos)
6. [Folder Structure](#folder-structure)
7. [Troubleshooting](#troubleshooting)
8. [FAQ](#faq)

## Getting Started

### System Requirements
- Windows 10 or later
- .NET 8.0 Runtime (automatically installed if missing)
- Internet connection
- SmugMug account with photos

### Installation
1. Download the latest WinMug release from [GitHub Releases](https://github.com/YourUsername/WinMug/releases)
2. Extract the ZIP file to a folder of your choice
3. Run `WinMug.exe` to start the application

## Authentication

### Automatic Authentication (Recommended)
1. Click the **"Authenticate with SmugMug"** button
2. WinMug will automatically open your web browser
3. Log in to your SmugMug account if prompted
4. Grant permission to WinMug to access your photos
5. The browser will automatically redirect back to WinMug
6. You should see your profile information appear in the app

### Manual Authentication (Fallback)
If automatic authentication fails:
1. WinMug will display an authorization URL
2. Copy and paste this URL into your web browser
3. Log in to SmugMug and authorize the application
4. SmugMug will display a 6-digit verification code
5. Enter this code in WinMug and click **"Submit"**

### Authentication Troubleshooting
- **Browser doesn't open**: Copy the authorization URL manually
- **Permission denied**: Make sure you're logged into the correct SmugMug account
- **Invalid verification code**: Ensure you enter exactly 6 digits without spaces or dashes

## Browsing Your Albums

### Loading Your Albums
1. After successful authentication, click **"Show my albums"**
2. WinMug will discover all your albums (this may take a few minutes for large collections)
3. A progress bar will show the discovery progress
4. Once complete, you'll see a list of all your albums

### Album Information
Each album displays:
- **Album name**: The title of your album
- **Image count**: Number of photos in the album
- **Size estimate**: Approximate download size
- **Privacy icon**: Indicates if the album is public 🌐 or private 🔒
- **Checkbox**: For selecting albums to download

### Album Statistics
At the top of the album list, you'll see:
- **Total albums found**: Your complete album count
- **Total estimated size**: Size of your entire photo library
- **Selected for download**: Number of selected albums and their total size

## Selecting Albums for Download

### Individual Selection
- Click the checkbox next to any album to select/deselect it
- Selected albums show a blue checkmark ✓

### Bulk Selection
- **Select all**: Click to select every album
- **Deselect all**: Click to clear all selections

### Smart Selection Tips
- Start with a few small albums to test the download process
- Consider your available disk space before selecting large albums
- Private albums require full authentication to download

## Downloading Photos

### Setting Up Download
1. **Select target directory**: Click **"Browse..."** to choose where photos will be saved
2. **Select albums**: Choose which albums to download using checkboxes
3. **Start download**: Click **"Start Download"** when ready

### Download Process
- WinMug downloads photos in their original quality
- Progress is shown with a progress bar and status messages
- You can pause or cancel downloads if needed
- Downloaded photos are organized in folders matching your SmugMug structure

### Download Controls
- **Pause**: Temporarily stop the download (can be resumed)
- **Cancel**: Stop and abort the current download

## Folder Structure

### Local Organization
WinMug preserves your SmugMug folder structure:

**SmugMug Structure:**
```
/Travel/Europe/Paris
/Travel/Europe/London
/Family/2024/Birthday
```

**Local Structure:**
```
Target Directory/
├── Travel/
│   └── Europe/
│       ├── Paris/
│       │   ├── photo1.jpg
│       │   └── photo2.jpg
│       └── London/
│           ├── photo3.jpg
│           └── photo4.jpg
└── Family/
    └── 2024/
        └── Birthday/
            ├── photo5.jpg
            └── photo6.jpg
```

### File Naming
- Original filenames are preserved
- If duplicate names exist, WinMug adds numbers (e.g., `photo_1.jpg`, `photo_2.jpg`)
- File extensions match the original format (JPG, PNG, etc.)

## Troubleshooting

### Common Issues

**"Authentication failed"**
- Check your internet connection
- Verify your SmugMug account credentials
- Try the manual authentication method

**"No albums found"**
- Ensure your SmugMug account has albums with photos
- Check that you granted full access permissions
- Try logging out and authenticating again

**"Download failed"**
- Check available disk space
- Verify internet connection stability
- Try downloading fewer albums at once

**"Permission denied"**
- Ensure the target directory is writable
- Try selecting a different download location
- Run WinMug as administrator if necessary

### Getting Help
- Check the application logs for detailed error messages
- Visit our [GitHub Issues](https://github.com/YourUsername/WinMug/issues) page
- Include log messages when reporting problems

## FAQ

**Q: Is WinMug free to use?**
A: Yes, WinMug is completely free and open-source.

**Q: Does WinMug modify my SmugMug photos?**
A: No, WinMug only downloads photos. It never modifies or deletes anything on SmugMug.

**Q: Can I download private albums?**
A: Yes, WinMug can download both public and private albums after proper authentication.

**Q: What photo formats are supported?**
A: WinMug downloads all formats supported by SmugMug (JPG, PNG, GIF, etc.).

**Q: Can I resume interrupted downloads?**
A: Currently, you need to restart downloads if they're interrupted. Resume functionality is planned for future versions.

**Q: How much disk space do I need?**
A: Check the size estimates in WinMug before downloading. Ensure you have at least 20% more space than the estimated size.

**Q: Can I download videos?**
A: Yes, WinMug downloads both photos and videos from your SmugMug account.

---

## Support

For additional support:
- 📖 Read this User Guide
- 🐙 Visit our [GitHub Repository](https://github.com/YourUsername/WinMug)
- 🐛 Report bugs on [GitHub Issues](https://github.com/YourUsername/WinMug/issues)
- 💬 Join discussions on [GitHub Discussions](https://github.com/YourUsername/WinMug/discussions)

**Happy downloading! 📸**

---
*© 2025 WinMug - Open Source SmugMug Photo Downloader*
