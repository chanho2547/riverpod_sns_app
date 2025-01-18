# 🌟 SNS App (Riverpod + Firebase)

Flutter와 Firebase를 사용하여 사람들이 소통할 수 있는 SNS 앱을 제작합니다.  
이 프로젝트를 통해 Flutter와 Firebase 기술에 익숙해지는 것을 목표로 합니다. 🚀

---

## 📋 **주요 기능**
1. 📝 **피드 작성**: 사용자가 텍스트와 이미지를 포함한 피드를 작성할 수 있습니다.
2. 💬 **댓글 기능**: 피드에 댓글을 작성하고 소통할 수 있습니다.
3. ✉️ **DM 기능**: 개인 메시지를 통해 1:1 대화를 나눌 수 있습니다.

---

## 🛠️ **사용 기술**

### **📱 Flutter**
- Riverpod (상태 관리)
- MVVM (아키텍처)

### **☁️ Firebase**
- **Firestore**: 피드 및 댓글 저장
- **Storage**: 이미지 파일 업로드
- **RealTime Database**: 실시간 DM 기능 구현

---

## 📂 **프로젝트 구조**
```
lib/
├── main.dart
├── screens/
│   ├── feed_screen.dart
│   ├── chat_screen.dart
│   ├── settings_screen.dart
│   ├── post_detail_screen.dart
├── widgets/
│   ├── post_item.dart
│   ├── comment_item.dart
├── providers/
│   ├── auth_provider.dart
│   ├── post_provider.dart
│   ├── chat_provider.dart
├── services/
│   ├── firebase_storage_service.dart
│   ├── realtime_database_service.dart
│   ├── firestore_service.dart
├── models/
│   ├── post_model.dart
│   ├── comment_model.dart
│   ├── chat_message_model.dart
└── utils/
    ├── constants.dart
    └── theme.dart
```

---

## 🚀 **실행 방법**

1. Firebase 프로젝트 생성 및 설정:
   - `google-services.json` (Android) 및 `GoogleService-Info.plist` (iOS)를 다운로드하여 프로젝트에 추가합니다.
   - Firebase Authentication, Firestore, Storage, Realtime Database를 활성화합니다.

2. Flutter 프로젝트 실행:
   ```bash
   flutter pub get
   flutter run
   ```

3. **즐겁게 개발하세요!**

---

## 🖼️ **스크린샷**
(추후 생성 예정)

---

## 🤝 **기여 방법**
1. 이 레포지토리를 포크하세요.
2. 새 브랜치를 생성하세요: `git checkout -b feature/my-feature`
3. 변경 사항을 커밋하세요: `git commit -m "Add some feature"`
4. 푸시하세요: `git push origin feature/my-feature`
5. Pull Request를 생성하세요.

---

## 📧 **문의**
프로젝트 관련 질문이나 건의 사항은 언제든지 문의해주세요!  
✉️ 이메일: chanho2547@gmail.com

---

