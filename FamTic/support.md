# FamTic — Support / 자주 묻는 질문

- ✉️ Email: **lovelsh.support@gmail.com**
- 🇰🇷 한국어: [개인정보 처리방침](./privacy.md) · 지원(이 페이지)
- 🇺🇸 English: [Privacy Policy](./privacy-en.md) · [Support (English only)](./support-en.md)

---

## English

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

#### Q. Does FamTic show advertising?
- Yes. While you use FamTic for free, a single **Google AdMob banner** sits at the bottom of the hub
  screen. FamTic uses no interstitial, rewarded or video ad formats.
- Buying **Remove Ads** — or **Together Unlock**, which already includes it — makes the banner go away.
- The first time you reach the hub, FamTic explains why it is asking and then shows the iOS **App
  Tracking Transparency** prompt. **Declining is fine: every feature keeps working**, and the banner is
  limited to non-personalised ads.
- In the EEA and the UK an extra consent step follows the ATT prompt, and you can reopen it any time
  from **Settings → Ad privacy settings**.
- Full details are in §7 of the [Privacy Policy](./privacy-en.md).

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

---

## 한국어

### 자주 묻는 질문

#### Q. 회원가입을 해야 하나요?
- 아니요. 팸틱은 **회원가입 절차가 없습니다.** 이메일·전화번호·비밀번호를 묻지 않으며, 앱을 열면
  바로 모든 모듈을 쓸 수 있습니다.
- 기기는 앱만 확인할 수 있는 익명 Firebase 인증 ID 로 식별됩니다.

#### Q. 가족을 어떻게 초대하나요?
- 팸을 만든 사람(**대표**)이 **팸 관리**에서 초대 코드를 발급합니다.
- 나머지 구성원은 그 코드를 입력하고 캐릭터와 애칭을 고른 뒤 합류를 요청합니다.
- 대표가 요청을 승인하면 합류가 끝납니다. 승인 전에는 공유 데이터가 보이지 않습니다.
- 초대 코드는 **3일** 후 만료되며, 대표는 언제든 코드를 중지하고 새로 발급할 수 있습니다.

#### Q. 휴대폰을 바꾸면 어떻게 되나요?
- 기존 기기에서 설정 화면의 **복구 코드**를 미리 저장해 두세요. 새 기기에서 그 코드를 입력하면 같은
  팸의 구성원으로 복구됩니다.
- 유료 팸이라면 구매 자체가 앵커가 됩니다. 새 기기에서 **구매 복원**을 누르면 팸을 되찾습니다.
- ⚠️ 복구 코드도 구매 기록도 없으면 익명 신원이 유일한 증명이라 되살릴 수 없습니다. 이 경우 대표에게
  초대 코드를 다시 받아 합류해 주세요.

#### Q. 가족을 초대하기 전에 먼저 써 볼 수 있나요?
- 네. **솔로(체험) 모드**는 계속 무료이고 모든 모듈이 들어 있습니다. 솔로 데이터는 기기 안에만
  저장됩니다.
- 나중에 팸을 만들면 솔로에서 쌓아 둔 기록이 그대로 옮겨집니다. 유실되지 않습니다.

#### Q. 내가 등록한 항목은 누가 볼 수 있나요?
- 항목마다 **공유 범위**(팸 전체 / 특정 멤버 / 나만 보기)를 고를 수 있습니다. 여기서 **"팸 전체"는 인터넷
  공개가 아니라 내가 초대해 합류한 우리 팸 구성원 전원**을 뜻합니다.
- 팸틱에는 **공개 게시판·타임라인·검색·낯선 사람과의 매칭 기능이 없습니다.** 내가 적은 내용이 팸 밖으로
  나가는 경로 자체가 없습니다.
- 공유 범위는 화면에서만 가리는 것이 아니라 서버 보안 규칙으로 강제됩니다. 볼 권한이 없는 항목은
  기기로 아예 내려오지 않습니다.

