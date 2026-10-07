# Privacy Policy - Dabba Diary

Last updated: 2026-10-06

Dabba Diary ("the app") is a tiffin and meal-subscription tracker developed by Rutik Rathod (contact: rathodrutik05@gmail.com). This policy explains what the app stores, what leaves your device, and the choices you have.

## Summary

Dabba Diary works fully offline. Your name, your meal prices and your daily delivered or skipped marks are stored on your device, and no account is needed. Signing in with Google is optional and exists for one reason: to back up your data so you can restore it on a new phone. If you never sign in, none of your tiffin data leaves your device. The app uses Firebase Analytics and Crashlytics to understand how it is used and to fix crashes, and shows ads through Google AdMob. Both are described below.

## Data stored on your device

Whether or not you sign in, the app stores the following in its private storage on your phone:

- The name you enter, the price per tiffin, and your tracking start date
- Which meals you receive (morning, afternoon, night)
- For each day, whether each meal was marked delivered or skipped
- Your settings: auto-mark, reminder time, appearance

Uninstalling the app deletes this data. Reminders are scheduled locally on your device; no server is involved.

## Optional: Google sign-in and cloud backup

If you choose Settings, Backup, Sign in with Google, the app uses Firebase Authentication to identify you and Google Cloud Firestore to store a copy of the data listed above. Your Google account name and email address are held by Firebase Authentication as part of your sign-in. The backup is stored under your account and can be read and written only by you; the developer does not read it.

While you are signed in, each change you make is also written to your backup. Signing in on a new phone restores it. Signing out stops further syncing but does not delete what is already backed up. To remove the backup and your sign-in record, use Delete account in Settings (see "Deleting your data").

Sign-in uses Google's own account and consent screens, governed by Google's Privacy Policy: https://policies.google.com/privacy

## Usage analytics and crash reports

The app uses Google Firebase Analytics and Firebase Crashlytics, which are on by default, whether or not you sign in, and which you can switch off at any time.

- **Analytics** records how the app is used so the developer can improve it: which screens are opened, when a meal is marked delivered or skipped (and for which meal slot), when the day sheet or share option is used, which setting was changed (the setting's name, and for toggles and theme the new value), and whether you signed in or out. It also keeps a few broad profile properties such as how many meals you track and whether auto-mark, reminders and dark theme are on. Firebase assigns a random app-instance ID to each install and may derive approximate location from the IP address.
- **Crash reports** record technical details when the app crashes: the error and stack trace, device model, Android version and app version.
- **Never sent:** your name, the price you enter, your dates, your amounts, or your email address. These events do not contain your tiffin records.

This data is processed by Google on the developer's behalf. See https://firebase.google.com/support/privacy for details. Analytics and crash reporting are switched off in development builds. If you are in the European Economic Area, the United Kingdom or Switzerland, analytics and crash reports start only after you accept them in the consent message (the same one used for ads), and "Ad privacy options" in Settings lets you change that choice. To stop both at any time, turn off Settings, Privacy, "Share usage data and crash reports". The app then collects no analytics events or crash reports. Your choice is saved with your settings, so it is also kept in your backup if you sign in. The app also links to this policy from Settings, Privacy.

## Advertising

The app shows banner ads provided by Google AdMob. To serve and measure ads, the AdMob SDK collects and processes data such as your device's advertising ID, IP address, approximate location derived from the IP address, device and app information, and how you interact with ads. This is collected by Google under its own policies, not by the developer:

- Google Privacy Policy: https://policies.google.com/privacy
- How Google uses data from apps that use its services: https://policies.google.com/technologies/partner-sites
- AdMob data disclosure: https://support.google.com/admob/answer/6128543

If you are in the European Economic Area, the United Kingdom or Switzerland, the app asks for your consent through Google's User Messaging Platform before requesting ads, and Settings shows an "Ad privacy options" entry so you can change your choice at any time. You can also reset or limit your advertising ID in your Android settings.

## What the app does not do

The app does not access your contacts, camera, microphone, photos or precise location. It does not sell your data.

## Permissions

- Internet and network state: for ads and, if you sign in, backup.
- Notifications: to show your optional daily reminder.
- Boot completed: to restore your daily reminder after the phone restarts. The reminder uses a standard (inexact) schedule, so it can arrive a few minutes after the chosen time.

## Deleting your data

- On your device: uninstall the app, or clear its storage in Android settings.
- Cloud backup and sign-in record: Settings, Backup, Delete account. You can also follow the steps at the delete-account page: https://luciferr2001.github.io/dabba-diary-privacy/DELETE_ACCOUNT.html

## Data retention

Local data stays until you delete it or uninstall the app. Cloud backup data stays until you delete your account. Analytics and crash data are retained by Firebase according to its standard retention settings (up to 14 months for analytics event data). Ad-related data held by Google follows Google's retention practices.

## Security

Data sent to Firebase travels over encrypted connections. Backup access is restricted so that only the signed-in owner can read or write their own data.

## Children's privacy

Dabba Diary is not directed at children under 13 and does not knowingly collect data from them.

## Changes to this policy

If the app's data practices change, this page will be updated and the "Last updated" date will change.

## Contact

For privacy questions, or to request deletion without using the app, email rathodrutik05@gmail.com.
