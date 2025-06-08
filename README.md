
# Premier League 2022/2023 Season Analysis ⚽📊

## Table of Contents
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools Used](#tools-used)
- [Data Cleaning/Preparation](#data-cleaningpreparation)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysiseda)
- [Results/Findings](#resultsfindings)
- [Final Thoughts](#final-thoughts)

---

## Project Overview  
⚽ This project dives into the 2022/2023 Premier League season to unpack stats, trends, and rivalries across all 380 matches. The analysis powers an interactive four-page dashboard designed for fans, analysts, and club strategists alike. From total goals and red cards 🚩 to deep club stats 🧠 and head-to-head duels 🔁—this dashboard captures the spirit of English football in a clean, data-driven format. Whether you're scouting match outcomes, comparing club discipline, or reliving the fiercest fixtures, it's all just a few clicks away.

The dashboard is structured into four distinct analytical views:

### 1️⃣ **PL Page**  
A landing screen introducing the dashboard’s purpose and navigation structure. Clean layout, club branding, and seasonal context help guide the user into the analysis.
![image](https://github.com/user-attachments/assets/30b21727-c88c-4323-8d00-34fa9b756abe)

### 2️⃣ **Overview Page**  
Five key metric cards answer big-picture questions:

- Total Matches Played  
- Total Goals Scored  
- Total Yellow Cards  
- Total Red Cards  
- Average Goals per Match  

Below these sits the official **Premier League Table**, dynamically ranked by points, goal difference, and wins—mimicking the league’s structure.  
![image](https://github.com/user-attachments/assets/eb8756a5-8a58-481f-9d59-1ff3910ce340)

### 3️⃣ **Club Stats Page**  
An interactive breakdown for each team:

Use slicers to choose any club and see their full seasonal stats at a glance.
![image](https://github.com/user-attachments/assets/0305bd55-6e66-43a7-a562-8bcbd6263733)


### 4️⃣ **Head to Head Page**  
A deep dive into any two clubs:

- All matches played between them in the season  
- Total goals, result breakdown (W/D/L)  
- Comparative metrics (shots, fouls, cards)  
- Dynamic logos and names update based on team selection  

This page is perfect for previewing rivalries or reviewing past clashes.
![image](https://github.com/user-attachments/assets/d55b0f4c-52cd-4ffd-b12b-f91fcc99e344)


---

## Data Sources  
- **Match Results**: `epl_results_2022-23.csv` — Includes all 380 matches with details like goals, shots, fouls, and cards.  
- **Club Info**: `epl_clubs_info_2022-23.csv` — Contains club names, abbreviations, hex codes, and logo links used to visually personalize team stats.
  Gotten from [Kaggle](kaggle.com)

---

## Tools Used  
- **Microsoft Excel**: Used for initial inspection, column structuring, and light cleaning.  
- **Power BI**: Used to build the interactive four-page dashboard, incorporating slicers, cards, visuals, and dynamic comparisons.  


---

## Data Cleaning/Preparation  
Before loading into Power BI, I processed the datasets with the following steps:

✅ Standardized date and time into datetime format for sorting and filtering.  
✅ Checked that all 380 fixtures were represented with complete home/away teams, goals, and match stats.  
✅ Verified card counts and referee names to ensure no nulls or inconsistencies.  
✅ Created calculated columns including `Goal Difference`, `Match Outcome`, and `Total Cards`.  
✅ Merged club color/logo data for visual branding across Power BI visuals.  
✅ Built team-level and match-level tables for summary visuals and drill-through functionality.

---

## Exploratory Data Analysis(EDA)  

- How did the season unfold in terms of matches, goals, and overall discipline?

- Which teams dominated the league—and which ones struggled?

- How did individual clubs perform both at home and away?
  
- Which clubs had the most aggressive or disciplined playstyles?

- What happened when any two teams went head-to-head?

- Were there key moments or trends across the season?

---

## Results/Findings  

🏆 **Champion's Form**: *Manchester City* led the table with the most wins and best goal difference, asserting dominance again.  
💥 **Goal Galore**: The league averaged 2.85 goals per match, highlighting a highly attacking season.  
🚩 **Discipline**: *Leeds United* accumulated the highest number of red cards, reflecting a rugged, high-risk playing style.  
🟨 **Yellow Parade**: Mid-table clubs like *Wolves* and *Nottingham Forest* racked up surprising card counts.  
🏠 **Home Advantage**: Home teams won 46% of matches, while away wins made up 30%.  

---

## Final Thoughts

The 2022–23 Premier League season delivered drama, rivalry, and relentless footballing passion—from last-minute screamers to shocking red cards. This dashboard doesn't just crunch numbers—it tells stories. Whether you're reliving the rise of champions, investigating your club's season trajectory, or fueling banter with friends over head-to-head records, it's all here.

With each click, you're not just analyzing data—you're stepping back onto the pitch, re-experiencing the highs, lows, and moments that made this season unforgettable. Football is more than a game—and this dashboard is more than stats. It's a celebration of the beautiful game, one match at a time. ⚽🔥

---
## 👤 Author

**[Sharon Nwajiaku]**  
📧 1sharonbukky@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/sharon-nwajiaku-2a22022b8?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app) | [Portfolio](https://sharon-analytics.github.io/)
