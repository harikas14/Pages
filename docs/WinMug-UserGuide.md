# WinMug User Guide
https://yvcodeapps.com/winmug-userguide
**Version 1.0.6** | **Price: $9.99** | **Available on Microsoft Store**

## Getting Started

WinMug is a premium desktop application that helps you download your entire SmugMug photo library to your computer, preserving your album structure and getting the original quality images. Perfect for backing up your precious memories or migrating to a new photo management system.

## Key Features

✅ **Complete Library Download**: Download your entire SmugMug photo collection
✅ **Original Quality**: Get full-resolution images exactly as uploaded
✅ **Folder Structure Preserved**: Maintains your SmugMug album organization
✅ **Private Album Support**: Access password-protected and private content
✅ **Batch Processing**: Download thousands of photos automatically
✅ **Resume Capability**: Pause and resume large downloads
✅ **File Date Preservation**: Sets file creation dates to original photo dates
✅ **Progress Tracking**: Real-time download progress and statistics
✅ **Metadata Export to CSV**: Export photo metadata to CSV files for each album
✅ **Metadata Embedding**: Embed captions, keywords, and GPS data into image files
✅ **Wide Format Support**: Metadata embedding for JPEG, PNG, HEIC, RAW, and more
✅ **Individual Photo Selection**: Select specific photos from albums to download
✅ **SmugMug Links in CSV**: Direct links to each photo on SmugMug in the CSV export

### System Requirements

- **Operating System**: Windows 10 version 1809 or later, Windows 11
- **Architecture**: x64 (64-bit)
- **Memory**: 4 GB RAM minimum, 8 GB recommended for large libraries
- **Storage**: Sufficient free space for your photo library
- **Internet**: Broadband connection recommended for large downloads
- **.NET Runtime**: .NET 8.0 (automatically installed if needed)

### What You Need

- A SmugMug account with photos (any plan type)
- Administrator privileges for initial installation
- An internet connection for downloading
- Adequate free disk space for your photo library

### What You DON'T Need

- ❌ API keys or developer accounts
- ❌ Technical knowledge or programming experience
- ❌ Special SmugMug subscription or plan upgrade
- ❌ Additional software or plugins

## Installation

### From Microsoft Store (Recommended)

1. Open the **Microsoft Store** on your Windows computer
2. Search for **"WinMug"**
3. Click **"Get"** or **"Buy"** ($7.99)
4. The app will download and install automatically
5. Click **"Launch"** or find WinMug in your Start menu

### System Permissions

WinMug may request the following permissions:
- **File System Access**: To save downloaded photos to your chosen location
- **Network Access**: To connect to SmugMug's servers for downloading
- **Credential Storage**: To securely store your SmugMug authentication

## Step-by-Step Instructions

### 1. Launch the Application

1. Open WinMug from your Start menu or desktop
2. The main window will open showing your authentication status
3. You'll see the WinMug logo and authentication section

### 2. Authenticate with SmugMug

1. Click the **"Authenticate with SmugMug"** button
2. Your web browser will open to SmugMug's website
3. **Log in with your regular SmugMug username and password**
   - Use the same credentials you use to access SmugMug normally
   - This is NOT an API key or special developer credential
4. SmugMug will ask if you want to authorize "Winmug" to access your photos
   - **Important**: The app requests "Full" access to download your private photos
   - This is necessary to access albums that aren't public
5. Click **"Authorize"** or **"Allow"** to grant access to your private content
6. SmugMug will show you a **6-digit verification code**
7. Copy this code (it looks like: 123456)
8. Go back to Winmug and paste the code in the "6-digit verification code" field
9. Click **"Complete Authentication"**

✅ **Success!** You should see "Authenticated as [your username]"

**Access Verification**: The app will automatically verify it has access to your private content. You should see a message like "✓ Private access verified" in the log. If you see a warning about "public access only," you may need to re-authenticate.

### 3. Choose Where to Save Your Photos

1. Click the **"Browse..."** button next to "Target Directory"
2. Choose a folder on your computer where you want to save your photos
   - Example: `C:\Users\YourName\Pictures\SmugMug Photos`
   - Make sure you have enough free space!

### 4. Select Albums (Optional)

1. WinMug will display all your albums in a tree structure
2. By default, all albums are selected for download
3. **To download everything**: Leave all albums checked (recommended)
4. **To download specific albums**: Uncheck albums you don't want
5. You can see the total size and image count for your selection
6. Use the **Tree View** or **List View** toggle to switch between views
7. Use the **Search** box to quickly find specific albums

### 4a. Select Individual Photos (Optional)

Want to download only specific photos from an album? WinMug supports individual photo selection:

