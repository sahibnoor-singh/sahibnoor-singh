<div align="center">
  <h1>Merge'em All</h1>
  <p><b>Merge-and-deliver puzzle game with a level map</b></p>
</div>

<br/>

## 📌 Overview

**Merge'em All** is a merge-and-deliver puzzle for Android (`com.kambogames.mergeemall`). Players merge toys on a board to fill delivery orders, progress through a level map, and collect daily rewards. It went through Voodoo's CPI testing and has since been updated several times for retention and performance.

---

## ✨ Features

- **Merge puzzle with obstacles** (rocks, ice, delivery box) and power-ups.
- **Level map** with locked levels, stars and a scrolling map; later levels are tuned harder using a simulated-player bot.
- **Economy:** fewer free power-ups, daily rewards and a double-reward option, and a one-time **Remove Ads** purchase.
- **Monetization:** AdMob rewarded and interstitial ads with consent.
- **Smaller download:** build size reduced from 100 MB to 76 MB (texture compression and import-setting changes).

---

## 🛠 Tech Stack

- **Engine:** Unity 6, C#
- **Services:** Google AdMob, Google Play Billing

---

## 📈 Challenges Faced

- **Map scrolling felt wrong on phones:** a duplicate scroll view sideways-scrolled the content. Removed it and fixed touch targets and drag thresholds.
- **Out-of-moves flow bugs:** players could get stuck after "give up". Fixed the state handling and text overlap.
- **Download size:** compressed textures and tuned import settings to cut 24 MB.

---

## 💡 What I Learned

- Tuning difficulty with an automated player instead of guesswork.
- Shipping updates safely: version codes, release notes and staged checks.
