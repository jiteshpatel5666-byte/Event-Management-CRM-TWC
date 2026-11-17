# Event Management CRM – Android Studio Project

This is an Android app project for a single administrator. The event records from `Event_Sheet_2026-27.xlsx` (Sheet1) are bundled into the app.

## Build APK
1. Install Android Studio (current stable) and Android SDK Platform 35.
2. Open this folder (`EventManagementCRM_Android`) in Android Studio.
3. Allow Gradle sync to finish.
4. Choose **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
5. Install the generated APK on your Android phone.

## Included
- Dashboard totals, upcoming event count, total event value and pending payment total.
- Search and filter by year / venue.
- Event list, add, edit and delete.
- Month-based event calendar.
- Customer/mobile, advance, pending and notes fields can be added by the admin.
- Offline storage using the app's local WebView storage.

## Data notes
- Existing workbook records are imported from `Sheet1` without inventing customer or payment details.
- Customer, mobile, advance, pending and notes start blank because they were not populated in the source event sheet.
- The workbook has additional reference sheets; this first version uses the main event register (`Sheet1`) as the event source.
- This is a single-device, admin-only starter app. It has no cloud sync, multi-device backup, login or automatic Excel synchronization. Export/backup should be added before relying on it for critical business records.

## Package
`com.eventcrm.admin`
