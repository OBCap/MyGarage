# 🚗 My Garage App

A mobile-first car garage management app optimized for iPhone. Single HTML file — no server, no accounts, no subscriptions. Deploy for free on GitHub Pages.

---

## Features

### Garage Overview
- Multiple vehicles with photo, year, make/model, license plate, VIN, color, engine size, and notes
- Add, edit, or delete vehicles at any time

### Per-Vehicle Sections

| Section | What's tracked |
|---|---|
| 🛢 **Oil Changes** | Oil type, volume, drain plug size · service history with date & mileage |
| 🔄 **Tires** | Separate info for Winter and All-Season sets (size, brand, purchase date/price, total mileage) · swap history |
| 🌧 **Wipers** | Driver, passenger, and rear blade sizes · replacement history |
| 🔧 **Repairs** | Date, mileage, notes |
| ⚙️ **Parts** | Date, mileage, part name, price, notes |
| 💳 **Expenses** | Date, mileage, description, price · running total |
| 🚨 **Accidents** | Date, mileage, photos, notes |

### Data Transfer (Import / Export)
- **Export** — saves a complete backup as a `.json` file (includes all data and photos)
- **Replace** — load a backup and replace everything on the current device
- **Merge** — add vehicles from a backup without deleting existing ones; duplicates are skipped automatically

---

## 🚀 Deploy to GitHub Pages (Free Hosting)

### Step 1 — Create a GitHub Account
Go to [github.com](https://github.com) and sign up for a free account if you don't have one.

### Step 2 — Create a New Repository
1. Click **"New"** (green button) on your GitHub dashboard
2. Name it `my-garage` (or anything you like)
3. Set visibility to **Public**
4. Click **"Create repository"**

### Step 3 — Upload the File
1. On your new repo page, click **"uploading an existing file"**
2. Drag and drop `index.html` into the upload area
3. Click **"Commit changes"**

### Step 4 — Enable GitHub Pages
1. Go to your repo → **Settings** tab
2. Click **"Pages"** in the left sidebar
3. Under **Branch**, select `main` and folder `/ (root)`
4. Click **Save**

### Step 5 — Open Your App
After about a minute your app will be live at:
```
https://YOUR-USERNAME.github.io/my-garage/
```

---

## 📱 Add to iPhone Home Screen

For a full-screen, native-app experience:

1. Open your GitHub Pages URL in **Safari**
2. Tap the **Share** button (box with arrow at the bottom)
3. Scroll down and tap **"Add to Home Screen"**
4. Name it **My Garage** and tap **Add**

The app will open without any browser UI, just like a native app.

---

## 🔄 Transferring Data Between Devices

All photos are embedded directly in the backup file, so a single `.json` file is everything you need.

**Moving to a new phone:**
1. Old device → tap **⇅** in the top bar → **Export Backup** → share the file via AirDrop, iCloud, or any messenger
2. New device → open the app → tap **⇅** → **Replace All Data** → select the file

**Keeping two devices in sync:**
1. Export from device A
2. On device B → tap **⇅** → **Merge with Current** → select the file
3. New vehicles are added; existing ones are untouched

---

## 💾 Data Storage & Privacy

All data lives in your browser's **localStorage** — it never leaves your device and is never sent anywhere.

- ✅ Works fully offline after the first load
- ✅ Completely private — no account, no cloud, no tracking
- ⚠️ Clearing browser/Safari data will erase records — use Export regularly to keep a backup
