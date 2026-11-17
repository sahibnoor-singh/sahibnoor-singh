<div align="center">
  <h1>Match'em All</h1>
  <p><b>Tile-matching puzzle with a solvable-board generator</b></p>
</div>

<br/>

## 📌 Overview

**Match'em All** is a tile-matching puzzle for Android (`com.kambogames.matchemall`). It went through Voodoo's CPI testing, and was then reworked for organic Play Store growth: a new level-map home screen, safer monetization and boards that can always be solved.

---

## ✨ Features

- **Solvable boards:** boards are built in reverse, so every level can be completed, and Shuffle keeps the board solvable.
- **Level map home screen** with hearts, coins, a profile avatar, shop, daily reward and spin.
- **Monetization:** AdMob with a consent flow and ad pacing (from level 4, every second level, at least 90 seconds apart), a rewarded "Continue" that undoes three tiles (two per level), and a one-time **Remove Ads** purchase.
- **Levels cycle** after level 50 so players never run out.

---

## 🛠 Tech Stack

- **Engine:** Unity 6, C#
- **Services:** Google AdMob (UMP consent), Unity IAP, Google Play Billing

---

## 📈 Challenges Faced

- **Unwinnable boards and stuck levels:** random icon shuffling could create boards that couldn't be solved. Replaced it with a reverse-built board generator and fixed empty, mismatched and ghost-tile cases.
- **Retention:** the first build had weak return rates. Reworked the home screen, rewards and ad pacing for the next release.

---

## 💡 What I Learned

- Generating puzzles by working backwards from a solved state.
- Balancing ads and purchases without hurting the first-session experience.
