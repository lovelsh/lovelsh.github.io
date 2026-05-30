# SubCheck — Support / 자주 묻는 질문

- ✉️ Email: **lovelsh.support@gmail.com**
- 🔒 [Privacy Policy / 개인정보 처리방침](./privacy.md)

---

## English

### Frequently Asked Questions

#### Q. How do I add a new subscription?
- Open the dashboard and tap the **+** button. Enter the service name, amount, billing date, billing cycle (monthly or yearly), and payment-method label. Categories include Streaming (OTT), Music, Shopping, Cloud, Games, AI, Telecom Bundle, and Other.
- You can also pick a service from the built-in catalog (Netflix, YouTube Premium, Spotify, Apple Music, etc.) to auto-fill the name and icon.

#### Q. When does the upcoming-charge reminder fire?
- SubCheck schedules a local notification **one day before** each subscription's next billing date, using the time you configured in Settings.
- If you never see reminders, open **iOS Settings → Notifications → SubCheck** and confirm that Allow Notifications, Banners, Sounds, and Badges are all enabled.
- Reminders are scheduled locally on your device — SubCheck does not send a server-side push, so they continue to work even without an internet connection.

#### Q. The home-screen widget is not refreshing. What should I do?
- The widget refreshes whenever you add, edit, or remove a subscription. iOS itself decides the exact refresh moment, so a brief delay is normal.
- If it stays stale:
  1. Long-press the widget → **Edit Widget** → confirm any filter is what you expect.
  2. Remove the widget, then re-add it from the widget gallery.
  3. Lock and unlock the device; iOS may schedule a refresh cycle.
- Both small and large widget sizes are supported.

#### Q. How do telecom bundles work?
- Many Korean carriers (SKT, KT, LGU+) bundle services like Netflix, YouTube Premium, or music streaming with their phone plans. SubCheck lets you register a **parent bundle** and attach the included **child services** to it, so you don't accidentally double-pay for a service you already get from your carrier.
- Open a subscription's detail screen and use **Add child / Link to bundle** to group services.

#### Q. Can I track subscriptions billed in foreign currency?
- Yes. When entering the amount you can pick a currency (USD, EUR, etc.). The currency unit is displayed alongside the amount throughout the app. Monthly totals show each currency separately so foreign charges do not get mixed up with KRW.

#### Q. How do discounts work?
- For each subscription you can record a fixed discount (e.g. −2,000 KRW) or a percentage discount (e.g. −20%). The app tracks the **actual amount charged** so monthly spending reflects what really leaves your account.

#### Q. Will there be a way to remove ads?
- The current release of SubCheck is **free with ads** served by Google AdMob. An optional in-app purchase to remove ads is under consideration — it will be announced on this page if it ships. SubCheck does not currently offer a subscription tier of its own.

