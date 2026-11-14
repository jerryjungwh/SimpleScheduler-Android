---
locale: en_US
description: "Privacy Policy of SimpleScheduler (Simganpyo), the Android timetable app: information processed, purposes, third-party services, and users' rights."
---
# Privacy Policy

This is an English translation of the Korean original. If the two differ, the Korean original prevails.

**SimpleScheduler (Korean name: 심간표)** (the "App") is a service for managing timetables, schedules, and To-Dos, provided by Jerry Jung (정우현) (the "Developer"). This Privacy Policy explains the types of information processed while users use the App, the purposes and methods of processing, and users' rights.

The App does not provide a sign-up feature. Timetables, schedules, To-Dos, alarms, and App settings are stored on users' devices and are not sent to any separate server of the Developer. However, the App uses the third-party services below for ads, payment and subscription management, usage statistics, and error analysis.

The Developer also runs `simganpyo.com`, a website about the App. Information processed when you use that website is described in Section 1-7.

---

## 1. Information Processed

### 1-1. Information Processed Only on the Device

| Information | Purpose | Storage location |
|------|------|-----------|
| Timetables, schedules, places, persons in charge, and memos | Timetable and schedule management | On-device database (SQLite) |
| To-Dos, linked timetables and schedules, and card customization information | To-Do management | On-device database and app-specific storage |
| Photos chosen by users (for To-Do cards and timetable backgrounds) | Customizing cards and timetables | App-specific storage |
| App settings, such as alarms, widgets, theme, and language | Providing App features and user settings | On-device storage (SharedPreferences, SQLite) |
| Expiry time of ad removal earned with a rewarded ad | Applying the 24-hour ad-removal benefit | On-device storage (SharedPreferences) |

- The information above is not sent to any server of the Developer.
- Only photos that users choose in the Android photo picker are copied to app-specific storage and used. The App does not request permission to access the entire photo library.
- The App does not use Android Auto Backup (Google Drive backup). If the App is uninstalled, the data in app-specific storage is deleted in accordance with operating system policy.
- If users choose manual backup, the timetable backup and the To-Do backup are each created as a file encrypted with a password that users set. Users choose whether to include photos, and choose the storage location or the app to share to. The Developer does not receive or retain backup files or passwords.

### 1-2. App Usage Statistics and Error Information

The App uses Firebase Analytics and Firebase Crashlytics.

| Service | Information that may be processed | Purpose |
|--------|---------------------|------|
| Firebase Analytics | App instance ID; app, device, and OS information; approximate region; screen views; app launches and updates; feature usage events; Advertising ID (depending on device settings and availability); Google Play purchase and subscription events | Analyzing usage statistics and improving features |
| Firebase Crashlytics | Crashlytics installation UUID; app, device, and OS information; crash and Application Not Responding (ANR) logs; diagnostic values at the time an error occurs | Error analysis and improving stability |

- The Developer does not send directly identifying information, such as names, email addresses, or phone numbers, to Firebase Analytics. The Developer also does not send content entered by users, such as timetable names, schedule names, To-Dos, or memos, to Firebase Analytics, and does not set a separate user ID.
- Crashlytics diagnostic values contain only app status and connection status, such as payment verification steps and error codes, response wait times, network connection type (Wi-Fi, mobile data, etc.) and whether the connection was validated, backup steps and counts, and widget drawing steps. Passwords, backup contents, purchase tokens, email addresses, and content entered by users are not recorded.

### 1-3. Advertising Information

The App uses Google AdMob to serve ads and Google User Messaging Platform (UMP) to provide an ad privacy options (consent) screen.

The Google Mobile Ads SDK may automatically collect or share the following information for ad delivery, measurement, analytics, and fraud prevention.

- Approximate location inferred from IP address
- User interactions, such as app launches, taps, and ad views
- Performance and diagnostic information about the App and the ad SDK
- Device identifiers, such as the Android Advertising ID and App Set ID

