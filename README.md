# 🏀 NBA Player Clustering with KMeans

Ever wondered which NBA players are **Superstars**, **Reliable Starters**, or **Bench Contributors** — based purely on stats?  
This Streamlit app takes regular season stats, crunches the numbers, and **groups players (or teams) into clusters** using PCA + KMeans.  
It's like a scouting report… but for data nerds. 📊

---

## ✨ Features

- **Interactive Clustering** — Choose `k` (number of clusters) and instantly see results.
- **League View or Team View** — Compare entire teams or zoom in to unique players on a single roster.
- **Season Filter** — Analyze a specific year or combine all seasons.
- **Automatic Player Stats Aggregation** — If a player has multiple rows, their stats are averaged for a cleaner profile.
- **Visual Insights** — PCA scatter plots to help you *see* the separation between clusters.

---

## 🚀 How to Download & Run

### 1️⃣ Clone this repo
```bash
git clone https://github.com/<your-username>/nba-kmeans-streamlit.git
cd nba-kmeans-streamlit
```

### 2️⃣ Install dependencies
We keep it simple — only the essentials:
```bash
pip install -r requirements.txt
```

### 3️⃣ Add the dataset
Place your `Regular_Season.csv` in the project root.  
*(This file contains the NBA stats — not included here because it’s chunky 🍔.)*

### 4️⃣ Launch the app
```bash
streamlit run nbaKMeans.py
```
Your browser will open the dashboard automatically.

---

## 🎮 How to Use

1. **Select a Season** — or choose `All` for a full dataset mash-up.
2. **Choose a Team** — or `League` to compare teams instead of players.
3. **Pick Number of Clusters (k)** — Watch as the scatter plot and table update instantly.
4. **Explore the Results** — See which cluster each player or team belongs to.

---

## 💡 Use Cases

- 🏀 **Front Office Analysis** — Group players into tiers for roster planning.
- 📊 **Fan Debates** — Back up your “best bench in the league” hot take with data.
- 🎓 **Sports Analytics Learning** — Understand how PCA + KMeans can reveal structure in real-world data.
- 📰 **Content Creation** — Turn the visualizations into Twitter/X or blog content for NBA fans.

---

## 📸 Sneak Peek
*(Add a screenshot of your Streamlit dashboard here)*  
![NBA KMeans Screenshot](screenshot.png)

---

## 🤝 Contributing
Feel free to fork, tweak, and submit PRs!  
Ideas:  
- Add advanced metrics (PER, BPM, WS)  
- Try different clustering algorithms  
- Create player profiles for each cluster

---

## 📜 License
MIT — Free to use, free to learn from, free to share.

---

**🏀 Data + Machine Learning = New ways to talk hoops.**
