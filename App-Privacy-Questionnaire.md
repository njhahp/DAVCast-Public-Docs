# DAVCast App Privacy Questionnaire Answers

Ready-to-paste answers for the App Store Connect App Privacy questionnaire.
These reflect the current implementation; re-verify if the implementation changes.

## Data collection summary

- DAVCast does not collect, transmit, or share user data with third parties for analytics, advertising, or tracking.
- DAVCast does not include its own analytics SDK, advertising SDK, or custom crash-reporting SDK.
- Data entered by the user stays on-device (Keychain, UserDefaults) or is used only to reach the user's own WebDAV server.

## Questionnaire answers

### Contact Info

- Collected: No
- (If you later add a feedback/contact form that sends email, select "Yes — Not Linked to Identity".)

### Health & Fitness

- Collected: No

### Financial Info

- Collected: No (DAVCast never sees payment details; purchases are processed by Apple through StoreKit.)

### Location

- Collected: No

### Sensitive Info

- Collected: No

### Contacts

- Collected: No

### User Content

- Collected: No (server credentials are stored only in Keychain on the user's device; no user content is uploaded by DAVCast.)

### Browsing History

- Collected: No

### Search History

- Collected: No

### Identifiers

- Collected: No (no advertising identifier or vendor identifier usage; no tracking.)

### Purchases

- Collected: Yes — Not Linked to Identity
- DAVCast verifies the user's subscription entitlement with Apple (StoreKit) to unlock Pro features. DAVCast does not collect or store purchase history itself.

### Usage Data

- Collected: No

### Diagnostics

- Collected: No

## Local Network (not part of the privacy questionnaire, but relevant)

- DAVCast requests local network access only for AirPlay / DLNA device discovery and casting.
- `NSLocalNetworkUsageDescription` in `Info.plist` is set to:
  "DAVCast uses your local network to discover and cast to AirPlay / DLNA devices."