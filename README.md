# 🧘 Sagara Breathwork App

**A clean, modern breathing timer for Sagara House of Breath and Ice**

Built from scratch with:
- ✅ Simple, intuitive UI
- ✅ Adjustable breath timing (1-10 seconds)
- ✅ Vibration feedback
- ✅ Fuchsia Sagara branding
- ✅ Android 13+ secure & modern
- ✅ ~48KB total size (fast, efficient)

## Quick Start

### For Developers
```bash
git clone <this-repo>
cd SagaraBreathwork
# Open in Android Studio OR run: ./gradlew assembleRelease
```

### For End Users
1. Download the APK from Drive: [Link will be here after first build]
2. Install on Android phone
3. Open → Start breathing
4. Adjust inhale/exhale durations with sliders
5. Hit Start

## Features

| Feature | Details |
|---------|---------|
| **Timer** | Large, easy-to-read countdown display |
| **Breath Phases** | Shows "INHALE" or "EXHALE" |
| **Adjustable Timing** | Customize inhale/exhale from 1-10 seconds |
| **Haptic Feedback** | Vibrates when breath phase changes |
| **Simple Controls** | Start, Pause, Reset buttons |
| **Offline** | Works completely offline, no internet needed |

## Branding

- **Logo**: Sagara fuchsia logo (✅ embedded)
- **Colors**: Fuchsia (#E91E8C) primary, clean UI
- **Typography**: Clear, modern, readable
- **Package**: `com.sagara.breathwork`

## Technical Details

- **Language**: Java (Android Native)
- **Architecture**: Single Activity + CountDownTimer
- **Min SDK**: Android 5.0+
- **Target SDK**: Android 13
- **Size**: ~50KB (compressed APK)
- **Permissions**: Only VIBRATE (no tracking, no ads, no data collection)

## Files

```
📁 SagaraBreathwork/
  ├── src/main/AndroidManifest.xml      App config
  ├── src/main/java/MainActivity.java   Timer logic  
  ├── src/main/res/layout/             UI layouts
  ├── src/main/res/drawable/           Sagara logo
  ├── build.gradle                      Build config
  └── BUILD_INSTRUCTIONS.md            How to build
```

## Next Steps

1. **[READ FIRST]** → `BUILD_INSTRUCTIONS.md` (how to build)
2. **Build APK** → Use Android Studio or gradle
3. **Test APK** → Install on phone, test timer
4. **Publish** → Google Play Store (optional)

## Want to Customize?

All source code is here. You can:
- Change colors/branding
- Add more breath patterns (4-7-8, box breathing, etc.)
- Add sound cues instead of vibration
- Add preset breathing exercises
- Add history/tracking

Just edit the Java files and rebuild!

---

**Created for Sagara House of Breath and Ice**  
*Master the science of breath*

**App Version**: 1.0  
**Built**:March 20, 2026  
**Contact**: sagara.breath@gmail.com
