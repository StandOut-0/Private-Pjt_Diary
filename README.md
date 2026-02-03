# Secure Diary App 📝🔐

Flutter로 개발한 **서버리스, 로컬 전용 일기 앱**입니다.  
모든 데이터는 **사용자의 기기 내부에만 암호화되어 저장**되며,
생체 인증을 통해서만 접근할 수 있습니다.

---

## ✨ Features
- iOS / Android 동시 지원 (Flutter)
- 지문 / Face ID 기반 생체 인증
- 서버 없는 완전 로컬 저장 (Hive Encrypted)
- 하루 여러 개의 일기 작성 가능
- 감정 색상 기반 일기 분류
- 월별 캘린더 & 리스트 뷰

---

## 🔐 Security
- 모든 일기 데이터는 **기기 내부에만 저장**
- 암호화 키는 `flutter_secure_storage`에 보관
- 앱 삭제 시 데이터는 복구 불가 (의도된 보안 설계)

---

## 🛠 Tech Stack
- Flutter / Dart
- local_auth
- Hive (Encrypted)
- Riverpod
- table_calendar

---

## 📱 Screens
- Calendar View
- Diary List View
- Diary Detail View

---

## 🚧 Notes
- 본 앱은 서버를 사용하지 않으며, 데이터 백업 기능은 제공하지 않습니다.
- 개인 프라이버시 보호를 최우선으로 설계되었습니다.
