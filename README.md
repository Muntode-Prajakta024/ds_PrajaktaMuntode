# 🧠 Data Science Project – Bitcoin Sentiment & Trader Performance Analysis

## 📄 Overview
This project explores the relationship between **Bitcoin market sentiment (Fear & Greed Index)** and **trader performance metrics** derived from historical trading data.
The goal is to uncover patterns in how emotions like *fear* or *greed* influence trading behavior and profitability.

---

## 📊 Datasets

### 1. Fear & Greed Index (`fear_greed_index.csv`)
| Column | Description |
|---------|-------------|
| `Date` | Date of the sentiment reading |
| `Classification` | Market emotion (e.g., Fear, Greed, Neutral) |
| `Value` | Numerical index representing sentiment intensity |

### 2. Historical Trader Data (`historical_data.csv`)
| Column | Description |
|---------|-------------|
| `account` | Trader ID |
| `symbol` | Cryptocurrency symbol |
| `execution_price` | Trade execution price |
| `size` | Trade size |
| `side` | Buy/Sell direction |
| `timestamp` | Time of trade |
| `closedPnL` | Profit or Loss from trade |
| `leverage` | Leverage used |

---

## 🧩 Analysis Steps

1. **Data Cleaning**
   - Converted numerical columns and handled missing data
   - Merged both datasets based on date

2. **Exploratory Data Analysis (EDA)**
   - Visualized sentiment trends and trader activity
   - Identified correlation between sentiment and profitability

3. **Insights Generation**
   - Assessed how *fear* vs *greed* periods affect overall PnL
   - Compared high-leverage vs low-leverage performance

---

## 🚀 Results & Insights

- Traders tend to take **higher leverage positions during “Greed” periods**, often resulting in volatile returns.
- **Fear periods** show lower activity but more consistent performance among disciplined traders.
- Market sentiment has a **lagging yet predictive effect** on trading profitability.

---

## 🛠️ Tools & Libraries

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Google Colab
- CSV datasets (local analysis)

---

## 👩‍💻 Author

**Prajakta Muntode**  
Data Analyst | Aspiring Data Scientist  
📧 prajaktamuntode76@gmali.com





