# DementiAnalytics Mobile MVP

## 📱 Speech Analysis Application for Cognitive Health Detection and Monitoring

## About
DementiAnalytics+ is an innovative mobile application designed to assist in monitoring cognitive and emotional health through speech analysis. Using advanced speech recognition and natural language processing, our app provides insights into cognitive patterns by analyzing various aspects of speech, including word usage, emotional tone, and linguistic patterns.

### Key Features
- Real-time speech recording and analysis
- Automatic speech-to-text transcription
- Basic linguistic pattern recognition
- Simple, elderly-friendly interface
- Secure data handling

### Technical Overview
Built with React Native for cross-platform compatibility, the app integrates OpenAI's Whisper for accurate automatic speech recognition, particularly optimized for elderly speech patterns. Our backend, powered by Django, processes the audio data and provides detailed analysis through a secure API.

### Target Users
- Healthcare providers
- Caregivers
- Research institutions
- Healthcare technology organizations

### Vision
Our goal is to create an accessible tool that aids in early detection and monitoring of cognitive health changes, providing valuable insights for healthcare providers and caregivers while maintaining user privacy and data security.

### Project Structure (subject to change)
```
dementianalytics-mobile/
├── src/
│   ├── components/
│   │   ├── AudioRecorder/
│   │   ├── Results/
│   │   └── common/
│   ├── screens/
│   │   ├── Home/
│   │   ├── Recording/
│   │   └── Analysis/
│   ├── services/
│   │   ├── api/
│   │   ├── audio/
│   │   └── analysis/
│   ├── utils/
│   └── config/
├── __tests__/
├── android/
├── ios/
├── docs/
└── assets/
```

### 🚀 Getting Started

1. Clone the repository
```bash
git clone https://github.com/DementiAnalytics/mobile-mvp.git
cd mobile-mvp
```

2. Install dependencies
```bash
npm install
```

3. iOS Setup
```bash
cd ios
pod install
cd ..
```

4. Start the application
```bash
# iOS
npx react-native run-ios

# Android
npx react-native run-android
```

### 📝 Requirements
- Node.js 18+
- React Native CLI
- Xcode (for iOS)
- Android Studio (for Android)
- OpenAI API Key (for Whisper integration)

### 🔧 Environment Setup
Create a `.env` file in the root directory:
```
API_BASE_URL=your_backend_url
OPENAI_API_KEY=your_api_key
```

### 📚 Documentation
- [Project Overview](docs/PROJECT_OVERVIEW.md)
- [Development Guidelines](docs/DEVELOPMENT.md)
- [API Integration](docs/API_INTEGRATION.md)

### 🤝 Contributing
1. Create a new branch for your feature
```bash
git checkout -b feature/your-feature-name
```

2. Commit your changes
```bash
git commit -m "Add: brief description of your changes"
```

3. Push to your branch
```bash
git push origin feature/your-feature-name
```

4. Create a Pull Request

### 📄 License
MIT
