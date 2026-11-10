# Daily-Challenge
A custom website for Daily Challenges.

A gamified web app that assigns you a unique daily challenge to keep your day interesting! Complete tasks, manage your lives or goals, and win the day before 6:00 PM.

[🔗 **Play the Game Here**](https://jooshiesaur.github.io/Daily-Challenge/)

---

## What It Does

- **Daily Draws:** Generates a new challenge every day with randomized lives or goal targets.
- **Dynamic Hardmode:** Triggers automatically if you don't draw your challenge by 10:00 AM (or by a random 5% chance on early rolls), complete with a high-contrast red & black theme.
- **Interactive Tracking:** Click skulls to deduct lives or checkmarks to track completed goals.
- **Sub-Randomization:** Supports unique sub-tasks and randomized variables (like assigned colors or secret missions).
- **History Log:** Keeps track of past challenges, dates, and win/loss records.

---

## How to Play

1. **Draw Your Task:** Click **"Draw A Challenge"** on the main dashboard after waking up.
2. **Follow the Rules:** 
   - **Lives Mode:** Click the **skull** icon every time you fail or break a rule. Clear the day with at least 1 life remaining to win!
   - **Goal Mode:** Click the **checkmark** as you complete reps toward your daily target number.
3. **Beat the Clock:** Complete your task before **6:00 PM** local time to secure victory (and earn dessert!).

---

## How to Add & Edit Challenges

You don't need to touch any code to customize your game!

1. Open the app in your browser and click on the **Challenge Editor** menu.
2. **Edit Existing Tasks:** Adjust probabilities, default min/max ranges for lives/goals, and HARDMODE descriptions.
3. **Add New Tasks:** Click **"Add Challenge"**, fill in the title, rules, win condition type (Lives vs. Goals), and optional sub-random items.
4. **Save & Export:** 
   - Custom challenges automatically save to your browser's `localStorage`.
   - Use the **Export JSON** button to back up your challenge deck or share it with friends.
