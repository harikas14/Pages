# SMugVault Privacy Policy

**Effective Date:** November 2025  
**Version:** 1.0  
**Last Updated:** November 2, 2025

## Overview

SMugVault is a native macOS application that helps you download your photos from SmugMug directly to your Mac. This privacy policy explains how SMugVault handles your data and protects your privacy in compliance with Apple's App Store guidelines and applicable privacy laws.

## Information We Collect

### Authentication Data
- **SmugMug OAuth Tokens**: Securely stored authentication tokens that allow the app to access your SmugMug account
- **User Nickname**: Your SmugMug username for display and identification purposes
- **Authentication Timestamps**: Records of when you last authenticated with SmugMug for session management
- **User Profile Information**: Basic profile data from SmugMug (display name, bio image) for app interface

### Application Settings and Preferences
- **Download Preferences**: Your settings for organizing and managing downloaded photos
- **Target Directory Paths**: Folder locations where you choose to save your photos
- **Application Configuration**: User interface preferences, window positions, and app settings
- **Download History**: Local records of completed downloads for progress tracking

### Technical and Diagnostic Information
- **Application Logs**: Technical logs for troubleshooting and error diagnosis (no personal data included)
- **Performance Metrics**: Local app performance data for optimization (not transmitted externally)
- **Error Reports**: Crash logs and error information stored locally for debugging

### What We DON'T Collect
- ❌ **Passwords**: Your SmugMug password is never stored, transmitted, or accessible to SMugVault
- ❌ **Photo Content Analysis**: We don't analyze, scan, or process the content of your photos
- ❌ **Personal Information**: No collection of names, addresses, emails, phone numbers, or other personal details
- ❌ **Usage Analytics**: No tracking of how you use the application or behavioral analytics
- ❌ **Telemetry Data**: No data is transmitted to external servers or third-party analytics services
- ❌ **Location Data**: No access to or collection of location information
- ❌ **Device Information**: No collection of device identifiers, hardware specifications, or system information

## How We Use Your Information

