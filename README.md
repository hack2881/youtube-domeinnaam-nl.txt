# YouTube AdGuard Filter List

## 📌 Overview

This repository contains a **complete AdGuard setup for YouTube**, designed to:

* ✅ Keep YouTube fully functional
* 🚫 Block as many ads as possible
* ⚖️ Maintain the perfect balance between usability and blocking

This setup is **not just a blocklist** — it is a **combination of a whitelist and a blocklist**, which must be used **together** for optimal performance.

---

## ⚠️ Important

Using only one of the lists will NOT give the best results:

* ❌ Only blocklist → Videos may break or not load
* ❌ Only whitelist → Ads will return
* ✅ Both combined → Best experience (recommended)

---

## 📂 Included Lists

### 1. Whitelist (Essential Allow Rules)

This list ensures that critical YouTube services are allowed, such as:

* Video streaming
* Thumbnails
* API requests

Without this, YouTube may not work correctly.

---

### 2. Blocklist (Ad & Tracking Blocker)

This list blocks:

* YouTube ads (pre-roll, mid-roll)
* Google Ads endpoints
* Tracking and telemetry

---

## 🚀 Installation

### Method 1 — Direct (Recommended)

1. Open **AdGuard**
2. Go to **Filters → Custom filters**
3. Click **Add filter by URL**
4. Add your RAW GitHub links:

blocklist
https://raw.githubusercontent.com/hack2881/youtube-domeinnaam-nl.txt/refs/heads/main/domeinnaam.txt

whitelist
https://raw.githubusercontent.com/hack2881/youtube-domeinnaam-nl.txt/refs/heads/main/youtube-whitelist

### Method 2 — Manual

1. Copy the contents of the list
2. Paste into **AdGuard → User rules**

---

## 🔄 Updates

This list should be updated regularly because:

* YouTube frequently changes ad delivery methods
* New ad domains and endpoints appear

---

## 📊 Expected Results

| Platform       | Effectiveness                 |
| -------------- | ----------------------------- |
| Desktop        | ⭐ 90–100% ad-free             |
| Mobile Browser | ⭐ 80–95%                      |
| YouTube App    | ⚠️ 70–90% (limited by Google) |

---

## 🔥 Recommended Setup (Best Experience)

For near 100% ad blocking, combine this with:

* AdGuard DNS
* Alternative clients like:

  * YouTube ReVanced
  * NewPipe

---

## 🤝 Contributing

Feel free to:

* Report broken rules
* Suggest new filters
* Submit pull requests

---

## ⚖️ Disclaimer

This project is for educational and personal use.
YouTube may change its systems at any time, which can affect effectiveness.

---

## ⭐ Final Note

This setup is designed as a **balanced system**, not an aggressive blocker.

👉 The whitelist and blocklist are **meant to work together** — do not separate them.
