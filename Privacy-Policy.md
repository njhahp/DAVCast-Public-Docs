# DAVCast Privacy Policy

Effective date: 2026-08-05

DAVCast is an iPhone and iPad app for connecting to WebDAV servers, browsing files, playing media, previewing documents, and casting supported content to external devices.

## Summary

DAVCast is designed to minimize data collection.

- Server passwords are stored in the device Keychain.
- App settings and library metadata such as playlists, favorites, and server configuration metadata are stored on the device.
- DAVCast connects to WebDAV servers that you configure in order to browse and play your content.
- DAVCast may access the local network to discover or cast to AirPlay or DLNA-compatible devices.
- DAVCast uses App Store purchase APIs to manage subscriptions.

## Information DAVCast processes

### Information you provide

When you configure DAVCast, you may provide:

- Server name
- Server URL and path
- Username
- Password

This information is used only to connect to the WebDAV server you configured.

### Information stored on device

DAVCast stores the following locally on your device:

- WebDAV server configuration metadata
- Playback settings
- Playlist data
- Favorite items and folders
- Subscription state cached from App Store entitlements

Passwords are stored in Apple Keychain. Other app settings and content metadata are stored locally using system storage such as UserDefaults.

### Network activity

DAVCast connects to:

- WebDAV servers that you explicitly configure
- Local-network playback targets when you use AirPlay or DLNA features
- Apple services required for subscription purchase, restore, and entitlement refresh

## What DAVCast does not do

Based on the current implementation, DAVCast does not include its own analytics, advertising SDKs, or custom crash-reporting SDKs.

DAVCast does not intentionally send your WebDAV credentials to unrelated third-party hosts. The app uses a clean playback URL plus an Authorization header by default and avoids attaching authorization headers to cross-host URLs.

## Credential handling

- Passwords are stored in Keychain.
- Playlist and favorite URLs are sanitized to avoid persisting embedded credentials.
- Authorization headers are attached only for trusted same-origin media URLs.
- Credentialed cast URLs are generated only for supported casting scenarios.

## Third-party services

DAVCast relies on Apple platform services such as:

- App Store / StoreKit for subscriptions and purchase restoration
- Keychain for secure password storage
- System media, document preview, and networking frameworks

If future versions add analytics, crash reporting, or other third-party services, this policy should be updated before release.

## Data retention and control

Because DAVCast stores most app data locally on your device, you can remove stored data by:

- Deleting server configurations inside the app
- Removing playlists and favorites inside the app
- Deleting the app from your device

Subscription transactions are handled by Apple and may remain subject to Apple's records and policies.

## Children's privacy

DAVCast is not directed to children under 13, and the app is not designed to knowingly collect personal information from children.

## Changes to this policy

This Privacy Policy may be updated if DAVCast features or data practices change. The published version should always reflect the behavior of the current App Store release.

## Contact and support

For support or privacy questions, use the support channel published with DAVCast in its public project page or App Store listing.