1. Find an album in the list and click **"View"** to open the album preview
2. The album's photos will display as thumbnails in a grid
3. Click on individual photos to select/deselect them (selected photos show a blue checkmark)
4. Use **"Select All"** or **"Deselect All"** buttons for quick selection
5. Selected photos are added to your download queue
6. Click **"Back to Albums"** to return to the album list
7. Your individual selections are preserved and combined with full album selections

**Tip**: This is perfect for downloading just the best photos from large albums!

### 5. Start Downloading

1. Click **"Start Download"**
2. WinMug will:
   - Discover all your albums and photos
   - Show you the total count and estimated size
   - Begin downloading in original quality
   - Set file creation dates to match photo capture dates
3. Monitor progress with:
   - Overall progress percentage
   - Current file being downloaded
   - Download speed and estimated time remaining
   - Real-time statistics

### 6. Monitor and Control Downloads

- **Status Messages**: Real-time updates on current activity
- **Progress Bars**: Visual indication of completion percentage
- **Statistics**: Photos downloaded, speed, time remaining
- **Pause/Resume**: Stop and continue downloads as needed
- **Cancel**: Abort the download process if necessary
- **Logs**: Detailed technical information for troubleshooting

## What Gets Downloaded

### Folder Structure
Your local folders will match your SmugMug organization:
```
Your Target Folder/
├── Family Photos/
│   ├── 2023 Vacation/
│   │   ├── IMG_001.jpg
│   │   └── IMG_002.jpg
│   └── Birthday Party/
│       └── IMG_003.jpg
└── Work Events/
    └── Conference 2023/
        └── IMG_004.jpg
```

### Photo Quality and Metadata
- **Original Quality**: Full-resolution images exactly as uploaded to SmugMug
- **Original Filenames**: Preserves your original file names when possible
- **All Formats**: JPG, PNG, RAW files, videos, and other media types
- **EXIF Data**: Maintains original photo metadata and camera information
- **Creation Dates**: Sets file creation times to match original photo capture dates
- **Folder Timestamps**: Preserves album creation and modification dates

### Metadata Export Options
WinMug offers two ways to preserve your SmugMug metadata:

**1. CSV Export** (Recommended)
- Creates a `{AlbumName}_metadata.csv` file in each album folder
- Includes: filename, title, caption, keywords, date taken, GPS coordinates, SmugMug link
- Perfect for importing into other photo management systems
- Works for all file types including RAW and videos

**2. Embed in Images**
- Writes metadata directly into image files (EXIF/IPTC/XMP)
- Supports: JPEG, PNG, TIFF, HEIC/HEIF, WebP, and most RAW formats
- Embeds: captions, keywords, GPS coordinates
- Note: RAW files are preserved unmodified for safety

### CSV File Contents
Each CSV file includes the following columns:
| Column | Description |
|--------|-------------|
| FileName | Local filename |
| FilePath | Full path to downloaded file |
| ImageKey | SmugMug unique identifier |
| Title | Photo title from SmugMug |
| Caption | Photo caption/description |
| Keywords | Comma-separated keywords |
| DateTaken | Original capture date |
| UploadDate | Date uploaded to SmugMug |
| Format | File format (JPG, PNG, etc.) |
| IsVideo | Yes/No |
| Latitude | GPS latitude (if available) |
| Longitude | GPS longitude (if available) |
| Altitude | GPS altitude (if available) |
| HasGPS | Yes/No |
| SmugMugLink | Direct link to photo on SmugMug |
| FileExists | Whether file was already downloaded |

## Troubleshooting

### Authentication Issues

**Problem**: "Authentication failed"
- **Solution**: Make sure you're using your SmugMug username/password (not email in some cases)
- **Solution**: Check that you clicked "Authorize" on the SmugMug page
- **Solution**: Make sure the verification code is exactly 6 digits

**Problem**: Browser doesn't open
- **Solution**: Copy the URL from the log and paste it into your browser manually

**Problem**: "Public access only" warning after authentication
- **Solution**: Re-authenticate and make sure you click "Authorize" for full access
- **Solution**: Check that you're authorizing the correct permissions (should be "Full" access)
- **Solution**: Some private albums may not be downloadable with limited access

### Download Issues

**Problem**: "Permission denied" or "Access denied"
- **Solution**: Choose a different target folder where you have write permissions
- **Solution**: Run the application as administrator (right-click → "Run as administrator")

**Problem**: Download is very slow
- **Solution**: This is normal for large libraries - SmugMug limits download speed
- **Solution**: Use Pause/Resume if you need to stop and continue later

**Problem**: Some photos failed to download
- **Solution**: Check the error log for specific issues
- **Solution**: Try running the download again - it will skip already downloaded files

### General Issues

**Problem**: Application won't start
- **Solution**: Make sure you have .NET 8.0 installed
- **Solution**: Check Windows compatibility (Windows 10/11 required)

