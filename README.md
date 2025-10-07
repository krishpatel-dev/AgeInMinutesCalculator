# 🕒 Age in Minutes Calculator 📱

[![Kotlin](https://img.shields.io/badge/Kotlin-100%25-7F52FF?logo=kotlin&logoColor=white)](https://kotlinlang.org/)
[![Android](https://img.shields.io/badge/Android-3DDC84?logo=android&logoColor=white)](https://developer.android.com)
[![Min SDK](https://img.shields.io/badge/min%20SDK-29%2B-34EA6B?logo=android)](https://developer.android.com/about/versions/10)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A beautiful and intuitive Android application that calculates your age in minutes with a modern, material design interface. Built with ❤️ using Kotlin and Android Studio.

## ✨ Features

### 🎨 Modern UI/UX
- 🎯 Clean, minimalistic design with custom color palette
- 📱 Fully responsive layout for all screen sizes
- 🎨 Material Design 3 components
- 🌓 Dark mode ready

### ⚡ Core Functionality
- 📅 Intuitive date picker
- ⚡ Real-time calculation
- 🔄 Automatic updates on date selection
- 📊 Precise minute-by-minute age calculation

### 🛠 Technical Highlights
- 100% Kotlin codebase
- Single Activity architecture
- Lightweight with minimal dependencies
- Optimized for performance

## 🏗 Tech Stack

| Category | Technologies |
|----------|--------------|
| 🏗 **Architecture** | Single Activity |
| 💻 **Language** | Kotlin 1.8+ |
| 📱 **UI** | XML, Material Design 3 |
| 🏗 **Build Tool** | Gradle (Kotlin DSL) |
| 🧪 **Testing** | JUnit, Espresso |

## 📦 Dependencies

```gradle
dependencies {
    implementation("androidx.core:core-ktx:1.12.0")
    implementation("androidx.appcompat:appcompat:1.7.0")
    implementation("com.google.android.material:material:1.12.0")
    implementation("androidx.constraintlayout:constraintlayout:2.2.1")
    
    testImplementation("junit:junit:4.13.2")
    androidTestImplementation("androidx.test.ext:junit:1.2.1")
    androidTestImplementation("androidx.test.espresso:espresso-core:3.6.1")
}
```

## 🚀 Getting Started

### Prerequisites

- Android Studio (Latest version recommended)
- Android SDK 34
- Kotlin plugin (included in Android Studio)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/age-in-minutes-calculator.git
   cd age-in-minutes-calculator
   ```

2. **Open in Android Studio**
   - Select "Open an existing project"
   - Navigate to the cloned directory and select it

3. **Build and Run**
   - Connect an Android device or start an emulator
   - Click "Run" (▶️) or press `Shift + F10`

## 🎨 UI/UX Design

### Color Palette

| Color | Hex | Usage |
|-------|-----|-------|
| Primary | `#2a9d8f` | Buttons, accents |
| Background | `#e9c46a` | App background |
| Text | `#264693` | Primary text |
| Light Grey | `#b7b7a4` | Secondary text |
| White | `#FFFFFF` | Text on buttons |
| Black | `#000000` | Text on light background |

### Screens

1. **Main Screen**
   - Title: "CALCULATE YOUR AGE IN MINUTES"
   - "SELECT DATE" button
   - Selected date display
   - Age in minutes display

## 📁 Project Structure

```
app/
├── src/
│   ├── main/
│   │   ├── java/com/krishhh/ageinmincalculator/
│   │   │   └── MainActivity.kt      # Main application logic
│   │   └── res/
│   │       ├── layout/
│   │       │   └── activity_main.xml # Main UI layout
│   │       ├── values/
│   │       │   ├── colors.xml       # Color definitions
│   │       │   ├── strings.xml      # String resources
│   │       │   └── themes.xml       # App theming
│   └── test/                        # Unit tests
└── build.gradle.kts                 # App level build config
```

## 🧪 Testing

### Running Tests

```bash
# Run all unit tests
./gradlew test

# Run instrumentation tests
./gradlew connectedAndroidTest
```

### Test Coverage

```bash
# Generate test coverage report
./gradlew createDebugCoverageReport
```

## 🤝 Contributing

We love contributions! Here's how to contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 🙏 Acknowledgments

- [Kotlin](https://kotlinlang.org/) - The awesome language used
- [Android Developer Docs](https://developer.android.com/docs) - For amazing documentation
- [Material Design](https://material.io) - For design guidelines

---

Made with ❤️ and ☕ by Krish
