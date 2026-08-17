# ⚡ QUICK START - Get APK in 15 Minutes

**Goal:** Get your app on your phone by tonight 🔥

---

## 🚀 5-Step Process (Easiest Way)

### STEP 1: Download Node.js (2 minutes)
1. Go to https://nodejs.org/
2. Click "LTS" (Long Term Support) - latest version
3. Download and install
4. Restart your computer

**Verify:** Open terminal/command prompt, type:
```
node -v
```
Should show a version number like `v18.x.x`

---

### STEP 2: Install Tools (3 minutes)
Open terminal and paste these commands one by one:

```bash
npm install -g eas-cli
npm install -g expo-cli
```

Wait for each to finish (you'll see "added X packages").

---

### STEP 3: Create Your Project (2 minutes)
```bash
# Create folder
mkdir anand-schedule
cd anand-schedule

# Install dependencies
npm install
```

Then **copy these 3 files into the folder:**
- `App.js`
- `app.json`
- `package.json`

(All provided to you)

---

### STEP 4: Create Free Expo Account (2 minutes)
1. Go to https://expo.dev
2. Click "Sign Up"
3. Create account with email/password
4. Verify your email

Back in terminal:
```bash
expo login
# Enter email and password
```

---

### STEP 5: Build APK (5 minutes setup + 10 mins building)
```bash
eas init --id anand-schedule-app
eas build --platform android
```

**Wait!** Building happens in the cloud.
- Takes 10-15 minutes
- You'll get an email with download link
- Download the `.apk` file
- Send to phone or download directly
- Install on phone
- Done! 🎉

---

## 📱 Install APK on Phone

1. Download APK file to phone (or email yourself the link)
2. Open file
3. Tap "Install"
4. Allow unknown apps if prompted
5. Open "Anand's Schedule"

---

## 🧪 Test First (OPTIONAL BUT RECOMMENDED)

Before building APK, test on your phone:

1. In terminal, go to your project folder
2. Run:
```bash
expo start
```

3. Download "Expo Go" app on your phone (from Play Store)
4. Open Expo Go, tap "Scan QR code"
5. Scan code from terminal
6. App loads instantly!

Test everything works, then build APK.

---

## ⚡ If Any Step Fails

| Problem | Fix |
|---------|-----|
| "npm not found" | Download Node.js from nodejs.org |
| "expo login failed" | Check internet, verify email |
| Build fails | Run `npm cache clean --force` then retry |
| Can't find downloaded APK | Check email for build link, or download from https://expo.dev/build |

---

## 🎯 What You'll Have

✅ **Native Android APK**
- Works offline
- Fast performance
- All features included
- Can share with friends
- Installable on any Android phone

✅ **Full Functionality**
- 📅 Daily Schedule (all times)
- 📚 Subject Strategy (weak & strong)
- 🎯 Shooting Practice Logger
- ✅ Habit Tracker with progress

✅ **Your Data**
- Saves locally (no cloud)
- Persistent between sessions
- Private (only on your phone)

---

## 💡 Pro Tips

1. **First time?** Do Step 3 (test in Expo Go) before building APK
2. **Fast internet needed** for downloading Expo Go and building
3. **Keep APK file** - can reinstall anytime
4. **Share with friends** - send them the APK file

---

## 🔥 After Building

1. **Install on phone**
2. **Open at 5 AM tomorrow**
3. **Start checking off habits**
4. **Log shooting sessions**
5. **Do ONE scary thing at 9:30 PM**
6. **Journal at 9:45 PM**

---

## 📞 Stuck?

Most common issues:

**"npm install fails"**
- Run: `npm cache clean --force`
- Then: `npm install` again

**"Expo login not working"**
- Check internet connection
- Verify you created account at expo.dev
- Try logging out: `expo logout` then `expo login`

**"Build takes forever"**
- First build takes 15 mins (normal)
- Subsequent builds faster
- Don't close terminal while building

**"Can't find download link"**
- Check your email (Expo sends build link)
- Or go to https://expo.dev → Build
- Log in with your account to see builds

---

## ✨ Next Level (After Testing)

Once APK is working perfectly:
- Modify `App.js` with your changes
- Rebuild APK with new changes
- Share updated version

All your habits and data persist even after updates!

---

## 🎯 You're Ready!

You have everything:
- ✅ React Native App (App.js)
- ✅ Configuration files
- ✅ Build instructions
- ✅ Support docs

**Start with Step 1 NOW.** 

By tonight you'll have a functioning APK on your phone. 🚀

---

## 🔥 Remember Your 8-8-1 Alignment

This app is built to track your transformation daily.

- **Life Path 8** = Building your power
- **Age 17 = 8** = Your peak moment
- **Year 1** = Starting something new

**Use this app to manifest your Phoenix rising.** 

Track daily. 💪

---

**Questions?** Re-read the BUILD_GUIDE.md for detailed explanations.

**Ready?** Start Step 1 now! ⚡
