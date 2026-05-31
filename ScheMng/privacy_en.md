# Privacy Policy

> Public hosted English version. Available at `https://lovelsh.github.io/ScheMng/privacy_en`. App Store Connect references this URL for the English locale.

---

## Privacy Policy

**Effective date**: 2026-05-31

**Service**: ScheduleManager (Korean app name: 자녀일정 / ScheMng)

**Developer / Operator**: SeungHee. Lee

ScheduleManager ("the App") is a tool that helps a parent or guardian organize a child's preschool, daycare or school notices and schedules. We treat your data — and your child's data — as personal information and process it as follows.

### 1. Personal information we collect

The App requires no account. We do **not** collect any personally identifying information from the guardian (name, email, phone number, date of birth, etc.) on our own infrastructure. The only data the App stores is what you, the user, type in or attach yourself.

### 2. Data the user enters and where it is stored

- Child profiles (name, preschool / school name, color, icon), schedule entries (title, notes, date, time, category, reminder timing) and attached notice photos are stored on **your device only**, via SwiftData and the local app sandbox file system.
- We do not operate a backend that receives this content. None of it is uploaded to a server we control.
- The child's name and school name are free-form text you enter for in-family identification convenience. We do not share or analyze this content.

### 3. Photo Library / Camera access — optional permission

- Used only when you attach a notice photo to a schedule. Access is one-shot per pick — the App never scans the whole Photo Library in the background.
- Attached photos are copied into the App's private sandbox directory and never leave the device through our infrastructure.
- Declining this permission does not affect any other feature (child profiles, schedules, reminders, calendar).

### 4. Local notifications — optional permission

- Used to fire the multi-day reminders you set per schedule. Notifications are scheduled by iOS on-device — no push server is involved.
- You pick the reminder offset (1 – 100 days in advance) and the exact time.
- Declining this permission only disables the reminder feature; nothing else changes.

### 5. Widget

- The WidgetKit extension (`ScheMngWidget`) shares an App Group with the host app and reads the same on-device data to render the upcoming-schedule widget.
- The widget does not collect any additional data.

### 6. iCloud (CloudKit) sync — future optional feature

- If a future release enables iCloud sync, data will be replicated through Apple's CloudKit Private Database tied to your own Apple ID. The App's operator cannot access that data.
- iCloud handling is governed by Apple's iCloud terms.

### 7. Advertising / IDFA

- The App displays a single 50pt bottom banner served by **Google AdMob (Google LLC)**.
- If you accept the App Tracking Transparency (ATT) prompt, your IDFA may be used by AdMob for ad personalization / measurement. Declining keeps the App fully usable.
- The App ships no behavioral analytics SDK (no Firebase Analytics, no Amplitude, etc.). AdMob is the only third-party SDK that leaves the device.
- AdMob data processing is governed by [Google's Privacy Policy](https://policies.google.com/privacy).

### 8. In-App Purchase

- 1.0 ships without any In-App Purchase.
- If a future "remove ads" IAP is added, it will be processed exclusively through Apple's StoreKit. We store no payment information beyond the transaction receipt.

### 9. Retention and deletion

All child, schedule and photo data lives on your device. Deleting the App removes the data with it. From **Settings → Data Management** you can also use **Restore Backup → Overwrite** to replace the entire on-device dataset.

### 10. Your rights

You can view, edit and delete every schedule / child / attached photo directly inside the App. Photos can be removed one by one from the schedule detail screen. Removing the App from iPhone removes all local data.

### 11. Children's data

The App is not designed for use by children under 14. It is a tool **for the parent or guardian** who enters and curates the child's schedule. Please enter only the information necessary for your own household.

### 12. Contact

- Owner: SeungHee. Lee
- Email: lovelsh.support@gmail.com

### 13. Changes

We will note material changes to this policy in an app update and on this page before they take effect.
