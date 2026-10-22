Shieldora

**Created by busareddyVineelKumarreddy**

Shieldora is a Flutter application that provides simple, on-device checks for suspicious messages and web addresses. It highlights common warning signs and explains why text may deserve a closer look.

## About the name and logo

Shieldora's visual identity is based on an aspirational idea of digital protection: a glossy blue glass shield paired with a green checkmark. The shield represents security, while the checkmark suggests confidence and reassurance. The blue-and-green palette gives the app a clear, modern safety theme. The supplied image is used as the Android launcher icon.

## Features

- Check pasted messages for common scam warning signs, such as pressure tactics, unexpected rewards, requests for credentials, shortened links, and numeric codes associated with OTP wording.
- Inspect a URL for basic structural warning signs, including IP-address hosts, unusually deep subdomains, and non-HTTPS addresses.
- Show a low, medium, or high risk level, a score, and the reasons that contributed to the result.
- View recent checks and session activity in the dashboard and history screens.
- Review privacy information in the app.

## Privacy and limitations

The checks are rule-based and run locally on the device. This version does not send scan content over the network, request SMS or contacts access, or save scan history after the app session ends.

Shieldora is an awareness aid, not a guarantee that a message or website is safe or malicious. Its local rules can miss new scams or flag legitimate content. Verify important requests through an official channel and check a website's domain before entering personal information.

## Technology

- **Dart** for the Flutter application and its local scanning logic
- **Flutter** and Material 3 for the user interface
- **Kotlin** for the Android activity shell
- **Gradle Kotlin DSL** for Android build configuration

**Release signing:** The current Android Gradle configuration uses debug signing for the release build. Set up your own release signing key before distributing a production APK.

## Project details

- App display name: **Shieldora**
- Version: **1.0.0+1**
- Android launcher icon: supplied blue glass shield with green checkmark artwork
- Scan history: kept in memory for the current app session only
