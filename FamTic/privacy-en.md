# FamTic Privacy Policy

Last updated: 2026-08-24

> 🇰🇷 **한국어**: [개인정보 처리방침 (한국어)](./privacy.md) · [지원 / FAQ](./support.md)
> 🇺🇸 English: this page · [Support / FAQ](./support-en.md)

> This policy covers FamTic 1.0. The Korean and English versions describe **the same facts in two
> languages**; if they are ever read differently, the Korean version governs. The public copy is hosted on
> GitHub Pages (https://lovelsh.github.io/FamTic/privacy-en) and the Korean copy is the URL entered in the
> "Privacy Policy URL" field of App Store Connect.

---

## Privacy Policy

**Effective date**: 2026-08-24

**Service**: FamTic (팸틱)

**Developer / Operator**: SeulHa Lab

FamTic ("the app") helps families, couples and parents keep schedules, anniversaries, shopping lists,
tuition payments, notes, trip packing lists and living expenses in one place. We take the privacy of our
users and their families seriously, and handle data as described below.

### 1. What we collect — there is no sign-up

The app has **no sign-up and no login.** It never asks for or collects a name, email address, phone
number, date of birth or postal address — or any other personally identifying information.

- The app uses only **Anonymous Authentication** from Google Firebase Authentication. The first time you
  open the app, your device is issued a random anonymous identifier (uid). That identifier is your only
  identity within the app.
- This anonymous identifier is **not linked** to your Google account, Apple ID, email address or phone
  number.
- Everything else the app stores is limited to **data you type in yourself**.

### 2. What you type in

The following items are stored when you enter them.

- **Display nickname and character**: an alias used to tell fam members apart (up to 10 characters) and
  one of 16 built-in characters. You are never required to enter a real name. No photo or image file is
  stored — only the character's identifier string is shared.
- **Fam (family) name**: a group name you choose (up to 20 characters).
- **Module entries**: schedules (title, date, time, note, reminder times), anniversaries (title, solar or
  lunar date, note, reminder times), shopping (item, quantity, note, who grabbed it), tuition (item,
  amount, due date, repeat cycle, paid or not), notes (title, body), trip packing (trip name, dates, item
  name, category, checked or not), living expenses (item, amount, date, category, who spent it).
- **Sharing scope settings**: for each entry, who inside your fam may see it (**Everyone / Selected
  members / Only me**) together with the list of anonymous identifiers it applies to. "Everyone" here does
  **not** mean public on the internet — it means **everyone in the fam you invited**.

The app **does not access your photo library, camera, contacts, location, microphone or health data**, and
does not request those permissions.

### 3. Where data is stored

Where your data lives depends on how you use the app.

**(1) Solo (trial) mode — on your device only**

- As long as you use the app alone, without creating or joining a fam, everything you enter is stored
  **only on your device** (the app's private storage area and `UserDefaults`).
- In this state nothing you enter is transmitted to any external server.

**(2) Shared (fam) mode — Google Firebase Firestore**

- Once you create a fam or join one with an invite code, the shared entries are stored in Google Cloud
  Firestore and synchronised between fam members' devices.
- **Storage region: `asia-northeast3` (Seoul, Republic of Korea).** Shared data is held in the Korean
  region.
- Data is stored only under the `families/{familyId}/` path, and server security rules **deny reads and
  writes to anyone who is not a member of that family**. Collection-wide enumeration (list) is blocked, so
  a third party who does not know the family ID has no way to discover the documents.
- Entries you mark "Only me" or "Selected members" are **never delivered to non-recipients at the server
  rule level.** They are not merely hidden in the UI.
- A fam holds at most 10 members.

We do not run our own servers, and we do not transmit your data anywhere other than the Firestore project
described above.

### 4. What "sharing" means — only with the family members you invited

In this app, "sharing" means **sharing among the members of your own fam (at most 10 people), each of whom
you invited and the fam owner approved.** Nothing else.

- **The app has no public board, no timeline, no feed, no search and no matching with strangers.** There
  is no path by which what you enter becomes visible to other users outside your fam, or to the internet.
- Every entry can be set to **Everyone / Selected members / Only me**. **"Everyone" means everyone in your
  own fam — never the public internet.**
- A new member must **enter an invite code and then be approved by the owner** (the person who created the
  fam). A code alone does not grant access.
- Invite codes expire **3 days** after they are issued, and the owner can re-issue or stop a code at any
  time.
- The owner can remove a member from the fam. Once removed, that member's device can no longer reach the
  shared data.

### 5. Recovery codes — for when you change phones

Because anonymous sign-in issues a new identifier when you move to a new device, the app provides a way to
get your fam back.

- When you run a backup, a human-readable **recovery code** is generated once.
- **The plaintext code is never stored on the server.** Only its `SHA-256` hash is stored, and the
  original code cannot be derived from the hash.
- Entering the code on a new device reconnects you to your existing fam only if the hash matches.
- As a secondary option, recovery information can be stored in the iCloud Keychain so another device
  signed in to the same Apple ID can restore without the code. That item exists only inside Apple's
  Keychain and **we cannot access it.** iOS removes Keychain items when the app is deleted.
- For a fam that has purchased the paid pass, the `SHA-256` hash of the purchase receipt's original
  transaction identifier is stored as a recovery anchor. **The original transaction identifier itself and
  any payment method details are not stored.**

### 6. In-app purchases

- The app offers **one non-consumable, one-time in-app purchase**.
  - Together Unlock (`com.lovelsh.FamilyPlan.together`) — unlocks using the app together with your
    family. **The owner pays once and every invited member uses it with no further purchase.**
- All payments go through Apple's payment system (StoreKit) and are processed by Apple. The app **does not
  collect or store payment method details such as card numbers.**
- Only the fact that a fam is paid, and the recovery hash described in §5, are stored in Firestore.
- This is not a subscription and does not auto-renew.

### 7. Advertising / advertising identifier

- **The app does not display advertising.** Because no ads are shown, no data is collected, transmitted or
  shared with third parties for advertising purposes.
- The app **does not request App Tracking Transparency (ATT) permission, and therefore does not access the
  advertising identifier (IDFA).**
- The app **does not track you across other companies' apps and websites.**
- The app **does not use behavioural analytics SDKs such as Firebase Analytics.** The only external SDKs
  the app actually initialises and uses are Firebase Authentication and Firebase Firestore.

### 8. Permissions

- **Notifications (optional)**: used for advance reminders for anniversaries, schedules and tuition due
  dates. Every reminder is a **local notification scheduled on your device**; no push is sent from any
  server. If you decline, only reminders stop working — everything else is unaffected.

The app requests no permissions beyond the one above.

### 9. Retention and deletion

- **Solo (trial) mode data**: held on the device only, so deleting the app deletes it too.
- **Shared data**: deleting an entry in the app deletes it from Firestore as well. When the owner removes a
  member, that member's profile document is deleted and their access ends.
- **⚠️ Deleting the app does not erase shared data held on the server.** Shared data lives in Firestore
  rather than on your device, so if you only delete the app, the records remain visible to the other
  members.
- **You can delete everything from inside the app**: **[Settings → Data management → Delete account &
  data]** deletes your data **together with your anonymous account**. Because it cannot be undone, it is
  guarded by two steps (a confirmation dialog, then typing the delete keyword yourself).
- **What gets deleted** depends on your role.
  - **Owner**: every shared entry in the fam, all member profiles (`members/{uid}`), invite-code mappings,
    recovery codes, the purchase-restore anchor, the fam document, and the local copy on the device.
  - **Member**: the shared entries you added, your own member profile, and the recovery code and local
    copy on your device. The rest of the fam is left intact.
  - **Solo (trial)**: all trial data stored on the device.
  - **In every case**: once that cleanup finishes, **the anonymous authentication account (uid) itself is
    deleted last.** After deletion you cannot come back as the same anonymous identifier.
- **Recovery codes and the purchase-restore anchor are invalidated at the same time.** A deleted fam
  cannot be brought back with an old recovery code.
- Because an anonymous identifier alone does not let us identify you, please use the in-app path above. If
  in-app deletion is impossible for some reason, contact us at §12 with your family ID.
- **In-app purchase history stays with your Apple account.** The purchase record itself is held by Apple,
  not by us, so in-app deletion cannot remove it. You can therefore use "Restore purchases" to get the
  pass back after deleting. However, since the purchase-restore anchor is deleted as described above,
  **what comes back is the pass alone, not the data of the deleted fam.** Refunds must be requested from
  Apple.

### 10. Your rights

You can view, edit and delete anything you entered at any time using the app's own features, and you can
change the **sharing scope** of any entry at any time. Nicknames and characters can be changed from the
Settings screen.

### 11. Children's privacy

The app is rated **4+** on the App Store, but **it is intended for adult guardians and couples who manage a
household together.** We do not market the app directly to children, and **we do not recommend that
children under 14 use it on their own.** Information relating to children (tuition item names and the
like) is text entered by a guardian, and is not disclosed to anyone outside that fam.

### 12. Privacy contact

- Responsible party: SeulHa Lab
- Email: lovelsh.support@gmail.com

### 13. Changes to this policy

If this policy changes, we will give notice in advance through an app update and through this page.
