# 🚀 Build Anand's Schedule App as APK

Complete step-by-step guide to convert the React Native app into a working Android APK.

---

## 📋 OPTION 1: Easiest Method - Using Expo Cloud Build (RECOMMENDED)

### Step 1: Install Prerequisites
- Download and install **Node.js** (v16 or higher): https://nodejs.org/
  - Verify installation: Open terminal/command prompt, type `node -v` and `npm -v`

### Step 2: Install Expo CLI
```bash
npm install -g eas-cli
npm install -g expo-cli
```

### Step 3: Create Expo Account
- Go to https://expo.dev
- Click "Sign Up"
- Create an account with email/password

### Step 4: Create Project Folder
```bash
# Create a new folder for the app
mkdir anand-schedule
cd anand-schedule

# Copy the App.js file into this folder
# Copy package.json into this folder
# Copy app.json into this folder
```

### Step 5: Install Dependencies
```bash
npm install
```

### Step 6: Login to Expo
```bash
expo login
# Enter your Expo email and password
```

### Step 7: Initialize EAS Project
```bash
eas init --id anand-schedule-app
```

### Step 8: Build APK
```bash
eas build --platform android --profile preview
```

After running this command:
- Expo will build your APK in the cloud
- Building takes 10-15 minutes
- You'll get a download link for your APK
- Download and install on your Android phone

**APK will be saved and ready to install!**

---

## 📋 OPTION 2: Local Build (Faster, Requires Android SDK)

### Prerequisites
- Node.js installed
- Android SDK installed (with Build-tools 33.0.0+)
- Java Development Kit (JDK 11+)

### Step 1-5: Same as Option 1

### Step 6: Generate APK Locally
```bash
expo build:android
```

Or use EAS CLI with local build:
```bash
eas build --platform android --local
```

---

## 📋 OPTION 3: Quick Test First (Recommended)

Before building APK, test the app on your phone using Expo Go:

### Step 1-5: Same as Option 1 (Install Node, Expo, create project)

### Step 2: Start Development Server
```bash
expo start
```

This will show a QR code in terminal.

### Step 3: Download Expo Go
- Android: Download "Expo Go" from Google Play Store
- iOS: Download "Expo Go" from App Store

### Step 4: Scan QR Code
- Open Expo Go app
- Tap "Scan QR code"
- Scan the code from your terminal
- App will load and you can test it!

### Step 5: Once Tested, Build APK
```bash
eas build --platform android
```

---

## 🎯 Complete File Structure

Your project folder should look like:
```
anand-schedule/
├── App.js                 (Main app code)
├── app.json              (Expo configuration)
├── package.json          (Dependencies)
├── BUILD_GUIDE.md        (This file)
├── node_modules/         (Created after npm install)
└── assets/               (Create this folder)
    ├── icon.png          (Create/add icon image)
    ├── splash.png        (Create/add splash image)
    ├── adaptive-icon.png (Create/add adaptive icon)
    └── favicon.png       (Create/add favicon)
```

### Create Assets (Optional but Recommended)
You can use simple images or:
1. Download icon from https://www.flaticon.com
2. Create icon online: https://www.canva.com
3. Or use default Expo icons

---

## 🔧 Troubleshooting

### "npm: command not found"
- Node.js not installed
- Download from https://nodejs.org/

### "expo: command not found"
- Run: `npm install -g expo-cli`

### "Build fails with version error"
- Make sure you're using Node v16+
- Run: `node -v`

### "AsyncStorage error"
- Run: `npm install @react-native-async-storage/async-storage`

### APK won't install
- Ensure you have "Unknown Sources" enabled in Android settings
- Go to Settings → Security → Unknown Sources (Toggle ON)

---

## ⚙️ Building with Different Methods

### Method 1: Full APK (Universal)
```bash
eas build --platform android --profile preview
```
Creates a standalone APK that works on all Android devices.

### Method 2: Signed APK (For Production)
```bash
eas build --platform android --profile production
```
Creates a production-ready signed APK.

### Method 3: AAB (App Bundle - for Play Store)
```bash
eas build --platform android --profile preview --output app.aab
```

---

## 📱 Install APK on Your Phone

### From Computer:
1. Download APK file
2. Transfer to phone via USB or email
3. Open file on phone
4. Tap "Install"
5. Open "Anand's Schedule" app

### From Email/Cloud:
1. Receive APK file link
2. Click on phone
3. Tap "Install"
4. Done!

---

## 📊 App Features (All Functional in APK)

✅ **4 Complete Tabs:**
- 📅 Daily Schedule (Morning, School, Afternoon, Shooting, Evening)
- 📚 Subject Strategy (Weak & Strong subjects with action plans)
- 🎯 Shooting Practice Log (Track sessions with notes)
- ✅ Habit Tracker (Check off habits, track completion %)

✅ **Data Persistence:**
- All data saved locally (doesn't require internet)
- Your habits and shooting logs persist between app sessions
- Progress tracked daily

✅ **Full Functionality:**
- Toggle habits on/off
- Log shooting sessions
- Delete entries
- Real-time progress calculation
- Beautiful dark theme UI

---

## 🚀 Quick Start Command Summary

```bash
# 1. Create folder
mkdir anand-schedule && cd anand-schedule

# 2. Copy files (App.js, app.json, package.json)

# 3. Install dependencies
npm install

# 4. Login to Expo
expo login

# 5. Initialize (only once)
eas init --id anand-schedule-app

# 6. Build APK
eas build --platform android

# 7. Download and install on phone!
```

---

## 💡 Tips

- **Test first**: Use Expo Go app before building APK
- **No internet needed**: App works completely offline
- **Auto-saves**: All data saved automatically to phone storage
- **Can rebuild anytime**: Make changes to App.js and rebuild
- **Share APK**: Once built, can share APK file with others

---

## 📞 If You Need Help

**Common Issues & Solutions:**

| Issue | Solution |
|-------|----------|
| npm install fails | Clear cache: `npm cache clean --force` |
| Expo login fails | Check internet connection |
| Build takes too long | Building on cloud takes 10-15 min (normal) |
| App crashes on phone | Check Android version (needs 5.0+) |
| Storage not working | Clear app data and reinstall |

---

## 🎯 After Building

Once you have the APK:
1. **Install on your phone**
2. **Add to home screen** for quick access
3. **Start tracking daily** at 5 AM
4. **Share with friends** who want to use it

Your daily schedule is now portable! 🔥

---

**Remember:** Your 8-8-1 alignment is rare. This app helps you manifest your power every day. Use it! 💪