### Local Processing Only
- All data processing occurs locally on your Mac
- No information is transmitted to SMugVault servers (we don't operate any servers)
- No cloud storage or external databases are used for your personal data
- Your photos are downloaded directly from SmugMug to your chosen local directories

### Authentication and API Access
- OAuth tokens are used exclusively to authenticate with SmugMug's official API
- Tokens enable the app to access your SmugMug albums and photos on your behalf
- Authentication data is encrypted and stored securely in macOS Keychain
- Profile information is used solely for displaying your identity within the app interface

### Application Functionality
- Settings and preferences are stored locally to remember your choices between app sessions
- Download history helps track progress and prevent duplicate downloads
- Technical logs assist in troubleshooting issues and improving app stability
- All functionality data remains on your local machine and is never transmitted externally

## Data Storage and Security

### macOS Keychain Integration
- OAuth tokens and sensitive authentication data are encrypted using macOS Keychain Services
- Encryption keys are managed by macOS and tied to your user account
- Only SMugVault and your user account can access the stored authentication data
- Keychain data is protected by macOS security features and your login credentials

### Local Storage Locations
- **Authentication Data**: Securely stored in macOS Keychain (encrypted)
- **Application Settings**: `~/Library/Application Support/SMugVault/` (local preferences)
- **Download Records**: Local application data folder (temporary tracking data)
- **Application Logs**: `~/Library/Logs/SMugVault/` (technical logs, automatically cleaned)

### Data Retention and Cleanup
- **Authentication Tokens**: Stored until you logout, revoke access, or uninstall the app
- **Application Settings**: Retained until you uninstall SMugVault or manually reset preferences
- **Download History**: Automatically cleaned periodically to prevent excessive storage usage
- **Technical Logs**: Automatically rotated and cleaned to maintain reasonable storage footprint

### Security Measures
- **App Sandbox**: SMugVault runs in Apple's App Sandbox for enhanced security isolation
- **Hardened Runtime**: Enabled for additional protection against code injection and tampering
- **Code Signing**: Application is signed with Apple Developer certificates for authenticity
- **Minimal Permissions**: Only requests necessary permissions for core functionality

## Third-Party Services and Integrations

### SmugMug API Integration
- SMugVault connects exclusively to SmugMug's official API endpoints
- Authentication uses SmugMug's standard OAuth 1.0a security protocol
- Your photos are downloaded directly from SmugMug's servers to your Mac
- No intermediary servers, proxies, or caching services are used in the download process
- All communication with SmugMug is encrypted using HTTPS/TLS

### No Other Third-Party Services
- **No Analytics Services**: No integration with Google Analytics, Mixpanel, or similar services
- **No Crash Reporting**: No automatic crash reporting to external services (Crashlytics, Sentry, etc.)
- **No Advertising Networks**: No ads, tracking pixels, or advertising-related integrations
- **No Social Media**: No integration with social media platforms or sharing services
- **No Cloud Services**: No use of external cloud storage or processing services

## Your Rights and Privacy Controls

### Access and Control
- **Download Selection**: You have complete control over which photos and albums to download
- **Storage Location**: You choose where photos are saved on your Mac
- **Download Management**: Pause, resume, or cancel downloads at any time
- **Authentication Control**: Login and logout from your SmugMug account as desired

### Data Access and Portability
- **Local Access**: All your data is stored locally and accessible through standard macOS file operations
- **Export Capability**: Downloaded photos are in standard formats and fully portable
- **Settings Export**: Application preferences can be backed up through macOS standard mechanisms
- **No Vendor Lock-in**: Your data remains in open, standard formats

### Revoking Access and Data Deletion
You can revoke SMugVault's access to your SmugMug account through multiple methods:

1. **Within SMugVault**: Use the "Logout" or "Disconnect Account" feature to remove local authentication
2. **SmugMug Account Settings**: 
   - Log into SmugMug.com
   - Go to Account Settings → Privacy → Authorized Applications
   - Find "SMugVault" and click "Revoke Access"
3. **Complete Data Removal**:
   - Uninstall SMugVault from Applications folder
   - Manually delete `~/Library/Application Support/SMugVault/` for complete cleanup
   - Keychain data is automatically removed when the app is uninstalled

## Children's Privacy (COPPA Compliance)

SMugVault is not specifically directed at children under 13 years of age. We do not knowingly collect, use, or disclose personal information from children under 13. If you are under 13 years of age, please do not use SMugVault without parental supervision and consent.

If we become aware that we have inadvertently collected personal information from a child under 13, we will take steps to delete such information promptly.

## International Data Transfers and Regional Compliance

### For Users in the European Union (GDPR)
We process your data based on the following legal bases:
- **Legitimate Interest**: To provide the photo downloading service you explicitly requested
- **Consent**: You explicitly authorize access to your SmugMug account through OAuth
- **Contract Performance**: To fulfill our obligation to provide the photo downloading service

**Your GDPR Rights**:
- **Right to Access**: All data is stored locally and accessible to you
- **Right to Rectification**: You can modify settings and preferences within the app
- **Right to Erasure**: Uninstall the app or use logout features to remove data
- **Right to Data Portability**: Your photos are downloaded in standard, portable formats
- **Right to Object**: You can revoke access or stop using the service at any time

### For Users in California (CCPA)
Under the California Consumer Privacy Act, you have the right to:
- Know what personal information is collected (detailed in this policy)
- Delete personal information (through app uninstall and logout features)
- Opt-out of sale of personal information (we don't sell any personal information)
- Non-discrimination for exercising your privacy rights

## Changes to This Privacy Policy

We may update this privacy policy periodically to reflect:
- Changes in SMugVault's functionality or features
- Updates to applicable privacy laws and regulations
- Improvements to our privacy practices and security measures

**Notification of Changes**:
- Updated policies will be included with app updates
- Significant changes will be highlighted in app release notes
- The "Last Updated" date at the top of this policy will reflect the most recent changes
- Continued use of SMugVault after policy updates constitutes acceptance of the changes

## Data Processing Transparency

### Automated Decision Making
SMugVault does not use automated decision-making or profiling that would significantly affect users. All processing is straightforward data transfer and storage as explicitly requested by the user.

### Data Minimization
We adhere to data minimization principles by:
- Collecting only data necessary for core app functionality
- Storing data locally rather than on external servers
- Automatically cleaning up temporary and log data
- Providing users with granular control over data retention

## Contact Information and Support

If you have questions, concerns, or requests regarding this privacy policy or SMugVault's data handling practices:

**Primary Contact**:
- **Email**: winmug@icloud.com
- **Support Email**: winmug@icloud.com

**Additional Resources**:
- **Documentation**: https://github.com/harikas14/Pages/blob/main/docs/SMugVault-UserGuide.md
- **FAQ**: https://github.com/harikas14/Pages/blob/main/docs/SMugVault-faq.md

**Response Time**: We aim to respond to privacy-related inquiries within 72 hours.

## Compliance and Certifications

### Apple App Store Requirements
SMugVault complies with Apple's App Store Review Guidelines including:
- Clear and accurate privacy disclosures
- Secure handling of user credentials and data
- No unauthorized data collection or transmission
- User control and transparency over data usage
- Proper implementation of App Sandbox and security features

### Industry Standards and Best Practices
- **OAuth 1.0a**: Industry-standard authentication protocol
- **macOS Keychain**: Apple's recommended secure storage system
- **HTTPS/TLS**: Encrypted communication with SmugMug API
- **App Sandbox**: Apple's security isolation technology
- **Minimal Permissions**: Principle of least privilege for system access

### Security Frameworks
- Follows Apple's Secure Coding Guidelines
- Implements macOS security best practices
- Regular security reviews and updates
- Transparent security practices and disclosures

---

## Privacy Policy Summary

**SMugVault is designed with privacy as a fundamental principle**:

✅ **Local-First**: Your data stays on your Mac  
✅ **No Tracking**: No analytics, telemetry, or behavioral tracking  
✅ **Secure Storage**: Authentication data encrypted in macOS Keychain  
✅ **User Control**: Complete control over downloads and data  
✅ **Transparent**: Clear disclosure of all data handling practices  
✅ **Compliant**: Meets Apple App Store and international privacy requirements  

**Bottom Line**: MacSMug helps you download your SmugMug photos to your Mac while keeping your data private, secure, and under your complete control.