**Problem**: Running out of disk space
- **Solution**: Choose a target folder on a drive with more space
- **Solution**: Consider downloading albums one at a time

## Tips and Best Practices

### Before You Start
- **Check available disk space** - photo libraries can be very large
- **Use a fast internet connection** - downloads can take hours for large libraries
- **Close other applications** - to free up system resources

### During Download
- **Don't close the application** - downloads will stop
- **Don't put computer to sleep** - downloads will pause
- **Use Pause if needed** - you can always resume later

### After Download
- **Verify your photos** - spot-check that everything downloaded correctly
- **Backup your downloads** - consider copying to an external drive
- **Organize if needed** - you can reorganize the downloaded folders

## Privacy and Security

WinMug is designed with privacy as a top priority. Your photos and data remain completely under your control.

### What Information is Stored Locally
- **OAuth Access Tokens**: Encrypted authentication tokens stored securely on your computer
- **Application Settings**: Your chosen download folder and preferences
- **Temporary Logs**: Technical logs for troubleshooting (automatically cleaned up)
- **No Passwords**: Your SmugMug password is never stored or transmitted to us

### What Information is NOT Collected
- ❌ **No Analytics**: We don't track how you use the application
- ❌ **No Telemetry**: No usage data is sent to external servers
- ❌ **No Photo Access**: Your photos are downloaded directly from SmugMug to your computer
- ❌ **No Personal Data**: No names, emails, or other personal information collected

### Data Security
- **Local Encryption**: All authentication data is encrypted using Windows Data Protection API
- **Direct Downloads**: Photos transfer directly from SmugMug to your computer (no intermediary servers)
- **Secure Authentication**: Uses SmugMug's official OAuth 1.0a authentication system
- **No Cloud Storage**: Everything stays on your local machine

### Revoking Access
You can revoke WinMug's access to your SmugMug account anytime:

**In WinMug:**
1. Click the **"Logout"** button to remove local authentication

**In SmugMug:**
1. Log in to your SmugMug account
2. Go to **Account Settings** → **Privacy**
3. Find **"WinMug"** in authorized applications
4. Click **"Revoke Access"**

### Privacy Policy
For complete details about data handling, see our full Privacy Policy included with the application and available on our website.

## Support and Help

### Getting Help
1. **Check this User Guide**: Most common questions are answered here
2. **Application Logs**: Look at the log messages in WinMug for specific error details
3. **Microsoft Store Reviews**: Check recent reviews for known issues and solutions
4. **Contact Support**: Use the contact information provided with your purchase

### Before Contacting Support
Please try these steps first:
- Restart the application
- Check your internet connection
- Verify you have sufficient disk space
- Try re-authenticating with SmugMug
- Check the application logs for error messages

### Reporting Problems
When contacting support, please include:
- **WinMug Version**: Found in the application's About section
- **Windows Version**: Your operating system version
- **Error Description**: What you were trying to do when the error occurred
- **Error Messages**: Any specific error messages from the application
- **Library Size**: Approximate number of photos/albums in your SmugMug account
- **Log Files**: Copy relevant error messages from the application logs

### Response Time
- **Email Support**: We aim to respond within 24-48 hours
- **Critical Issues**: Priority support for authentication or major functionality problems
- **Feature Requests**: We welcome suggestions for future updates

## Frequently Asked Questions

### General Questions

**Q: Is WinMug worth $7.99?**
A: WinMug provides professional-grade photo backup capabilities that would typically cost much more. Consider the value of your photo collection and the time saved versus manual downloading.

**Q: How long will downloads take?**
A: Download time depends on your library size and internet speed:
- Small libraries (< 1,000 photos): 30 minutes to 2 hours
- Medium libraries (1,000-10,000 photos): 2-12 hours
- Large libraries (> 10,000 photos): 12+ hours or multiple days
- Very large libraries (> 50,000 photos): May take several days

**Q: Will this use my SmugMug bandwidth?**
A: Yes, downloads count against any bandwidth limits on your SmugMug plan. Most personal plans have generous or unlimited bandwidth.

**Q: Can I download just specific albums?**
A: Yes! WinMug shows all your albums in a tree view where you can select/deselect specific albums before downloading.

**Q: What if I add new photos to SmugMug later?**
A: Simply run WinMug again - it will skip existing files and only download new photos, making it perfect for regular backups.

**Q: Does this work with all SmugMug account types?**
A: Yes! WinMug works with all SmugMug plans: Basic, Power, Portfolio, and Business.

### Technical Questions

**Q: Is WinMug safe and secure?**
A: Absolutely! WinMug uses SmugMug's official OAuth authentication system. Your password is never stored, and all data stays on your computer.

**Q: What's the difference between "Public" and "Full" access?**
A:
- **Public Access**: Only downloads publicly visible photos/albums
- **Full Access**: Downloads your entire library including private content
- WinMug requests "Full" access to ensure complete backup capability