Ads may be personalized or non-personalized, depending on users' region, consent status, and device and Google settings. Users in regions where consent is required see a consent screen on first launch. They can change their choice later in the "Privacy options" entry on the App's Settings screen. Users can also delete or reset the Advertising ID in Android Settings.

While users have a valid subscription or remaining time on ad removal earned with a rewarded ad, the App does not show banner ads or interstitial ads. The App does not show ads on the lock screen or the alarm screen.

### 1-4. Payment and Subscription Information

The App uses Google Play and RevenueCat, Inc. ("RevenueCat") to verify purchases of the ad-removal subscription and manage entitlements.

| Information | Purpose | Processed by |
|------|------|-----------|
| RevenueCat anonymous user ID | Linking purchases and entitlements without an account | RevenueCat |
| Purchase, receipt, and transaction information; product IDs | Purchase verification, restoring purchases, and fraud prevention | Google Play, RevenueCat |
| Subscription status and history of renewals, cancellations, payment failures, and refunds | Determining the ad-removal entitlement and managing subscriptions | Google Play, RevenueCat |
| App and SDK versions; device and OS information; language and currency codes; country inferred from IP address | Operating the service, checking compatibility, statistics, and reviewing inquiries | RevenueCat |
| Firebase app instance ID | Linking subscription statistics with Firebase Analytics | RevenueCat, Google |

- The App does not send names, email addresses, phone numbers, or the Advertising ID to RevenueCat.
- The RevenueCat anonymous user ID is created by the RevenueCat SDK. It may change if the App is uninstalled and reinstalled. Valid purchases on the same Google Play account can be linked again with the App's "Restore purchases" feature.
- Payment method information, such as card numbers, is processed by Google Play, not by the App or the Developer.

### 1-5. Customer Inquiries

When users send an inquiry by email or use the contact form on the App's subscription management screen (RevenueCat Customer Center), the email address and inquiry content that they enter are processed to answer the inquiry. Inquiries sent through the contact form are forwarded to the Developer through RevenueCat's servers, and the following information is attached to help look into the problem. This information is not shown to users who send inquiries.

- RevenueCat anonymous user ID and active subscriptions (entitlements)
- Country, device version, and last seen app version
- Total amount paid and date of first use

The Developer uses this information only to the extent necessary to review and answer inquiries.

### 1-6. App Permissions

| Permission | Used for | Type |
|------|-------------|------|
| Notifications (Android 13 or later) | Showing the weekly table on the lock screen | Optional. Requested only when the weekly table on the lock screen is turned on |
| Display over other apps | Weekly table on the lock screen, and the schedule alarm screen | Optional. Requested when the related feature is turned on |
| Alarms & reminders (exact alarms) | Ringing schedule alarms and To-Do reminders at the set time | Required for alarms |
| Internet access, view network connections | Ads, subscription checks, and sending statistics and errors | Granted automatically |
| Run at startup, wake the screen | Re-registering alarms after the device restarts, and ringing alarms | Granted automatically |
| Advertising ID | Ad delivery and measurement | Granted automatically (can be deleted in device settings) |

Users can still use the App's other features without allowing optional permissions. Users can change permissions at any time in Android Settings.

### 1-7. Website Visit Information

The Developer runs `simganpyo.com`, a website about the App. The website has no sign-up or sign-in. It uses **Google Analytics** (installed through Google Tag Manager) to see which posts or searches people arrive from, which pages they read, and whether they press a store button.

