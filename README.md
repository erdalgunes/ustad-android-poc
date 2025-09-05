# Ustad Android POC

> A proof-of-concept Android application for the Ustad learning platform

[![Build Status](https://img.shields.io/badge/build-setup-yellow)](https://github.com/erdalgunes/ustad-android-poc)
[![Version](https://img.shields.io/badge/version-0.1.0-blue)](CHANGELOG.md)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)

## 🚀 Quick Start

```bash
# Clone the repository
git clone https://github.com/erdalgunes/ustad-android-poc.git
cd ustad-android-poc

# Open in Android Studio
# File -> Open -> Select project directory

# Build and run
./gradlew assembleDebug
```

## 📱 About

The Ustad Android POC is a proof-of-concept mobile application designed to explore and validate key technical approaches for the Ustad learning platform on Android devices.

### Key Features (Planned)
- 🔐 User authentication and session management
- 📱 Modern Android UI with Jetpack Compose
- 💾 Offline-capable content delivery
- 🎥 Media playback and interactions
- 📊 Analytics and progress tracking

## 🏗️ Architecture

- **Language**: Kotlin
- **UI**: Jetpack Compose
- **Architecture**: MVVM + Repository Pattern
- **DI**: Hilt
- **Database**: Room
- **Networking**: Retrofit + OkHttp

## 📚 Documentation

Comprehensive documentation is available in our [Project Wiki](wiki/Home.md):

- [📋 Project Overview](wiki/Project-Overview.md) - Goals, features, and timeline
- [⚡ Quick Start Guide](wiki/Quick-Start-Guide.md) - Get up and running quickly
- [🏗️ Architecture Overview](wiki/Architecture-Overview.md) - Technical architecture
- [👨‍💻 Development Guidelines](wiki/Development-Guidelines.md) - Coding standards

## 🛠️ Development

### Prerequisites
- Android Studio Arctic Fox or later
- JDK 11 or higher
- Android SDK 21+ (Android 5.0+)

### Setup
1. Clone the repository
2. Open in Android Studio
3. Sync project with Gradle files
4. Run on device/emulator

For detailed setup instructions, see [Environment Setup](wiki/Environment-Setup.md).

## 🤝 Contributing

We welcome contributions! Please see our:

- [Contributing Guidelines](wiki/Contributing.md)
- [Code Style Guide](wiki/Code-Style-Guide.md)
- [Development Guidelines](wiki/Development-Guidelines.md)

### Reporting Issues
- 🐛 [Bug Report](https://github.com/erdalgunes/ustad-android-poc/issues/new?template=bug_report.yml)
- ✨ [Feature Request](https://github.com/erdalgunes/ustad-android-poc/issues/new?template=feature_request.yml)
- ❓ [General Question](https://github.com/erdalgunes/ustad-android-poc/issues/new?template=general_inquiry.yml)

## 🧪 Testing

```bash
# Run unit tests
./gradlew test

# Run instrumentation tests
./gradlew connectedAndroidTest

# Generate test report
./gradlew jacocoTestReport
```

## 📈 Project Status

| Component | Status |
|-----------|--------|
| Project Setup | ✅ Complete |
| Architecture | 🚧 In Progress |
| Core Features | ⏳ Planned |
| Testing | ⏳ Planned |
| Documentation | ✅ In Progress |

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Ustad Project](https://github.com/UstadMobile) - Parent project
- Android Jetpack Team - For excellent development tools
- Open source community - For inspiration and libraries

---

**Project Lead**: [@erdalgunes](https://github.com/erdalgunes)  
**Created**: 2025-01-05  
**Last Updated**: 2025-01-05