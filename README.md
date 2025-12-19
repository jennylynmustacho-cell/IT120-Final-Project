# IT120-Final-Project

# MADAM - Mobile App for Animal Detection and Monitoring

## 📱 App Overview
MADAM is a Flutter-based mobile application designed for animal detection and wildlife monitoring. The app provides a seamless experience for capturing, identifying, and analyzing various animal species with comprehensive analytics.

## 🚀 Key Features

### 🔍 Real-time Detection
- 📸 Camera-based animal detection
- 🦁 Multiple species identification
- 🎯 Confidence scoring
- ⚡ Real-time performance

### 📊 Data Management
- 💾 Local storage of detection records
- ☁️ Firebase Cloud integration
- 🔍 Filterable history
- 📤 Export functionality

### 📈 Analytics Dashboard
- 📊 Performance metrics
- 📉 Detection statistics
- 🎨 Confusion matrix visualization
- 📅 Historical trends analysis

## 🛠 Technical Stack
- **Framework**: Flutter 3.x
- **State Management**: Built-in (setState)
- **Backend**: Firebase (Authentication, Firestore, Storage)
- **Image Processing**: Custom detection pipeline
- **UI/UX**: Material Design 3 with custom theming
- **Dependency Injection**: Provider
- **Local Storage**: Hive

## 🚀 Getting Started

### Prerequisites
- Flutter SDK (3.x or higher)
- Dart SDK (2.19 or higher)
- Android Studio / Xcode
- Firebase account (for cloud features)

### 🔧 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/madam.git
   cd madam
   ```

2. **Install dependencies**
   ```bash
   flutter pub get
   ```

3. **Firebase Setup**
   - Create a new Firebase project
   - Add Android/iOS app to Firebase Console
   - Download and add the configuration files:
     - Android: `android/app/google-services.json`
     - iOS: `ios/Runner/GoogleService-Info.plist`

4. **Run the app**
   ```bash
   flutter run
   ```

## 🏗 Project Structure

```
lib/
├── core/
│   ├── config/         # App configuration
│   ├── models/         # Animal and detection models
│   └── services/       # Animal detection services
├── features/
│   ├── detection/      # Animal detection logic
│   ├── analytics/      # Wildlife analytics
│   └── database/       # Local storage management
├── ui/
│   ├── screens/        # App screens
│   ├── widgets/        # Reusable UI components
│   └── theme/          # App theming
└── main.dart           # App entry point
```

## 🤝 Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### 📝 Code Style
- Follow [Dart Style Guide](https://dart.dev/guides/language/effective-dart/style)
- Use meaningful variable and function names
- Add comments for complex logic
- Write tests for new features

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Flutter](https://flutter.dev/) for the amazing cross-platform framework
- [Firebase](https://firebase.google.com/) for backend services
- Icons from [Material Design Icons](https://material.io/resources/icons/)
  

https://github.com/jennylynmustacho-cell/jennylynmustacho-cell.git