**Q: How do I verify I have the correct access level?**
A: After authentication, check the application logs. You should see "✓ Private access verified" confirming full access to your library.

**Q: Can I pause large downloads?**
A: Yes! WinMug includes pause/resume functionality, perfect for managing large downloads over multiple sessions.

**Q: What file formats are supported?**
A: WinMug downloads all file types supported by SmugMug: JPG, PNG, GIF, TIFF, RAW files (CR2, NEF, etc.), and videos (MP4, MOV, etc.).

**Q: What is the CSV metadata export?**
A: WinMug can create a CSV file for each album containing all photo metadata (titles, captions, keywords, GPS coordinates, dates, and direct SmugMug links). This is useful for:
- Importing metadata into other photo management software
- Creating searchable photo databases
- Preserving SmugMug organization information

**Q: Does metadata embedding work for all image formats?**
A: WinMug supports metadata embedding for most formats:
- **Full support**: JPEG, PNG, TIFF, WebP, GIF
- **Full support**: HEIC/HEIF (Apple format)
- **Read-only**: RAW files (CR2, NEF, ARW, etc.) - these are preserved unmodified
- **Limited**: Videos (some metadata may be embedded)

**Q: Why aren't GPS coordinates showing for some photos?**
A: GPS coordinates are only included when:
- The original photo has GPS data from the camera or phone
- The GPS data was added in SmugMug
- SmugMug returns Latitude=0, Longitude=0 when no location is set, which WinMug correctly ignores

**Q: Can I download individual photos instead of entire albums?**
A: Yes! Click "View" on any album to see its photos, then click individual photos to select them. Selected photos are added to your download queue alongside any full albums you've selected.

### Licensing and Updates

**Q: Is this a one-time purchase?**
A: Yes! $7.99 gives you lifetime access to WinMug with free updates through the Microsoft Store.

**Q: How do I get updates?**
A: Updates are delivered automatically through the Microsoft Store when available.

**Q: Can I install on multiple computers?**
A: Yes, you can install WinMug on any Windows computer where you're signed in with the same Microsoft account used for purchase.

---

## Credits & Third-Party Licenses

WinMug is built with the help of several excellent open-source projects. We gratefully acknowledge and thank their creators:

### ExifTool by Phil Harvey
- **License**: GNU GPL v3 (GNU General Public License)
- **Website**: [https://exiftool.org/](https://exiftool.org/)
- **Source Code**: [https://github.com/exiftool/exiftool](https://github.com/exiftool/exiftool)
- **Usage in WinMug**: Reading and writing metadata in image files (JPEG, PNG, HEIC, RAW, and more)

ExifTool is an industry-standard tool for reading and writing metadata in virtually every image format. WinMug bundles ExifTool and calls it as an external executable to provide comprehensive metadata embedding support.

### SixLabors.ImageSharp
- **License**: Apache License 2.0
- **Source Code**: [https://github.com/SixLabors/ImageSharp](https://github.com/SixLabors/ImageSharp)
- **Usage in WinMug**: Cross-platform image processing library

### CommunityToolkit.Mvvm
- **License**: MIT License
- **Source Code**: [https://github.com/CommunityToolkit/dotnet](https://github.com/CommunityToolkit/dotnet)
- **Usage in WinMug**: Modern MVVM framework for the WPF application

### Microsoft.Extensions.*
- **License**: MIT License
- **Usage in WinMug**: Dependency injection, configuration, logging, and hosting infrastructure

### Serilog
- **License**: Apache License 2.0
- **Source Code**: [https://github.com/serilog/serilog](https://github.com/serilog/serilog)
- **Usage in WinMug**: Diagnostic logging for troubleshooting and error reporting

---

## Version History

### Version 1.0.6 (Current)
- **NEW**: CSV metadata export with SmugMug links for each photo
- **NEW**: Metadata embedding using ExifTool (supports PNG, HEIC, RAW, and more)
- **NEW**: Individual photo selection within albums
- **IMPROVED**: GPS coordinate validation (ignores invalid 0,0,0 coordinates)
- **IMPROVED**: Performance optimization for albums with 500+ photos
- **FIXED**: Metadata embedding now works for full gallery downloads (not just individual photos)

### Version 1.0.5
- Unified download process for photos and albums
- Enhanced photo selection and download features
- UI improvements for compact design

### Version 1.0.0
- Initial release
- Complete SmugMug library download
- OAuth 1.0a authentication
- Folder structure preservation
- Progress tracking and pause/resume

---

**WinMug** | Copyright © 2025 YVCode Apps | All Rights Reserved

*SmugMug is a trademark of SmugMug, Inc. WinMug is not affiliated with or endorsed by SmugMug, Inc.*
