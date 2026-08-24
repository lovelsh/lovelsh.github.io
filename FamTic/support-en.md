# FamTic — Support / FAQ (English)

- ✉️ Email: **lovelsh.support@gmail.com**
- 🇺🇸 English: [Privacy Policy](./privacy-en.md) · Support (this page)
- 🇰🇷 한국어: [개인정보 처리방침](./privacy.md) · [자주 묻는 질문](./support.md)

> This page is generated from the English section of the bilingual
> [support page](./support.md). Both say the same thing; edit `support.md`, never this file.

---
### Frequently Asked Questions

#### Q. Do I need to create an account?
- No. FamTic has **no sign-up**. It never asks for an email address, phone number, or password — open
  the app and you can start using every module immediately.
- Your device is identified by an anonymous Firebase Authentication ID that only the app can see.

#### Q. How do I invite my family?
- The person who creates the fam (the **owner**) opens **Fam management** and issues an invite code.
- Everyone else enters that code, picks a character and a display nickname, and requests to join.
- The owner approves the request. Until it is approved, the joiner cannot see any shared data.
- Invite codes expire after **3 days**, and the owner can stop a code at any time and issue a new one.

#### Q. What happens if I change my phone?
- Save the **recovery code** shown in Settings while you still have your old device. Entering it on the
  new device restores your membership in the same fam.
- For a paid fam, the purchase itself also works as an anchor: **Restore purchases** on the new device
  brings the fam back.
- ⚠️ Without a recovery code and without a purchase, the anonymous identity is the only proof of
  membership. If it is lost, ask the owner to send a fresh invite code.

#### Q. Can I try the app before inviting anyone?
- Yes. **Solo mode** is free forever and includes every module. Solo data is stored on your device only.
- When you later create a fam, everything you built up in solo mode is migrated over — nothing is lost.

#### Q. Who can see what I add?
- Every item carries a **sharing scope**: everyone in your fam, selected members only, or only me.
  "Everyone" means **everyone in your own fam — it is never public**.
- FamTic has **no public feed, no timeline, no search and no matching with strangers.** What you write
  never leaves the fam you invited.
- The scope is enforced by server-side security rules, not just hidden in the UI — items you are not
  allowed to see are never delivered to your device.

#### Q. Do anniversaries support lunar dates?
- Yes. Anniversaries can be registered on the solar or the **lunar** calendar, so lunar birthdays and
  memorial days land on the correct date every year.
- You can be reminded on the day, one day before, or seven days before.

#### Q. Why am I not getting reminders?
- All reminders are **local notifications scheduled on your device** — there is no server push, so they
  work offline, but they do require notification permission.
- Open **iOS Settings → Notifications → FamTic** and confirm notifications are allowed. Then check
  **Settings → Notifications** inside the app for the reminder timings you enabled.

#### Q. How does the paid unlock work?
- Using FamTic **with a family** (creating a fam and inviting members) is unlocked by a single
  **one-time in-app purchase** — it is not a subscription and does not auto-renew.
- Only the **owner** pays. Everyone the owner invites uses the fam for free, with no extra purchase.
- Solo mode stays free.
- Moved to a new device? Use **Settings → Restore purchases**.

#### Q. How do I delete my data or my account?
- In the app: **Settings → Delete account & data**, then confirm twice.
- If you are the **owner**, deleting removes the whole fam — every shared module document, all member
  profiles, and the invite codes — and then deletes your anonymous account.
- If you are a **member**, your member profile and your own entries are removed and your account is
  deleted; the rest of the fam is untouched.
- Recovery codes and purchase-restore anchors are invalidated at the same time, so a deleted account
  cannot be brought back with an old recovery code.
- Deleting the app from your iPhone removes all solo-mode data stored on the device.

#### Q. Where is shared data stored?
- Shared items are stored in Google Firebase (Cloud Firestore), **Seoul region (asia-northeast3)**, so
  fam members stay in sync. Solo-mode data never leaves your device.
- FamTic does not collect your name, email address, or phone number. The nickname you type is a
  display label you choose yourself.

#### Q. Which iOS version is required?
- iOS 16 or later, iPhone only.

### Still stuck?
Please email **lovelsh.support@gmail.com** with:
- iOS version
- Device model
- A short description of what you did and what you expected
- Optional screenshot
