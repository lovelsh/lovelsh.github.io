# ScheduleManager (자녀일정) — FAQ

- [Privacy Policy](./privacy_en.md)
- Email: **lovelsh.support@gmail.com**

---

## Frequently Asked Questions

### Q1. How do I add a new schedule?

- On the Schedule tab, tap the **+** button at the top right and enter a title, notes, date / time, a category (School / Academy / Homework / Event / Supplies / Field Trip / Counseling / Other) and the child.
- From the same screen you can attach one or more notice photos with **Pick Photo** or **Camera**.
- Saving updates both the Schedule list and the Calendar instantly.

### Q2. How do I manage several children?

- Open **Settings → Manage Children → Children List** and tap **+** to add each child with a name, school / daycare name and color.
- Use the per-child chips above the Schedule list and Calendar to filter to a single child.
- The chosen color is used for each schedule's left accent bar and the dot in the calendar.

### Q3. When will my reminders arrive?

- When you enable the **Reminder** toggle in the schedule form you can pick a reminder offset between **1 and 100 days** in advance.
- You also pick the exact time of day (e.g. 8:00 AM before drop-off).
- If a reminder never appears, check **iOS Settings → Notifications → ScheduleManager** and make sure Allow Notifications, Banners, Sounds and Badges are all on.
- Reminders are scheduled locally on the device — they fire even without an internet connection.

### Q4. How do I add the home-screen widget?

- Long-press an empty area of the home screen, tap **+** at the top left and search for `ScheduleManager` (or `자녀일정`).
- Small and Medium sizes are supported. The widget shows the next upcoming schedule with the child's name, date and category icon.
- The widget refreshes automatically after schedules change, but the exact refresh moment is decided by iOS so there can be a short delay.

### Q5. Where are attached notice photos stored?

- Attached photos are saved as JPEG into the app's private container (`ScheduleImages` folder).
- They are never uploaded to any server, and the developer cannot access them.
- Tap a photo on the schedule detail screen to view it full-size and read the notice.

### Q6. How do backup and restore work?

- **Settings → Data Management → Export Backup** writes all children / schedules / photos to a single `.schemng` backup file (share it through iCloud Drive / AirDrop / Messages).
- **Restore Backup** lets you choose **Overwrite** (delete existing data and replace with the backup) or **Merge** (keep both existing and backup data).
- The backup is the recommended way to migrate to a new device or recover from an accidental delete.

### Q7. How do I tidy up completed schedules?

- Swipe a schedule row from left to right to toggle the **Done / Not Done** state. You can also tap the circle on the left of the row.
- The Schedule tab has an **All / Done / Upcoming** segmented control for filtering.
- The list automatically splits into "Upcoming · Past · Undated" so old items do not crowd the view.

### Q8. Why is there an ad banner?

- ScheduleManager 1.0 is **free with a Google AdMob banner**. A single 50pt banner appears at the bottom of the main screen.
- On first launch the App Tracking Transparency (ATT) dialog asks for IDFA consent — declining does **not** restrict any functionality.
- A future update may introduce a paid "remove ads" In-App Purchase.

### Q9. Which iOS version is required?

- iOS 17 or newer. The app uses SwiftUI, SwiftData and the iOS 17+ widget / local notification APIs.

### Q10. How do I delete all of my data?

- Delete schedules individually from the schedule detail screen.
- Delete an entire child from **Settings → Manage Children → Children List**. Removing a child also removes every schedule and attached photo for that child.
- Deleting ScheduleManager from iPhone removes all on-device data.

---

## Still stuck?

Email **lovelsh.support@gmail.com** with:

- iOS version (e.g. iOS 17.4)
- iPhone model (e.g. iPhone 15 Pro)
- A short description of what you did and what happened
- (Optional) a screenshot
