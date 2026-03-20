# Sagara Breathwork - Build Instructions

## Overview
This is a clean, modern Android breathing timer app built from scratch, branded for Sagara House of Breath and Ice.

**Features:**
- Simple, intuitive breathing timer interface
- Adjustable inhale/exhale durations (1-10 seconds)
- Vibration feedback between breath cycles
- Fuchsia Sagara branding
- Modern Android 13+ compatible

## Build Methods

### Option 1: Android Studio (Recommended)
1. **Download & Install Android Studio**
   - Download from https://developer.android.com/studio
   - Install Java 11 or higher

2. **Open Project**
   - File → Open → Select `SagaraBreathwork` folder
   - Wait for Gradle sync to complete

3. **Build & Sign APK**
   - Build → Generate Signed Bundle/APK
   - Create new keystore (or use existing)
   - Select release build
   - APK will be in `app/release/`

### Option 2: Command Line (Linux/Mac)
```bash
# Install Android SDK (if not already installed)
# Then set ANDROID_HOME environment variable

# Clone/Download this project
cd SagaraBreathwork

# Build APK
./gradlew assembleRelease

# Output: app/build/outputs/apk/release/app-release.apk
```

### Option 3: Online Build Service
If you don't have Android Studio, use a free online service:
1. Go to https://gradleapp.github.io/
2. Upload this entire `SagaraBreathwork` folder
3. Download the signed APK

## Project Structure
```
SagaraBreathwork/
├── src/main/
│   ├── AndroidManifest.xml          (App permissions & configuration)
│   ├── java/
│   │   └── com/sagara/breathwork/
│   │       └── MainActivity.java     (Breathing timer logic)
│   └── res/
│       ├── drawable/                 (Sagara logo)
│       ├── layout/                   (UI layout)
│       └── values/                   (Strings, colors, styles)
├── build.gradle                       (Build configuration)
└── settings.gradle                    (Gradle settings)
```

## Customization

### Change App Name
Edit `src/main/res/values/strings.xml`:
```xml
<string name="app_name">Your App Name</string>
```

### Change Logo/Icon
Replace `src/main/res/drawable/ic_launcher.png` with your image

### Change Colors
Edit `src/main/res/values/colors.xml`:
```xml
<color name="sagara_fuchsia">#E91E8C</color>
```

### Change Default Timer Duration
Edit `MainActivity.java`:
```java
private int inhaleDuration = 4;  // Change to your desired value
private int exhaleDuration = 4;  // Change to your desired value
```

## Requirements
- **Minimum SDK**: Android 5.0+ (API 21)
- **Target SDK**: Android 13 (API 33)
- **Java**: Version 11+

## APK Installation
Once built, transfer the APK to your Android device and:
1. Enable "Unknown Sources" in Settings
2. Open the APK file
3. Install

## Support
For issues or customization, contact Mark @ sagara.breath@gmail.com

---
**Version:** 1.0  
**Branding:** Sagara House of Breath and Ice  
**Website:** sagarabreathandice.com