| Item | Detail |
|------|--------|
| Cookie names and lifetime | `_ga` (2 years), `_ga_<measurement ID>` (2 years). Google Tag Manager itself sets no cookies |
| Information processed | The random identifier in the cookie, the address of the page visited and of the page before it, any tags on the link you arrived through (utm values), browser, device and operating system information, screen size, language, an approximate region estimated from the IP address, and actions such as pressing a store button or picking an example |
| Purpose | Understanding how people reach the website and use it, and improving the website |
| Processed by | Google LLC. How Google processes information on sites that use its services is described in [Google's notice](https://www.google.com/policies/privacy/partners/) |
| Retention | **14 months**, as set on the Google Analytics property (separate from the cookie lifetime) |

The website collects no directly identifying information such as a name, email address or phone number. Google receives the IP address in order to estimate an approximate region.

The website keeps where a visit came from in the browser's **`sessionStorage`** until the tab is closed, and passes that value in the address of the Google Play button. This is used to count how the App was installed; the value contains nothing that identifies a person.

**How to refuse**

- Visitors in the European Economic Area, the United Kingdom and Switzerland are asked before any measurement starts, and nothing is collected until they agree. Choosing "Decline" sets no cookies.
- Elsewhere, blocking or deleting cookies in the browser stops the collection.
- The [Google Analytics Opt-out Add-on](https://tools.google.com/dlpage/gaoptout) refuses it on every site.
- Refusing cookies does not limit reading the website or going to the store.

The website's visit-statistics cookies are used to improve the service, and the ways to refuse above stop the collection at any time.

---

## 2. Purposes of Use

The information processed is used only for the following purposes.

- Providing timetable, schedule, To-Do, alarm, widget, and backup features
- Serving ads, ad performance measurement, and fraud prevention
- Applying the ad-removal benefit from rewarded ads and paid subscriptions
- Google Play purchase verification, subscription status checks, restoring purchases, and subscription management
- Analyzing app usage statistics and improving features and usability
- Analyzing crashes, ANRs, and errors, and improving the App's stability
- Receiving customer inquiries, looking into payment and subscription issues, and answering inquiries

---

## 3. Processing by Third Parties and Entrustment of Processing

The Developer does not sell or rent users' information. The following companies process information to the extent necessary to operate the App.

| Entrusted party (services) | Entrusted tasks | Information processed |
|---------------|-----------|-----------|
| Google LLC (Google Play, AdMob, UMP, Firebase, Analytics and Tag Manager) | App distribution and updates, payment processing, ad and consent management, usage statistics, error analysis, and website visit statistics | Purchase and transaction information; ad and app interactions; app, device, OS, and diagnostic information; Advertising ID and app instance ID; approximate location based on IP address; and other information each service needs |
| RevenueCat, Inc. | Purchase verification; subscription status and entitlement management; subscription statistics; the subscription management screen and forwarding of inquiries | Anonymous user ID; Firebase app instance ID; purchase and transaction information; subscription status and history; app, SDK, device, and OS information; language and currency codes; country based on IP address; email addresses and content of inquiries; and the information attached to inquiries in Section 1-5 |

Each company's information processing follows the policies below.

- [Google Privacy Policy](https://policies.google.com/privacy)
- [Google AdMob privacy information](https://support.google.com/admob/answer/6128543)
- [Privacy and Security in Firebase](https://firebase.google.com/support/privacy)
- [RevenueCat Privacy Policy](https://www.revenuecat.com/privacy-policy)

---

## 4. Cross-Border Transfer of Personal Information

When third-party services are used, information is processed outside the Republic of Korea.

| Recipient | Destination country | Information transferred | Purpose of transfer | Timing and method of transfer | Retention and use period |
|-------------|-----------|-----------|-----------|----------------|----------------|
| Google LLC and its related service providers | The United States and other countries where Google has service facilities | The Google information listed in Section 3 | Payment, ads, statistics, error analysis, and providing the App's services | Transmitted over encrypted network connections when users use App, ad, payment, or statistics features | A period in accordance with Google's policies and applicable laws |
| RevenueCat, Inc. | The United States | The RevenueCat information listed in Section 3 | Purchase verification, entitlement management, subscription statistics, the subscription management screen, and forwarding of inquiries | Transmitted over encrypted network connections when users use subscription features or the subscription management screen | The period necessary to provide the service and meet legal obligations, or until a deletion request is processed |
| Google LLC | The United States and other countries where Google operates facilities | The website visit information in Section 1-7 | Understanding how people reach and use the website | Sent over an encrypted network when the website is visited | The period set on the Google Analytics property (14 months) and periods under Google's policies |

If users do not want a cross-border transfer, they can choose not to purchase or restore subscriptions and not to use the subscription management screen. In that case, they cannot use paid subscriptions, but they can still use other features. Ad-related processing can be adjusted with the Privacy options feature in Section 1-3 and Android ad settings. If users do not want the cross-border transfer of website visit statistics, the ways to refuse in Section 1-7 stop the collection.

---

## 5. Retention Period and Destruction

- **App data on the device:** It is kept in app-specific storage and is deleted in accordance with operating system policy if the App is uninstalled. Users must manage and delete their exported backup files themselves.
- **Google Play purchase information:** It is retained and processed in accordance with Google Play policies and applicable laws.
- **RevenueCat information:** It is processed in accordance with RevenueCat's policies for the period necessary for subscription management, restoring purchases, responding to inquiries, and legal obligations. If users request deletion, the Developer deletes it to the extent possible using the features RevenueCat provides.
- **Firebase Analytics and Crashlytics information:** It is processed in accordance with Google's policies and the retention period set by the Developer.
- **Website visit information:** Processed according to the retention period set on the Google Analytics property (14 months) and Google's policies. Cookies stay in the visitor's browser for up to 2 years and can be deleted there.
- **AdMob information:** It is processed in accordance with Google's advertising data policies and users' ad privacy settings.
- **Customer inquiries:** They are retained for the period necessary to resolve inquiries and handle disputes, and then deleted.

---

## 6. Users' Rights and How to Exercise Them

Users can manage their information or exercise their rights in the following ways.

- Deleting app data on the device by uninstalling the App
- Using the App's delete feature, or deleting exported backup files directly
- Changing the App's permissions in Android Settings
- Making ad choices and deleting or resetting the Advertising ID in the "Privacy options" entry in App settings and in Android ad settings
- Managing and canceling subscriptions in the Payments & subscriptions menu of the Google Play Store or on the App's subscription management screen
- Relinking valid purchases on the same Google Play account with the App's "Restore purchases" feature
- Sending requests for access, deletion, or similar regarding subscription information and inquiry records stored with RevenueCat to the email address below
- On the website, refusing visit statistics by blocking or deleting cookies, through the consent notice where it is shown, or with the Google Analytics Opt-out Add-on

Because the App does not maintain user accounts, the Developer may ask for the RevenueCat anonymous user ID or non-sensitive purchase-related information to verify the requester's identity. The Developer does not ask for passwords, full purchase tokens, or card information.

---

## 7. Children's Privacy

In accordance with the App's target age setting on Google Play, the App is provided for users aged 16 or older. The Developer does not knowingly collect personal information of users under the target age. If the Developer becomes aware that such information has been processed, the Developer takes the necessary measures in accordance with applicable laws and platform policies.

---

## 8. Security Measures

- Communication with third-party services uses encrypted connections.
- Manual backup files are encrypted with AES-GCM, using a key derived with PBKDF2 from the password that users set.
- The Developer does not store backup passwords and cannot recover forgotten passwords.
- Content entered by users, backup files, passwords, and purchase tokens are not recorded in statistics or error logs.

However, no method of transmission or storage can guarantee absolute security.

---

## 9. External Links

Third-party websites linked from the App or this document are not operated by the Developer. When using those services, please review each company's privacy policy.

---

## 10. Privacy Officer and Contact

- Privacy Officer: Jerry Jung (정우현)
- Email: jerryjung2929@gmail.com

Please send inquiries about the processing of personal information, requests for access and deletion, and complaints to the email address above.

---

## 11. Changes to This Policy

This Policy may be amended when applicable laws, Google Play policies, the SDKs the App uses, or App features change. Amendments are posted on this page. For material changes, the Developer will notify users through an in-app notice or other appropriate means before they take effect. Previous versions of this Policy are available in the [change history](https://github.com/jerryjungwh/SimpleScheduler-Android/commits/master/en/index.md).

---

Effective date: 2026-11-14  
Last updated: 2026-11-14

---

[View the Terms of Use](terms)
