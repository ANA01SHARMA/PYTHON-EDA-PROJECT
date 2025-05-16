# 📊 Street Centerline Dataset Analysis

This project analyzes a city’s street centerline dataset using Python's data science stack (Pandas, NumPy, Seaborn, Matplotlib). It explores key insights such as common street names, segment lengths, responsible authorities, and more.

---

## 📁 Dataset

- **Source:** `Street_Centerline_DATASET_2021.csv`
- **Columns Used:**  
  `ST_NAME`, `LENGTH`, `RESPONSIBL`, `ONEWAY`, `Shape__Length`, `CLASS`

---

## 🎯 Objectives

### ✅ Objective 1: Top 10 Most Common Street Names
- Analyzes street name frequency.
- Displays top 10 most frequently occurring street names with a horizontal bar chart.

### ✅ Objective 2: Top 10 Longest Street Segments
- Identifies the longest street segments by `LENGTH`.
- Uses h-line and point plot to visualize segment lengths.
- Also shows basic stats: `max`, `min`, `mean`.

### ✅ Objective 3: Segment Length Distribution by Responsible Authority
- Shows how street lengths vary across top 8 responsible authorities.
- Uses:
  - Value counts
  - Group statistics (`describe()`)
  - Strip plot with mean markers

### ✅ Objective 4: Street Direction Types
- Analyzes counts of street directions using the `ONEWAY` field (`B`, `T`, `TF`).
- Visualized using a bar chart.

### ✅ Objective 5: Correlation Matrix
- Examines relationships between `LENGTH`, `Shape__Length`, and `CLASS`.
- Visualized using a heatmap.

---

## 🧰 Technologies Used

- **Python 3.x**
- **Libraries:**
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`

---

## 📌 Usage

1. Clone/download this repo.
2. Make sure the dataset CSV path is correct in the script.
3. Run the script:
   ```bash
   python analysis_script.py
