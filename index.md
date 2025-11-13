# WeSpot Privacy Policy

**Last Updated:** November 13, 2025  
**Effective Date:** November 13, 2025

---

## 1. Who We Are

WeSpot is operated by **WeSpot Labs, Inc.** (“WeSpot,” “we,” “our,” or “us”). We provide a mobile application that helps families and trusted groups stay connected, share locations, and respond quickly to safety events.

This Privacy Policy describes how WeSpot collects, uses, and safeguards personal information when you use the WeSpot mobile application and related services (collectively, the “App”). If you disagree with any part of this Privacy Policy, please do not use the App.

---

## 2. Information We Collect

| Category | Details | How it is collected | Control |
| --- | --- | --- | --- |
| Account data | Email, password hash, display name, profile photo | When you create or update your account | Required to create an account |
| Safety & contact data | Emergency contacts, trusted friends, safe zones, optional medical details | When you configure safety features | You can add, edit, or delete this data at any time |
| Location data | Current GPS coordinates, historical trips, geofence events | When you enable location tracking or safety features | Controlled via Privacy Settings → “Allow location tracking” |
| Driving & device telemetry | Motion sensor data for crash detection, speed, battery level | Only when you opt in to driving safety or battery monitoring | Controlled via dedicated toggles in Privacy Settings |
| Communications | Messages, location shares, group posts | When you use chat or sharing features | You can delete conversations and revoke sharing |
| Diagnostics | Crash logs, performance metrics | Only when you opt in to crash reporting or analytics | Controlled via Privacy Settings |

We also receive limited information from third-party providers we rely on:

- **Firebase (Google)** for authentication, databases, cloud messaging, analytics (optional), and Crashlytics (optional).  
- **Google Maps Platform** for map tiles, place search, and route data.  
- **In-app purchases and subscriptions** are handled by Google Play and Apple App Store; they provide transaction and entitlement confirmations.

We do **not** sell personal information and do **not** ingest social media data.

---

## 3. How We Use Information

We process personal information to:

1. **Provide the App** – sign-in, sync trusted contacts, share live locations, run emergency alerts, and deliver push notifications you request.  
2. **Keep you safe** – monitor geofences you configure, send SOS messages, detect severe driving events, notify trusted contacts of low battery or crashes (only when those features are enabled).  
3. **Improve reliability** – if you opt in to anonymous analytics we track feature usage, device type, and performance to improve the experience.  
4. **Diagnose issues** – if you opt in to Crashlytics we capture crash logs to debug problems.  
5. **Comply with law** – handle legal obligations, enforce our policies, and respond to lawful requests.

We rely on the following legal bases under data protection laws:  
**Consent** (for optional analytics, crash reporting, voice SOS, driving/battery monitoring), **Contract** (to deliver the service you requested), **Legitimate interest** (to secure accounts, prevent abuse), and **Legal obligation** (for record keeping or responding to lawful requests).

---

## 4. Privacy Controls in the App

You have granular control inside **Settings → Privacy Settings**:

- **Allow essential data collection** – required for account security, syncing trusted contacts, and delivering requested services.  
- **Share anonymous analytics** – optional; when off, analytics data is not collected or sent.  
- **Send crash reports** – optional; when off, Crashlytics identifiers are cleared and future crash events are not sent.  
- **Allow location tracking** – toggles live and background location updates, geofencing, and WorkManager background jobs.  
- **Enable driving safety monitoring** – optional; requires location tracking and device motion sensors.  
- **Share low-battery alerts** – optional; stops sending battery telemetry when off.  
- **Enable voice SOS detection** – optional; when off, the microphone is not activated for SOS keywords.  
- **Data retention** – choose how long WeSpot keeps your location history (30, 90, 180, 365, 730, or 1095 days). The default is 12 months.

These preferences take effect immediately and are stored securely on your device and in your user profile.

---

## 5. How We Share Information

We share personal information only in the following circumstances:

- **Trusted contacts you designate** – live or historical location data, arrival/departure alerts, crash or SOS notifications, and low-battery warnings.  
- **Service providers** – Firebase (Google), Google Cloud Platform, WorkManager/Android system services, Apple Push Notification service, Google Play / App Store billing. These providers process data on our behalf under contracts that require them to safeguard it.  
- **Legal disclosures** – if required by law or to protect users, suspected victims, or WeSpot.  
- **Business transfers** – in the event of a merger, acquisition, or sale of assets, provided the new entity honors this policy.

We do **not** sell personal information or share it with advertising networks without your explicit consent.

---

## 6. Data Security

We take security seriously:

