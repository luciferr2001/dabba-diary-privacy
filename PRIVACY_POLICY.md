# Privacy Policy - Dabba Diary

Last updated: 2026-10-06

Dabba Diary ("the app") is a tiffin and meal-subscription tracker developed by Rutik Rathod (contact: rathodrutik05@gmail.com). This policy explains what the app stores, what leaves your device, and the choices you have.

## Summary

Dabba Diary works fully offline. Your name, your meal prices and your daily delivered or skipped marks are stored on your device, and no account is needed. Signing in with Google is optional and exists for one reason: to back up your data so you can restore it on a new phone. If you never sign in, none of your tiffin data leaves your device. The app shows ads through Google AdMob, described below.

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

## Advertising

The app shows banner ads provided by Google AdMob. To serve and measure ads, the AdMob SDK collects and processes data such as your device's advertising ID, IP address, approximate location derived from the IP address, device and app information, and how you interact with ads. This is collected by Google under its own policies, not by the developer:

- Google Privacy Policy: https://policies.google.com/privacy
- How Google uses data from apps that use its services: https://policies.google.com/technologies/partner-sites
- AdMob data disclosure: https://support.google.com/admob/answer/6128543

If you are in the European Economic Area, the United Kingdom or Switzerland, the app asks for your consent through Google's User Messaging Platform before requesting ads, and Settings shows an "Ad privacy options" entry so you can change your choice at any time. You can also reset or limit your advertising ID in your Android settings.

## What the app does not do

The app does not access your contacts, camera, microphone, photos or precise location. It does not sell your data, and it does not use Firebase Analytics or crash-reporting services.

## Permissions

- Internet and network state: for ads and, if you sign in, backup.
- Notifications: to show your optional daily reminder.
- Exact alarms and boot completed: to deliver the reminder on time and after a restart.

## Deleting your data

- On your device: uninstall the app, or clear its storage in Android settings.
- Cloud backup and sign-in record: Settings, Backup, Delete account. You can also follow the steps at the delete-account page: https://luciferr2001.github.io/dabba-diary-privacy/DELETE_ACCOUNT.html

## Data retention

Local data stays until you delete it or uninstall the app. Cloud backup data stays until you delete your account. Ad-related data held by Google follows Google's retention practices.

## Security

Data sent to Firebase travels over encrypted connections. Backup access is restricted so that only the signed-in owner can read or write their own data.

## Children's privacy

Dabba Diary is not directed at children under 13 and does not knowingly collect data from them.

## Changes to this policy

If the app's data practices change, this page will be updated and the "Last updated" date will change.

## Contact

For privacy questions, or to request deletion without using the app, email rathodrutik05@gmail.com.