#### Q. 기념일에 음력을 쓸 수 있나요?
- 네. 기념일은 양력과 **음력** 모두 등록할 수 있어, 음력 생신이나 제사도 매년 정확한 날짜에 뜹니다.
- 당일 · 하루 전 · 7일 전 중에서 골라 미리 알림을 받을 수 있습니다.

#### Q. 알림이 오지 않습니다.
- 모든 알림은 **기기 안에서 예약되는 로컬 알림**입니다. 서버 푸시가 아니라 오프라인에서도 동작하지만,
  알림 권한은 필요합니다.
- **iOS 설정 → 알림 → 팸틱**에서 알림 허용을 확인하시고, 앱 안 **설정 → 알림 설정**에서 켜 둔 시점을
  다시 확인해 주세요.

#### Q. 유료 이용권은 어떻게 동작하나요?
- **가족과 함께 쓰기**(팸 만들기·초대)는 **1회성 인앱 결제**로 열립니다. 구독이 아니므로 자동 갱신되지
  않습니다.
- 결제는 **대표만** 하면 됩니다. 대표가 초대한 구성원은 추가 결제 없이 무료로 함께 씁니다.
- 솔로 모드는 계속 무료입니다.
- 기기를 바꾼 경우 **설정 → 구매 복원**을 이용해 주세요.

#### Q. 광고가 보이나요?
- 네. 무료로 쓰시는 동안 허브 화면 **맨 아래에 Google AdMob 배너 한 줄**이 표시됩니다. 전면 광고·보상형
  광고·동영상 광고는 사용하지 않습니다.
- **광고 제거**를 구매하시거나, 광고 제거가 포함된 **함께 쓰기 이용권**을 구매하시면 배너가 사라집니다.
- 허브에 처음 들어가시면 왜 묻는지 설명해 드린 뒤 iOS **앱 추적 투명성(ATT)** 창이 뜹니다. **허용하지
  않으셔도 모든 기능을 그대로 쓰실 수 있고**, 배너는 개인화되지 않은 광고로만 표시됩니다.
- 유럽경제지역(EEA)·영국 등에서는 ATT 다음에 동의 창이 한 번 더 뜨며, **설정 → 광고 개인정보 설정**에서
  언제든 다시 여실 수 있습니다.
- 자세한 내용은 [개인정보 처리방침](./privacy.md) §7 을 참고해 주세요.

#### Q. 데이터나 계정을 삭제하려면?
- 앱 안에서 **설정 → 데이터 관리 → 계정 및 데이터 삭제**를 누르고 두 번 확인하면 됩니다.
- **대표**가 삭제하면 팸 전체가 사라집니다 — 공유 모듈 문서, 구성원 프로필, 초대 코드가 모두 삭제된 뒤
  익명 계정이 삭제됩니다.
- **일반 구성원**이 삭제하면 본인의 구성원 프로필과 본인이 등록한 항목이 정리되고 계정이 삭제됩니다.
  나머지 팸은 그대로 유지됩니다.
- 복구 코드와 구매 복원 앵커도 함께 무효화되므로, 삭제한 계정을 예전 복구 코드로 되살릴 수 없습니다.
- 아이폰에서 앱을 삭제하면 솔로 모드의 기기 내 데이터도 함께 지워집니다.

#### Q. 공유 데이터는 어디에 저장되나요?
- 공유 항목은 Google Firebase(Cloud Firestore) **서울 리전(asia-northeast3)** 에 저장되어 팸 구성원끼리
  동기화됩니다. 솔로 모드 데이터는 기기를 떠나지 않습니다.
- 이름·이메일·전화번호는 수집하지 않으며, 애칭은 이용자가 직접 정하는 표시용 별칭입니다.

#### Q. 어떤 iOS 버전이 필요한가요?
- iOS 16 이상, iPhone 전용입니다.

### 그래도 해결되지 않으면
**lovelsh.support@gmail.com** 으로 아래 내용을 보내 주세요.
- iOS 버전
- 기기 모델
- 어떤 동작을 했고 무엇을 기대했는지 짧은 설명
- (선택) 스크린샷
