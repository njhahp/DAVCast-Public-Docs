---
layout: page
title: Privacy Policy
permalink: /privacy-policy
---

# DAVCast Privacy Policy

Effective date: 2026-08-05

DAVCast is designed to minimize data collection while allowing you to connect to your own WebDAV servers, manage files (upload/download/create folder/rename/move/delete), and play or preview your media.

## Summary

- Server passwords are stored in Apple Keychain
- App settings, playlists, favorites, and server metadata are stored locally on device
- DAVCast connects only to servers and devices you configure or use
- DAVCast may use local-network access to discover or cast to AirPlay or DLNA devices
- DAVCast uses Apple App Store services to handle subscriptions
- DAVCast can transfer files only between your device and your configured WebDAV server when you use upload or download actions

## Information DAVCast processes

When you configure DAVCast, you may provide:

- Server name
- Server URL and path
- Username
- Password

This information is used to connect to the WebDAV server you configured.

## Storage and credential handling

- Passwords are stored in Apple Keychain
- Other app data is stored locally on your device
- Playlist and favorite URLs are sanitized to avoid storing embedded credentials
- Authorization headers are attached only for trusted same-origin media URLs

## What DAVCast does not do

Based on the current implementation, DAVCast does not include its own analytics SDK, advertising SDK, or custom crash-reporting SDK.

## Third-party services

DAVCast relies on Apple system services such as:

- App Store and StoreKit for subscriptions
- Keychain for password storage
- System frameworks for media playback, document preview, and networking

## Control and deletion

You can remove local data by deleting server configurations, playlists, favorites, or the app itself from your device.

## Contact

For privacy questions, use the public project support channel:

- https://github.com/njhahp/DAVCast/issues
---

© 2026 DAVCast
