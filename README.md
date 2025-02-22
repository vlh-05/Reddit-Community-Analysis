# Community and Influence Detection Using Reddit API 🚀

## 📌 Overview
This project explores **community structures and influential users** within Reddit subreddits using **network analysis**. By analyzing user interactions via the **Reddit API**, we aim to understand **how information spreads, how communities form, and who the key influencers are**.

Using **Python** and libraries like **NetworkX, PyVis, and PRAW**, this project constructs a **network graph** where:
- **Nodes** represent users
- **Edges** represent interactions (comments/replies)

The study also implements **PageRank, Louvain Community Detection, and Centrality Metrics** to analyze the dynamics of Reddit communities.

---

## 📂 Project Structure


---

## 🛠️ Tech Stack
- **Python** 🐍
- **PRAW (Python Reddit API Wrapper)** 🔗
- **NetworkX (Graph Analysis)** 📊
- **PyVis (Interactive Visualizations)** 🎨
- **Matplotlib (Data Visualization)** 📈
- **Pandas (Data Processing & Analysis)** 📑

---

## 📊 Methodology
### 🔹 **Data Collection**
- Extracted data from **'AskReddit' subreddit** using **Reddit API**.
- Collected **top 10 hottest posts and all their comments**.
- Constructed a **user interaction graph**.

### 🔹 **Network Analysis**
- **Community Detection**: **Louvain Method** to identify community structures.
- **Influence Detection**: **PageRank Algorithm** to find top influencers.
- **Graph Metrics Computed**:
  - **Degree Distribution** (Number of connections per user)
  - **Betweenness Centrality** (User’s role in connecting others)
  - **Closeness Centrality** (How fast information spreads from a user)
  - **Eigenvector Centrality** (How influential a user is in their network)
  - **Clustering Coefficient** (Likelihood of forming clusters)

---

## 📊 Results
1️⃣ **Top Influencers Identified** using PageRank  
2️⃣ **Community Structures Visualized** using Louvain Method  
3️⃣ **Interactive Network Graph** created using **PyVis**  
4️⃣ **Tabular Metrics Report** generated in `network_centrality_metrics.csv`  

✅ **Preview of Top Influential Users (PageRank Score)**
| User      | PageRank | Betweenness | Closeness | Eigenvector | Clustering |
|-----------|---------|------------|-----------|-------------|------------|
| User_A    | 0.0254  | 0.0034     | 0.5678    | 0.4231      | 0.65       |
| User_B    | 0.0249  | 0.0029     | 0.5402    | 0.3897      | 0.60       |

✅ **Interactive Network Graph**
- **[View Interactive Graph](./reddit_network.html)** (Open in Browser)

---

## 🚀 How to Run the Project
### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/<your-username>/Reddit-Community-Analysis.git
cd Reddit-Community-Analysis
```
### **2️⃣ Install Dependencies**
```bash
# Create a virtual environment (optional but recommended)
python -m venv venv

# Activate virtual environment
# On Windows (Command Prompt)
venv\Scripts\activate

# On Windows (PowerShell)
venv\Scripts\activate.ps1

# On macOS/Linux
source venv/bin/activate

# Install required dependencies
pip install -r requirements.txt

# Verify installation
pip freeze

```
### **3️⃣ Run the Python Script
```bash
python reddit_analysis.py
```
### **4️⃣ View the Outputs**
- **Interactive Network Graph:** Open `reddit_network.html`
- **Degree Distribution Plot:** `degree_distribution.png`
- **Tabular Data:** Open `network_centrality_metrics.csv` in Excel

---

## 🔍 **Future Improvements**
✅ Expand to **multiple subreddits** for cross-community analysis  
✅ Implement **real-time data tracking** for evolving Reddit discussions  
✅ Apply **Natural Language Processing (NLP)** for **sentiment analysis & topic modeling**  

---

## 📜 **References**
- [PRAW (Python Reddit API)](https://praw.readthedocs.io)
- [NetworkX Graph Analysis](https://networkx.org/)
- [PyVis for Interactive Visualizations](https://pyvis.readthedocs.io)

---

## ⭐ **Contributing**
Feel free to **fork the repository** and submit **pull requests** if you want to improve this project! 🎯

