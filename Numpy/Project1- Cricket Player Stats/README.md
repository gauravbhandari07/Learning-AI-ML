# 🏏 ICC Cricket Player Stats — NumPy Analytics Project

This project is a simple and beginner-friendly cricket analytics system built using **NumPy**.  
It reads ICC player statistics from a CSV file, analyzes their performance, classifies players by role, calculates a custom performance score, ranks top players, and exports the final results back into a CSV file — simulating real-world sports analytics workflows.

---

## 📁 Project Structure

icc-cricket-numpy-project/
│
├── data/
│ ├── players_stats.csv # Input dataset (Runs, SR, Avg, Wickets, Economy)
│ └── players_scores.csv # Output file with performance scores
│
├── src/
│ └── analysis.py # NumPy script performing all analysis
│
├── README.md # Project documentation
└── requirements.txt # Dependencies list



yaml
---

## 📊 Features

- Read cricket performance data from CSV  
- Convert CSV data into NumPy arrays  
- Compute averages and identify best performers  
- Classify players as Batsmen, Bowlers, or All-Rounders  
- Apply a weighted scoring formula for performance ranking  
- Rank the top 3 ICC players  
- Export scored results to `players_scores.csv`  
- Clean, professional GitHub-ready structure  

---

## 🚀 Getting Started

### 1. Install Dependencies

```bash
pip install -r requirements.txt
2. Run the Analysis

```bash
cd src
python analysis.py



📂 Input Data Example (players_stats.csv)


Player,Runs,StrikeRate,BattingAverage,Wickets,Economy
Virat Kohli,12000,92,58,4,5.1
Babar Azam,7000,88,56,3,5.4
Rohit Sharma,10000,91,48,8,5.5
Joe Root,6000,87,50,30,4.8
David Warner,6500,95,45,1,5.8
Kane Williamson,6500,86,52,5,4.9
Jasprit Bumrah,250,60,12,300,4.5
Mitchell Starc,500,70,18,200,5.2
Rashid Khan,1100,110,22,350,4.1
Ben Stokes,3000,90,38,120,5.0
🧠 What the Script Does (Summary)
✔ Load CSV into NumPy
Reads player stats and converts them into numeric arrays.

✔ Perform Statistical Analysis
Finds average stats, best strike rate, and most wickets.

✔ Classify Players
Groups players into Batsmen, Bowlers, or All-Rounders using simple logic.

✔ Generate Performance Score
Uses a weighted formula:


Score = (Runs*0.002) + (StrikeRate*0.8) + (BatAvg*1.5)
        + (Wickets*0.5) - (Economy*1.2)


✔ Rank Top Players
Sorts players by the above score and prints the top 3.

✔ Export Results
Saves scores into players_scores.csv for clean reporting.

📈 Output Example (players_scores.csv)

Player,Score
Virat Kohli,208.50
Rashid Khan,199.30
Joe Root,185.20
...





🎯 Why This Project Is Useful
Demonstrates real-world NumPy skills

Teaches CSV import/export workflows

Great starter project for GitHub portfolio

Simple, clean, and easy to understand

Relates to cricket analytics — a popular domain

🤝 Contributing
Contributions, improvements, and suggestions are welcome!

📜 License
This project is licensed under the MIT License.

yaml
---

If you want, I can also generate:  
📌 A **GitHub project banner** image  
📌 A polished `requirements.txt`  
📌 A Markdown **project showcase text for LinkedIn**