- All network traffic uses TLS 1.2+ encryption.  
- Sensitive data in Firebase is protected by security rules and access controls.  
- Local caches and notification payloads stored by the app are encrypted using AES-based secure storage.  
- Crashlytics/Analytics identifiers are cleared immediately when you revoke consent.  
- Access to production systems is restricted to authorized staff with audit logging.

No security program is perfect, but we regularly assess our controls and monitor for vulnerabilities.

---

## 7. Data Retention & Deletion

| Data Type | Retention | How to manage |
| --- | --- | --- |
| Location history | As per the retention period you choose (default 365 days) | Change in Privacy Settings or delete account |
| Emergency alerts, place alerts | Up to 24 months unless you delete them sooner | Delete from the activity feed or delete account |
| Account/profile info | Until you close your account | Delete account in Privacy Settings |
| Telemetry analytics/crash data | Only while you have those toggles enabled | Disable toggles to stop future collection |

**Export your data** – In Privacy Settings tap “Export my data” to download a JSON copy of your profile, locations, alerts, and contacts.  
**Delete account & data** – In Privacy Settings tap “Delete account & data.” We immediately disable services, remove Firestore collections, delete Storage files, clear local encrypted caches, revoke FCM tokens, and request Firebase Auth to remove your user account. Some legal obligations (e.g., fraud logs) may require limited retention after deletion.

---

## 8. Children’s Privacy

WeSpot is designed for families but is **not intended for children under 13**. We do not knowingly collect personal information from children under 13. If you believe WeSpot has inadvertently collected data from a child, contact us and we will delete it.

---

## 9. International Data Transfers

We store data in the United States and may transfer it to other countries where our processors operate. We rely on Standard Contractual Clauses and equivalent safeguards required by applicable law. By using the App, you understand your data may be processed outside your home country.

---

## 10. California Notice (CCPA/CPRA)

California residents have the right to know what personal information we collect, request deletion, request correction, and opt out of “sales” or “sharing” (WeSpot does neither). Exercise these rights via the in-app Privacy Settings or by contacting us (see Section 13). We do not discriminate against users who exercise these rights.

---

## 11. European Economic Area & United Kingdom

If you are in the EEA or UK, you may exercise GDPR/UK GDPR rights—access, rectification, erasure, restriction, portability, objection, and withdrawal of consent—through the App or by contacting us. You may lodge a complaint with your local supervisory authority, but we encourage you to contact us first.

---

## 12. Third-Party Services

| Service | Purpose | Policy |
| --- | --- | --- |
| Firebase Authentication | Account sign-in | https://policies.google.com/privacy |
| Firebase Firestore/Realtime Database | Sync locations, alerts, chats | https://policies.google.com/privacy |
| Firebase Cloud Messaging | Push notifications | https://policies.google.com/privacy |
| Firebase Crashlytics & Analytics (optional) | Diagnostics and metrics | https://policies.google.com/privacy |
| Google Maps Platform | Maps, geocoding, routing | https://policies.google.com/privacy |
| Google Play / Apple App Store | Billing, subscriptions | Google & Apple privacy policies |
| Share Plus (system share sheet) | Exporting your data | Shares through OS-provided channels |

Each provider has its own privacy practices; we recommend reviewing their policies.

---

## 13. Contact Us

**WeSpot Labs, Inc.**  
privacy@wespot.app  
1234 Market Street, Suite 200  
San Francisco, CA 94103, USA  
Phone: +1 (415) 555-0199  
Data Protection Officer: dpo@wespot.app

We will respond to verified requests within 30 days (or the shorter period required by applicable law).

---

## 14. Changes to This Policy

We may update this Privacy Policy from time to time. If the changes are material, we will notify you via the App or email. The “Last Updated” date at the top reflects the latest revision. Your continued use of the App after the effective date means you accept the changes.

---

## 15. Consent

By using WeSpot, you acknowledge that you have read and understood this Privacy Policy. You may withdraw consent at any time using the in-app controls; doing so may disable certain features.

---

## Appendix A – Data Categories & Purposes (Summary)

| Category | Examples | Purpose |
| --- | --- | --- |
| Identity | Email, profile photo | Account creation, authentication |
| Contact | Emergency contacts, phone | Notify trusted contacts, SOS |
| Location | GPS, place alerts | Live sharing, safety automation |
| Usage | Screen flows, feature toggles | Improve UI/UX (optional analytics) |
| Diagnostics | Crash stack traces | Debug (optional Crashlytics) |
| Sensor | Accelerometer, speed | Driving safety (when enabled) |

---

**WeSpot Labs, Inc.** – Keeping the people you care about close, while respecting their privacy.





























