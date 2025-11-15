# SMugAegis - Frequently Asked Questions 🤔

**Quick answers to common questions about SMugAegis**

## 📋 Table of Contents

1. [General Questions](#general-questions)
2. [Pricing & Purchase](#pricing--purchase)
3. [System Requirements](#system-requirements)
4. [Authentication & Security](#authentication--security)
5. [Downloading & Performance](#downloading--performance)
6. [Troubleshooting](#troubleshooting)
7. [Support & Contact](#support--contact)

---

## 🌟 General Questions

### What is SMugAegis?
SMugAegis is a native macOS application that allows you to download your entire SmugMug photo library while preserving folder structure and original quality. It's built specifically for Mac users who want a seamless, professional experience for managing their SmugMug photo downloads.

### How is SMugAegis different from other photo downloaders?
- **Native macOS app** - Built with SwiftUI for true Mac experience
- **SmugMug specialized** - Designed specifically for SmugMug's API
- **Folder preservation** - Maintains your SmugMug organization
- **Original quality** - Always downloads highest resolution
- **Secure authentication** - OAuth 1.0a with Keychain storage
- **Professional interface** - Modern, intuitive design

### Is SMugAegis affiliated with SmugMug?
No, SMugAegis is an independent application created by third-party developers. We use SmugMug's official API but are not affiliated with SmugMug, Inc.

### Can I use SMugAegis with other photo services?
Currently, SMugAegis is designed exclusively for SmugMug. We may consider supporting other services in future versions based on user demand.

---

## 💰 Pricing & Purchase

### How much does SMugAegis cost?
SMugAegis is available for **$9.99** on the Mac App Store. This is a one-time purchase with no subscription fees.

### Is there a free trial?
Currently, SMugAegis doesn't offer a free trial. However, we offer a 30-day money-back guarantee through the Mac App Store if you're not satisfied.

### Are there any subscription fees?
No! SMugAegis is a one-time purchase. You pay $9.99 once and own the app forever, including free updates.

### Is there an educational discount?
Yes, SMugAegis participates in Apple's educational pricing program. Students and educators can get a discount through the Mac App Store.

### Can I use SMugAegis on multiple Macs?
Yes! Your Mac App Store purchase allows you to install SMugAegis on all Macs associated with your Apple ID.

---

## 💻 System Requirements

### What macOS version do I need?
SMugAegis requires **macOS 13.0 (Ventura) or later**. This ensures compatibility with the latest SwiftUI features and security standards.

### Does SMugAegis work on Intel Macs?
Yes! SMugAegis is a universal app that runs natively on both:
- **Apple Silicon** (M1, M2, M3 Macs)
- **Intel Macs** (x86_64 architecture)

### How much storage space do I need?
- **App size:** ~50MB for SMugAegis itself
- **Photo storage:** Depends on your SmugMug library size
- **Recommendation:** Ensure 2x your library size in free space

### What internet connection do I need?
- **Minimum:** Stable broadband connection
- **Recommended:** High-speed connection for large downloads
- **Note:** Download speed depends on your internet bandwidth

---

## 🔐 Authentication & Security

### How does SMugAegis access my SmugMug account?
SMugAegis uses **OAuth 1.0a**, the industry-standard secure authentication protocol. You sign in through SmugMug's official website, and they provide SMugAegis with secure access tokens.

### Does SMugAegis store my SmugMug password?
**No!** SMugAegis never sees or stores your SmugMug password. All authentication is handled securely through OAuth, and access tokens are stored in your Mac's Keychain.

### Is my data safe?
Absolutely! SMugAegis is designed with privacy as a core principle:
- **No data collection** - We don't collect any personal information
- **Local storage** - All photos are stored on your Mac
- **Secure tokens** - Access credentials stored in macOS Keychain
- **No tracking** - No analytics or tracking mechanisms

### Can I revoke SMugAegis's access?
Yes! You can revoke SMugAegis's access anytime by:
1. Signing into your SmugMug account
2. Going to Account Settings → Privacy
3. Removing SMugAegis from authorized applications

### What permissions does SMugAegis need?
SMugAegis only requests the minimum permissions needed:
- **Read access** to your SmugMug photos and albums
- **No write access** - SMugAegis cannot modify your SmugMug content
- **No sharing access** - SMugAegis cannot share your photos

---

## 📥 Downloading & Performance

### How fast are downloads?
Download speed depends on several factors:
- **Your internet connection** - Primary limiting factor
- **SmugMug's servers** - API rate limits and server load
- **Concurrent downloads** - SMugAegis downloads 3-5 photos simultaneously
- **Photo size** - Larger photos take longer

### Can I download my entire library at once?
Yes! SMugAegis can handle large libraries, but we recommend:
- **Start with smaller albums** to test your setup
- **Monitor available disk space** during large downloads
- **Use stable internet connection** for best results
- **Consider downloading in batches** for very large libraries (10,000+ photos)

### What happens if my download is interrupted?
SMugAegis automatically handles interruptions:
- **Resume capability** - Downloads continue where they left off
- **Retry logic** - Failed downloads are automatically retried
- **Error handling** - Clear error messages and recovery options
- **Progress preservation** - No need to start over

### Does SMugAegis preserve my folder structure?
Yes! SMugAegis maintains your SmugMug organization:
- **Folder hierarchy** - Exact same structure as SmugMug
- **Album names** - Preserved as folder names
- **File names** - Original filenames maintained
- **Metadata** - Photo information preserved

### Can I choose download quality?
SMugAegis always downloads the **highest quality available** (original resolution). This ensures you get the best possible version of your photos.

---

## 🔧 Troubleshooting

### SMugAegis won't start or crashes on launch
Try these solutions:
1. **Restart your Mac** and try again
2. **Check macOS version** - Ensure you have macOS 13.0+
3. **Reinstall SMugAegis** from the Mac App Store
4. **Check Console app** for error messages
5. **Contact support** if the problem persists

### I can't sign in to SmugMug
Common solutions:
1. **Check internet connection** - Ensure stable connectivity
2. **Try in browser first** - Verify SmugMug credentials work
3. **Clear browser cache** - Remove stored login data
4. **Disable VPN** - Some VPNs interfere with OAuth
5. **Check SmugMug status** - Verify SmugMug services are operational

### Downloads are slow or failing
Optimization tips:
1. **Check internet speed** - Run a speed test
2. **Reduce concurrent downloads** - Lower from 5 to 2-3
3. **Try smaller batches** - Download albums individually
4. **Use wired connection** - Ethernet is more stable than WiFi
5. **Close other apps** - Free up bandwidth and memory

### My photos aren't appearing in the library
Troubleshooting steps:
1. **Refresh the library** - Press Cmd+R or restart SMugAegis
2. **Check album privacy** - Ensure albums are accessible
3. **Verify SmugMug account** - Check account status and permissions
4. **Sign out and back in** - Refresh authentication tokens
5. **Check SmugMug directly** - Verify photos exist in your account

### SMugAegis is using too much memory
Performance optimization:
1. **Restart SMugAegis** - Clears memory caches
2. **Close other applications** - Free up system memory
3. **Download smaller batches** - Reduce memory pressure
4. **Check Activity Monitor** - Monitor system resources
5. **Restart your Mac** - Full system refresh

---

## 📞 Support & Contact

### How do I get help?
We offer multiple support channels:

1. **This FAQ** - Check here first for quick answers
2. **User Guide** - Comprehensive documentation at [UserGuide.md](https://github.com/harikas14/Pages/blob/main/docs/UserGuide.md)
3. **Email Support** - [support@smug vault.app](mailto:winmug@icloud.com)

### What information should I include when contacting support?
Please provide:
- **macOS version** - Found in Apple Menu → About This Mac
- **SMugAegis version** - Found in SMugAegis → About SMugAegis
- **Error messages** - Exact text of any error messages
- **Steps to reproduce** - What you were doing when the issue occurred
- **Screenshots** - If applicable, include relevant screenshots

### How quickly will I get a response?
We aim to respond to all support requests within:
- **Email support** - 24-48 hours
- **GitHub issues** - 1-3 business days
- **Critical bugs** - Same day when possible

### Can I request new features?
Absolutely! We love hearing from users. You can:
- **Email us** with feature requests
- **Create GitHub issues** for feature suggestions

## 🔄 Updates & Future

### How do I update SMugAegis?
SMugAegis updates automatically through the Mac App Store:
- **Automatic updates** - Enable in Mac App Store preferences
- **Manual check** - SMugAegis → Check for Updates (https://github.com/harikas14/Pages/blob/main/docs/SMugAegis-README.md)

### What's coming in future versions?
We're constantly improving SMugAegis. Planned features include:
- **Enhanced keyboard shortcuts** - More efficient navigation
- **Batch operations** - Advanced selection and download options
- **Custom presets** - Save download preferences
- **Performance improvements** - Better handling of large libraries

### How can I stay updated?
- **Watch our GitHub** - (https://github.com/harikas14/Pages/blob/main/docs/SMugAegis-README.md)

---

## ❓ Still Have Questions?

If you can't find the answer you're looking for:

1. **Search this FAQ** - Use Cmd+F to search for keywords
2. **Check the User Guide** - More detailed instructions
3. **Contact our support team** - We're here to help!

**We're committed to making SMugAegis the best SmugMug downloader for Mac, and your feedback helps us improve!**

---

*Last updated: September 26, 2025*  