#### Q. Where is my data stored? Is it sent to a server?
- All subscription data is stored **on your device only**, in SwiftData (Apple's on-device database).
- SubCheck does **not** operate its own server and does **not** transmit subscription information to any external service controlled by the developer.
- If a future release enables iCloud sync, data would sync only inside your own iCloud account (CloudKit Private Database), which the developer cannot access.

#### Q. How do I delete all my data?
- Inside the app: open **Settings → Reset app data** to wipe all subscriptions, or delete each entry individually from its detail screen.
- Deleting the SubCheck app from your iPhone also removes all on-device data.

#### Q. Which iOS version is required?
- iOS 17 or later. The app is built with SwiftUI and SwiftData and uses iOS 17+ APIs for widgets and local notifications.

### Still stuck?
Please email **lovelsh.support@gmail.com** with:
- iOS version
- Device model
- A short description of what you did and what you expected
- Optional screenshot

---

## 한국어

### 자주 묻는 질문

#### Q. 새 구독은 어떻게 등록하나요?
- 대시보드에서 **+** 버튼을 눌러 서비스 이름, 결제 금액, 결제일, 결제 주기(월간/연간), 결제 수단을 한 화면에서 입력하면 됩니다. 카테고리는 OTT, 음악, 쇼핑, 클라우드, 게임, AI, 통신사 제휴, 기타 중에서 선택할 수 있습니다.
- 기본 제공 카탈로그(Netflix, YouTube Premium, Spotify, Apple Music, 멜론, 지니뮤직 등)에서 서비스를 골라 이름과 아이콘을 자동 채울 수도 있습니다.

#### Q. 결제일 알림은 언제 오나요?
- 다가오는 결제일 **하루 전**, 설정에서 지정한 시각에 로컬 알림으로 푸시됩니다.
- 알림이 오지 않는다면 **iOS 설정 → 알림 → SubCheck** 에서 "알림 허용", 배너·사운드·뱃지가 모두 켜져 있는지 확인하세요.
- 알림은 기기 내부에서만 예약되므로 서버 푸시가 아닙니다. 인터넷 연결이 없어도 정상 동작합니다.

#### Q. 홈 화면 위젯이 갱신되지 않아요. 어떻게 해야 하나요?
- 위젯은 구독을 추가·수정·삭제할 때마다 업데이트됩니다. 다만 실제 새로고침 시점은 iOS가 결정하므로 약간의 지연이 발생할 수 있습니다.
- 그래도 오래 멈춰 있다면 아래를 시도해 보세요.
  1. 위젯을 길게 눌러 **위젯 편집** → 필터 설정이 맞는지 확인합니다.
  2. 위젯을 제거한 뒤 위젯 갤러리에서 다시 추가합니다.
  3. 기기를 잠그고 다시 깨워 보세요. iOS가 새로운 새로고침 주기를 잡을 수 있습니다.
- 작은 사이즈와 큰 사이즈 위젯을 모두 지원합니다.

#### Q. 통신사 제휴 묶음은 어떻게 관리하나요?
- SKT·KT·LGU+ 등 통신사 요금제와 함께 제공되는 OTT나 음악 서비스를 **부모 묶음**으로 등록한 뒤 그 안에 **자식 구독**을 연결해 묶어 관리할 수 있습니다. 이렇게 정리해 두면 통신사로 이미 받고 있는 서비스를 따로 또 결제하는 일을 막을 수 있습니다.
- 구독 상세 화면에서 **자식 추가 / 묶음에 연결** 메뉴로 그룹화하세요.

#### Q. 외화로 결제되는 구독도 등록할 수 있나요?
- 네. 금액 입력 시 통화(USD, EUR 등)를 선택할 수 있고 앱 전반에서 통화 단위가 함께 표시됩니다. 월간 합계는 통화별로 분리되어 표시되므로 외화 결제가 원화 합계에 섞이지 않습니다.

#### Q. 할인은 어떻게 적용되나요?
- 구독마다 정액 할인(예: −2,000원) 또는 정률 할인(예: −20%)을 기록할 수 있습니다. 앱은 **실제 결제되는 금액**을 추적하므로 월간 통계가 실제 카드에서 빠져나가는 금액을 그대로 반영합니다.

#### Q. 광고를 제거할 수 있나요?
- 현재 SubCheck는 **무료 + Google AdMob 광고** 모델입니다. 향후 광고 제거 인앱 결제 도입을 검토 중이며, 도입 시 본 페이지에 공지합니다. 본 앱 자체에는 구독형 결제가 없습니다.

#### Q. 입력한 데이터는 어디에 저장되나요? 서버로 전송되나요?
- 모든 구독 데이터는 **이용자 기기 내부**의 SwiftData(Apple 온디바이스 DB)에만 저장됩니다.
- SubCheck는 별도의 자체 서버를 운영하지 않으며, 구독 정보를 운영자가 관리하는 외부 서비스로 전송하지 않습니다.
- 향후 iCloud 동기화가 추가될 경우에도 이용자 본인의 iCloud(CloudKit Private Database) 안에서만 동기화되며, 운영자는 해당 데이터에 접근할 수 없습니다.

#### Q. 모든 데이터를 삭제하려면 어떻게 하나요?
- 앱 안에서 **설정 → 앱 데이터 초기화**로 전체 구독을 한 번에 삭제하거나, 각 구독 상세 화면에서 개별 삭제할 수 있습니다.
- iPhone에서 SubCheck 앱을 삭제하면 기기 내부 데이터도 모두 사라집니다.

#### Q. 어떤 iOS 버전이 필요한가요?
- iOS 17 이상이 필요합니다. SwiftUI / SwiftData / iOS 17+ 위젯·로컬 알림 API를 사용합니다.

### 그래도 해결되지 않는다면
**lovelsh.support@gmail.com** 로 아래 정보와 함께 이메일을 보내 주세요.
- iOS 버전
- 기기 모델명
- 어떤 동작에서 어떤 결과가 나왔는지 짧은 설명
- (선택) 스크린샷
