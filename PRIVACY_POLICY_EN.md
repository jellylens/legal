# Privacy Policy

**JellyLens - visionOS Media Player**

**Effective Date:** 2026-01-21
**Version:** 1.0

---

## 1. Data Controller

The data controller responsible for data processing under GDPR is:

**Thies Schneider**
Germany

**Email:** vision@jellylens.com

The full postal address (Impressum, § 5 DDG) is available in the app under Settings → Legal and on the App Store product page.

---

## 2. General Information

JellyLens is a client application for self-hosted Jellyfin media servers. The app processes data exclusively to provide the contractually agreed functions (connecting to your server, playing media, storing playback positions).

**Important:** JellyLens does not transmit any data to the developer or third parties. All data is exchanged exclusively between the app and your own Jellyfin server.

---

## 3. Legal Basis for Processing

Data processing is based on **Art. 6(1)(b) GDPR** (contract fulfillment). Data processing is necessary to provide the app functions that you use by using the app.

**No consent is required**, as processing is necessary for contract fulfillment.

---

## 4. What Data is Processed?

### 4.1 Server Connection Data
- **What:** Server URL, username, authentication token
- **Purpose:** Establish connection to your Jellyfin server
- **Storage Location:** Locally on your device (Keychain, encrypted)
- **Transmission:** Only to your own Jellyfin server

### 4.2 Playback Data
- **What:** Playback positions, progress, "watched" status
- **Purpose:** Synchronization between devices, resume playback
- **Storage Location:** Locally on your device (Core Data) + on your Jellyfin server
- **Transmission:** Only to your own Jellyfin server

### 4.3 User Preferences
- **What:** Language, subtitle settings, audio track preferences
- **Purpose:** Personalization of app functions
- **Storage Location:** Locally on your device (UserDefaults)
- **Transmission:** None

### 4.4 Network Data
- **What:** Local network connections (for server discovery)
- **Purpose:** Automatic discovery of Jellyfin servers on local network
- **Storage Location:** No persistent storage
- **Transmission:** Only broadcast on local network

---

## 5. To Whom is Data Transmitted?

**JellyLens transmits data exclusively to your own Jellyfin server.**

There is **no transmission** to:
- The developer (Thies Schneider)
- Apple (except standard iOS/visionOS system functions)
- Third parties
- Tracking services
- Analytics services
- Advertising networks

**You have full control:** All data transmitted by JellyLens to your server is subject to your own server configuration and privacy policy.

---

## 6. Storage Duration

- **Server connection data:** Until manual logout or app deletion
- **Playback data:** Until manual deletion or app deletion
- **User preferences:** Until manual reset or app deletion

**Data deletion:** When uninstalling the app, all locally stored data is automatically deleted from your device.

---

## 7. Your Rights (Data Subject Rights under GDPR)

You have the following rights regarding your personal data:

### 7.1 Right of Access (Art. 15 GDPR)
You have the right to obtain information about the data processed by the app.

**Implementation:** All data the app processes is listed in Section 4. It is held only on your device and on your own Jellyfin server — the developer holds no copy. Data on your server is fully accessible to you through your server's own interface.

### 7.2 Right to Rectification (Art. 16 GDPR)
You have the right to have incorrect data corrected.

**Implementation:** Edit your settings directly in the app or on your Jellyfin server.

### 7.3 Right to Erasure (Art. 17 GDPR)
You have the right to request deletion of your data.

**Implementation:**
- Local data: Settings → Legal → Delete All Data (signs you out and erases all local app data)
- Server data: manage or delete it directly on your own Jellyfin server

### 7.4 Right to Data Portability (Art. 20 GDPR)
You have the right to receive your data in a structured, machine-readable format.

**Implementation:** The app keeps no central copy of your data. Your media and playback data reside on your own Jellyfin server, from which you can export them using your server's own tools. Local app data can be erased via Settings → Legal → Delete All Data.

### 7.5 Right to Object (Art. 21 GDPR)
Since processing is based on contract fulfillment (Art. 6(1)(b) GDPR), objection is not possible as long as you wish to use the app. However, you can stop using the app at any time and delete your data.

---

## 8. Right to Lodge a Complaint

You have the right to lodge a complaint with a data protection supervisory authority if you believe that the processing of your data violates GDPR.

**Competent Authority in Germany:**

Bavarian State Office for Data Protection Supervision (BayLDA)
Promenade 18
91522 Ansbach
Germany

**Website:** https://www.lda.bayern.de
**Email:** poststelle@lda.bayern.de
**Phone:** +49 (0) 981 180093-0

---

## 9. Data Security

JellyLens employs technical and organizational measures to protect your data:

- **Encryption:** Server credentials are stored encrypted in the iOS/visionOS Keychain
- **Local Storage:** All data is stored locally on your device (no cloud storage by the developer)
- **HTTPS:** All connections to your Jellyfin server use encrypted HTTPS connections (if your server supports it)
- **No Tracking:** JellyLens contains no analytics, tracking, or advertising SDKs

---

## 10. Third-Party Libraries

JellyLens uses the following open-source libraries:

### 10.1 FFmpeg (LGPL v2.1+)
- **Purpose:** Audio/video decoding for container formats (MKV, WebM, TS)
- **Data Processing:** Performed locally on your device, no data transmission to third parties
- **License:** GNU Lesser General Public License v2.1+
- **Source:** https://github.com/jellylens/ffmpeg

### 10.2 JellyfinAPI SDK (Swift)
- **Purpose:** Communication with Jellyfin server API
- **Data Processing:** Transmission to your own Jellyfin server
- **License:** MPL-2.0 (Mozilla Public License 2.0) — every source file carries an MPL-2.0 header; used unmodified as a Swift Package dependency
- **Source:** https://github.com/jellyfin/jellyfin-sdk-swift

**Important:** These libraries process data exclusively locally on your device or transmit it to your own Jellyfin server. No third parties receive access to your data.

---

## 11. Children

JellyLens is not specifically directed at children under 16 years of age. The app does not knowingly collect data from children. Parents should supervise children's use of the app and ensure that only age-appropriate content is available on the Jellyfin server.

---

## 12. Changes to this Privacy Policy

This privacy policy may be updated as needed (e.g., for new app features or legal changes). The current version can be found at:

**URL:** https://github.com/jellylens/legal/blob/main/PRIVACY_POLICY_EN.md

**Notice:** Significant changes will be communicated through an app update.

---

## 13. Contact

For questions about data protection or to exercise your rights, contact us at:

**Email:** vision@jellylens.com
**Response Time:** Within 14 days

---

**Last Updated:** 2026-06-22
**Version:** 1.1
**Data Controller:** Thies Schneider, Germany (full postal address in the in-app Impressum, § 5 DDG)
