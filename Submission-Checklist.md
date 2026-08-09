# DAVCast App Store Submission Checklist

## Public links

- Publish a Support URL
- Publish a Privacy Policy URL
- Publish a Terms of Use URL if subscriptions are offered
- Confirm all public pages are reachable without login

## App Store Connect metadata

- App name, subtitle, description, keywords, categories
- Support URL
- Marketing URL if used
- Privacy Policy URL
- Terms of Use (EULA) URL if subscriptions are offered
- **If using the Apple standard EULA: include the standard EULA link (`https://www.apple.com/legal/internet-services/itunes/dev/stdeula/`) in the App Description for every localized description** (App Review Guideline 3.1.2 requires a functional link to the Terms of Use in app metadata)
- App Review notes
- Screenshots for required device classes
- App icon and age rating

## App privacy disclosure

- Fill App Privacy in App Store Connect
- Reflect local credential storage in Keychain
- Reflect WebDAV network access
- Reflect local-network usage for AirPlay / DLNA device discovery and casting
- Reflect subscription and purchase processing through Apple
- Confirm whether any analytics or crash SDKs are present before submission

## Subscription setup

- Verify product IDs match the app code:
  - `davcast.pro.monthly`
  - `davcast.pro.yearly`
- Verify subscription group naming and localization
- Verify trial configuration for the yearly plan
- Verify price and storefront availability
- Verify Restore Purchases and entitlement refresh flow
- Verify in-app Terms of Use and Privacy Policy links work (paywall and Settings)

## Technical checks

- Confirm `NSLocalNetworkUsageDescription` text is accurate
- Confirm background audio behavior is intended
- Test same-origin authorization handling
- Test playlist and favorite URL sanitization
- Test with at least one real WebDAV server
- Test AirPlay / DLNA on the same local network

## Review package

- Provide reviewer test steps
- Provide demo content and sample files when needed
- Explain subscription gating clearly in review notes
- Explain that server passwords are stored in Keychain
- Explain that playlist and favorite URLs are sanitized to avoid embedded credentials

## Release readiness

- Re-run unit tests
- Re-check localized strings for purchase and subscription copy
- Re-check screenshots against the current UI
- Re-check privacy policy against the current implementation
