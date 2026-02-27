# 🛡️ Flunk-Safe
**The ultimate contingency planner for academic targets.**

Stop guessing and start calculating. Flunk-Safe is a browser-based tool designed to remove the "finals anxiety" by showing you exactly what marks you need to hit your target percentage.

## Features
- **Brute-Force Calculation:** Input current scores and pending max marks to see your required average.
- **🛡️ Safe-Zone Visuals:** Instant feedback on how realistic your goals are.
- **Interactive Sliders:** 0.5-unit precision for granular mark tracking.
- **Expected Scores Sidebar:** Project your scores for upcoming tests separately to see where you'll land.
- **Local Persistence:** Data is saved to your browser's `localStorage`—no login, no data loss.

## The Logic
Flunk-Safe uses weighted deficit math:
1. **Total Max:** Sum of all subject maximum marks.
2. **Target Floor:** `Total Max * (Target % / 100)`.
3. **The Deficit:** `Target Floor - Current Scored Marks`.
4. **The Goal:** `Deficit / Remaining Max Marks`.

## How to Use
1. Download `index.html`.
2. Open it in any browser.
3. Input your target (e.g., 90%).
4. Add your subjects and slide the bars to your current marks.
5. Get your required score for the remaining subjects instantly.

## Contribution
Found a bug or have a feature idea? Open an issue or submit a pull request.
