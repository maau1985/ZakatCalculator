# Zakat Calculator - Installation Guide

## 📱 How to Install on Your Phone

This is a Progressive Web App (PWA) that works like a native app on your phone!

### Method 1: Using a Web Server (Recommended)

1. **Upload all files to a web hosting service**
   - You can use free hosting like:
     - GitHub Pages (free)
     - Netlify (free)
     - Vercel (free)
     - Any web hosting service

2. **Install on Android:**
   - Open the website URL in Chrome
   - Tap the menu (3 dots) → "Add to Home screen"
   - Or tap the "Install" button that appears at the top
   - The app will be added to your home screen

3. **Install on iPhone:**
   - Open the website URL in Safari
   - Tap the Share button (square with arrow)
   - Scroll down and tap "Add to Home Screen"
   - Tap "Add" in the top right

### Method 2: Local Server (For Testing)

If you want to test it locally first:

1. **Using Python (if installed):**
   ```bash
   cd zakat-calculator-app
   python3 -m http.server 8000
   ```
   Then open http://localhost:8000 in your browser

2. **Using any local server:**
   - Open the folder in VS Code
   - Use "Live Server" extension
   - Or use any other local development server

### Free Hosting Setup (GitHub Pages)

**Easiest method - Takes 5 minutes:**

1. Create a free GitHub account at https://github.com
2. Create a new repository (call it "zakat-calculator")
3. Upload all files from the `zakat-calculator-app` folder
4. Go to Settings → Pages
5. Under "Source", select "main" branch
6. Click Save
7. Your app will be live at: `https://yourusername.github.io/zakat-calculator`

## 📋 Files Included

- `index.html` - Main app file
- `manifest.json` - App configuration
- `sw.js` - Service worker for offline support
- `icon-192.png` - App icon (192x192)
- `icon-512.png` - App icon (512x512)

## ✨ Features

✅ **Works Offline** - Once installed, works without internet
✅ **Saves Your Data** - All calculations saved automatically
✅ **Add/Remove People** - Manage family members easily
✅ **Adjustable Settings** - Change gold rate, adjustment %, Zakat rate
✅ **Real-time Calculations** - Updates instantly as you type
✅ **Mobile Optimized** - Designed specifically for phones

## 🎯 How to Use

1. **Set Gold Rate**: Enter current 22-carat gold price per gram
2. **Adjust Settings**: 
   - Value Adjustment % (default 85% for making charges)
   - Zakat Rate % (default 2.5%)
3. **Manage People**:
   - Click "Add Person" to add new family members
   - Enter gold weight in grams for each person
   - Delete people using the Delete button
4. **View Summary**: Total Zakat appears at the bottom

## 💾 Data Storage

- All data is stored locally on your phone
- Nothing is sent to any server
- Data persists even when you close the app
- Completely private and secure

## 🔄 Updates

To update the app in the future:
- Just replace the files on your web server
- The app will auto-update on next visit

## 🆘 Troubleshooting

**App won't install:**
- Make sure you're using HTTPS (required for PWA)
- Try using Chrome on Android or Safari on iPhone
- Clear browser cache and try again

**Data not saving:**
- Check if browser allows local storage
- Try reinstalling the app

**App not working offline:**
- Make sure you opened it at least once with internet
- Service worker needs initial installation

## 📞 Support

If you need help, the app is self-contained and simple:
- All code is in index.html
- You can modify it directly
- No backend or database required
- Just HTML, CSS, and JavaScript

---

## 🎨 Customization

Want to customize colors or features?
Edit the `index.html` file:

- **Change colors**: Look for color codes like `#667eea`
- **Change default values**: Find the values in the JavaScript section
- **Add more people by default**: Edit the `people` array in JavaScript

Enjoy calculating your Zakat! 🌙
