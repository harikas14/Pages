# SMugAegis 📸

**The Ultimate SmugMug Photo Downloader for Mac**

[![macOS](https://img.shields.io/badge/macOS-13.0+-blue.svg)](https://www.apple.com/macos/)
[![Swift](https://img.shields.io/badge/Swift-6.0-orange.svg)](https://swift.org/)
[![SwiftUI](https://img.shields.io/badge/SwiftUI-Native-green.svg)](https://developer.apple.com/swiftui/)
[![License](https://img.shields.io/badge/License-Proprietary-red.svg)](LICENSE)

SMugAegis is a native macOS application that allows you to download your entire SmugMug photo library while preserving folder structure and original quality. Built with modern SwiftUI and optimized for macOS 13+, SMugAegis provides a seamless, professional experience for managing your photo downloads.

![SMugAegis Screenshot](SMugAegis/Resources/SMugAegisStory.jpeg)
![SMugAegis Screenshot](SMugAegis/Resources/SMugAegis-Welcome-Page1.png)
![SMugAegis Screenshot](SMugAegis/Resources/SMugAegis-OAUTH-Page.png)
![SMugAegis Screenshot](SMugAegis/Resources/SMugAegis-Page3.png)
![SMugAegis Screenshot](SMugAegis/Resources/SMugAegis-Dwnld-Prgrs-Page.png)
![SMugAegis Screenshot](SMugAegis/Resources/SMugAegis-Dwnlod-Status-Page.png)

## ✨ Features

### 📸 **Complete Library Access**
- Browse your entire SmugMug library with intuitive navigation
- Folder and album hierarchy preservation
- Search functionality across all photos and albums
- Grid and list view modes for optimal browsing

### ⚡ **Intelligent Download Management**
- Concurrent downloads with real-time progress tracking
- Resume interrupted downloads automatically
- Organize downloads by folder structure
- Original quality preservation
- Background download support

### 🔐 **Secure Authentication**
- OAuth 1.0a secure authentication with SmugMug
- Credentials stored safely in macOS Keychain
- No third-party data sharing
- Privacy-first design

### 🎨 **Native macOS Experience**
- Modern SwiftUI interface optimized for macOS
- Sidebar navigation with familiar macOS patterns
- Dark mode and light mode support
- Accessibility features including VoiceOver support
- Keyboard navigation and shortcuts

### 🚀 **Professional Performance**
- Optimized for large photo libraries
- Memory-efficient browsing and downloading
- Real-time progress indicators
- Error handling and retry mechanisms
- Automatic folder organization

## 🛠 Requirements

- **macOS:** 13.0 (Ventura) or later
- **Architecture:** Apple Silicon (M1/M2/M3) or Intel
- **Storage:** 50MB for app + space for downloaded photos
- **Network:** Internet connection for SmugMug access
- **Account:** Active SmugMug account

## 📦 Installation

### From Mac App Store (Recommended)
1. Open the Mac App Store
2. Search for "SMugAegis"
3. Click "Get" or purchase for $9.99
4. The app will download and install automatically


## 🚀 Quick Start

1. **Launch SMugAegis** from your Applications folder
2. **Sign in** with your SmugMug account using the secure OAuth flow
3. **Browse** your photo library using the sidebar navigation
4. **Select** photos or albums you want to download
5. **Click Download** and choose your destination folder
6. **Monitor progress** in the Downloads tab

For detailed instructions, see the [User Guide](UserGuide.md).

## 🏗 Development

### Prerequisites
- Xcode 15.0 or later
- Swift 6.0
- macOS 13.0+ SDK

### Building from Source

```bash
# Clone the repository
git clone https://github.com/smugaegis/SMugAegis.git
cd SMugAegis

# Build with Swift Package Manager
swift build

# Run the application
swift run

# Or open in Xcode
open SMugAegis.xcodeproj
```

### Project Structure

```
SMugAegis/
├── Sources/
│   ├── Authentication/     # OAuth 1.0a implementation
│   ├── Models/            # Data models (User, Node, Image)
│   ├── Services/          # API client and download manager
│   ├── ViewModels/        # MVVM view models
│   └── Views/             # SwiftUI views and components
├── Resources/
│   ├── AppIcon.swift      # App icon generator
│   ├── Localizable.strings # Localization
│   └── Screenshots/       # App Store assets
├── Tests/                 # Unit and integration tests
└── Scripts/               # Build and validation scripts
```

### Running Tests

```bash
# Run all tests
swift test

# Run specific test suite
swift test --filter SMugAegisTests

# Run validation script
swift Scripts/validate_app.swift
```

## 🔧 Configuration

SMugAegis stores its configuration in the following locations:

- **Credentials:** macOS Keychain (secure)
- **Preferences:** `~/Library/Preferences/com.smugaegis.SMugAegis.plist`
- **Downloads:** User-selected folder (default: `~/Downloads/SmugMug`)

## 🛡 Privacy & Security

SMugAegis is designed with privacy as a core principle:

- **No Data Collection:** We don't collect any personal information
- **Local Storage:** All photos are stored locally on your Mac
- **Secure Authentication:** OAuth tokens stored in macOS Keychain
- **No Tracking:** No analytics or tracking mechanisms
- **Open Source:** Core functionality is transparent and auditable

For complete details, see our [Privacy Policy](PRIVACY.md).

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guidelines](CONTRIBUTING.md) for details.

### Development Workflow

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Make your changes
4. Add tests for new functionality
5. Ensure all tests pass (`swift test`)
6. Commit your changes (`git commit -m 'Add amazing feature'`)
7. Push to the branch (`git push origin feature/amazing-feature`)
8. Open a Pull Request

## 📋 Roadmap

### Version 1.1 (Planned)
- [ ] Advanced keyboard shortcuts
- [ ] Batch operations for large libraries
- [ ] Custom download presets
- [ ] Enhanced search filters

### Version 1.2 (Future)
- [ ] Multi-account support
- [ ] Automated backup scheduling
- [ ] Photo metadata editing
- [ ] Integration with Photos app

## 🐛 Support

### Getting Help

1. **User Guide:** Check our comprehensive [User Guide](UserGuide.md)
2. **FAQ:** Browse [Frequently Asked Questions](https://github.com/harikas14/Pages/blob/main/docs/SMugAegis-FAQ.md)
4. **Email:** Contact us at [winmug@icloud.com](mailto:support@smugaegis.app)

### Known Issues

- Large libraries (10,000+ photos) may require additional memory
- Multi-monitor setups need additional testing
- Some SmugMug private galleries may have access limitations

## 📄 License

SMugAegis is proprietary software. See [LICENSE](LICENSE) for details.

## 🙏 Acknowledgments

- **SmugMug** for providing an excellent API
- **Apple** for the SwiftUI framework
- **Swift Community** for amazing tools and libraries
- **Beta Testers** who helped make SMugAegis better

## 📞 Contact

- **Email:** [winmug@icloud.com](mailto:winmug@icloud.com)
- **Support:** [winmug@icloud.com](mailto:winmug@icloud.com)

---

**Made with ❤️ for the Mac and SmugMug communities**

*SMugAegis is not affiliated with SmugMug, Inc. SmugMug is a trademark of SmugMug, Inc.*
