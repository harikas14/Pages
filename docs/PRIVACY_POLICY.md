# WinMug Privacy Policy

**Effective Date:** January 2025  
**Version:** 1.0

## Overview

WinMug is a desktop application that helps you download your photos from SmugMug to your local computer. This privacy policy explains how WinMug handles your data and protects your privacy.

## Information We Collect

### Authentication Data
- **SmugMug Access Tokens**: Securely stored OAuth tokens that allow the app to access your SmugMug account
- **User Nickname**: Your SmugMug username for display purposes
- **Authentication Timestamps**: When you last authenticated with SmugMug

### Application Settings
- **Target Directory**: The folder path where you choose to save your photos
- **Download Preferences**: Your settings for organizing downloaded photos
- **Application Logs**: Technical logs for troubleshooting (no personal data)

### What We DON'T Collect
- ❌ **Passwords**: Your SmugMug password is never stored or transmitted to us
- ❌ **Photo Content**: Your photos are downloaded directly from SmugMug to your computer
- ❌ **Personal Information**: No names, addresses, emails, or other personal details
- ❌ **Usage Analytics**: No tracking of how you use the application
- ❌ **Telemetry**: No data is sent to external servers

## How We Use Your Information

### Local Storage Only
- All data is stored locally on your computer
- No information is transmitted to our servers
- No cloud storage or external databases are used

### Authentication Purpose
- OAuth tokens are used solely to authenticate with SmugMug's API
- Tokens allow the app to download your photos on your behalf
- Authentication data is encrypted using Windows Data Protection API

### Application Functionality
- Settings are stored to remember your preferences
- Logs are created for troubleshooting technical issues
- All data remains on your local machine

## Data Storage and Security

### Local Encryption
- OAuth tokens are encrypted using Windows Data Protection API (DPAPI)
- Encryption keys are tied to your Windows user account
- Only you can decrypt the stored authentication data

### Storage Location
- Authentication data: `%APPDATA%\Winmug\credentials.dat` (encrypted)
- Application settings: Local application data folder
- Logs: Local application data folder (temporary)

### Data Retention
- Authentication tokens: Stored until you logout or revoke access
- Settings: Stored until you uninstall the application
- Logs: Automatically cleaned up periodically

## Third-Party Services

### SmugMug Integration
- WinMug connects directly to SmugMug's official API
- Authentication uses SmugMug's OAuth 1.0a system
- Your photos are downloaded directly from SmugMug to your computer
- No intermediary servers or services are used

### No Other Third Parties
- No analytics services (Google Analytics, etc.)
- No crash reporting services
- No advertising networks
- No social media integrations

## Your Rights and Controls

### Access Control
- You control what photos are downloaded
- You choose where photos are saved on your computer
- You can pause, resume, or cancel downloads at any time

### Revoking Access
You can revoke WinMug's access to your SmugMug account:
1. **In WinMug**: Click "Logout" to remove local authentication
2. **In SmugMug**: Go to Account Settings → Privacy → Authorized Applications → Revoke "WinMug"

### Data Deletion
- **Uninstall**: Removes the application and most data
- **Manual Cleanup**: Delete `%APPDATA%\Winmug` folder to remove all traces
- **SmugMug**: Revoke access to prevent future authentication

## Children's Privacy

WinMug is not directed at children under 13. We do not knowingly collect personal information from children. If you are under 13, please do not use this application.

## Changes to This Policy

We may update this privacy policy to reflect changes in the application or legal requirements. Updates will be posted with the application and on our website.

## Data Processing Legal Basis

### For Users in the European Union
We process your data based on:
- **Legitimate Interest**: To provide the photo downloading service you requested
- **Consent**: You explicitly authorize access to your SmugMug account
- **Contract Performance**: To fulfill the service of downloading your photos

## Contact Information

If you have questions about this privacy policy or data handling:

- **Email**: WinMug@icloud.com
- **Website**: https://github.com/harikas14/Pages/blob/main/docs/WinMug-UserGuide.md
- **GitHub**: [(https://github.com/harikas14/Pages/blob/main/docs/WinMug-UserGuide.md)]

## Compliance

### Microsoft Store Requirements
This application complies with Microsoft Store privacy requirements:
- Clear disclosure of data collection and use
- Secure handling of user credentials
- No unauthorized data transmission
- User control over their data

### Industry Standards
- OAuth 1.0a authentication (industry standard)
- Windows Data Protection API for encryption
- No unnecessary permissions requested
- Transparent data handling practices

---

**Summary**: WinMug is designed with privacy in mind. Your photos and data stay on your computer. We only store the minimum information needed to download your photos from SmugMug, and everything is encrypted and stored locally.
