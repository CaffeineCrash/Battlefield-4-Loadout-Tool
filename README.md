# 🎯 BF4 Weapon Lab (Precision Edition)

An advanced gunplay analysis tool and precision visualizer for Battlefield 4, powered by live Sym.gg data.

---

## 🚀 Live Demo
Test the tool live here: https://caffeinecrash.github.io/Battlefield-4-Loadout-Tool/

---

## 📊 Key Features

* **Performance Metrics:** Calculates damage and Time-to-Kill (TTK) to determine if a burst is sufficient to secure a kill at a given range.
* **Recoil & Spread Visualization:** Maps horizontal and vertical recoil drift and spread radius onto a target dummy for real-time feedback.
* **Pacing Analysis:** Evaluates spread and recoil reset times (SDEC/Recoil-Dec) to maintain an efficient firing rhythm.
* **Mechanics Integration:** Applies modifiers for attachments like Bipods, Heavy Barrels, and grips. The Bipod setting automatically disables movement inputs to reflect stationary firing.
* **Dynamic Loadout Suggestions:** Analyzes the weapon's unique recoil profile, distance, and burst size to automatically recommend the optimal barrel and underbarrel attachments.
* **Burst Weapon Support:** The tool automatically detects burst-fire weapons. *Note: Since raw data from Sym.gg may not always include this parameter, you need to manually add the number of shots per burst to the input data (e.g., BurstShots 3).*

---

## 📸 Screenshots & Preview


<img width="1824" height="1010" alt="Screenshot 2026-06-04 120823" src="https://github.com/user-attachments/assets/a9b8db4c-aa40-4359-9d0a-ce877349e062" />


---

## 🛠️ How to Use

1.  Go to **Sym.gg** and look up your favorite Battlefield 4 weapon data.
2.  Copy the raw **ADS** data values.
3.  Paste the data into the **Sym.gg Data Import** box inside the tool and click **Load & Apply Data**.
4.  Adjust the **Distance** and **Shots in Burst** sliders to simulate different gunplay scenarios.
5.  Check the **Loadout Recommendation** box to instantly see the math-proven best attachment setup for that exact scenario!

---

## 🤝 Credits
Special thanks to the **Sym.gg** community for compiling and documenting the hidden weapon mechanics of Battlefield 4.
