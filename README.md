# 📊 Dow Jones Institutional Holder Network Visualization

This project visualizes the network of **institutional investors** and the companies they hold within the **Dow Jones Industrial Average (DJIA)** using real-time financial data.  
It provides insights into which institutions hold stakes in multiple companies and how interconnected the corporate-investor landscape is.

---

## 🧠 What It Does

- Fetches institutional holders of all 30 DJIA companies using [Yahoo Finance](https://finance.yahoo.com/).
- Builds a **bipartite graph** using `NetworkX`, connecting companies and their holders.
- Colors and sizes nodes based on their type and connectivity.
- Visualizes the network using `matplotlib`.

---

## 🛠️ Tech Stack

- **Python 3**
- [`yfinance`](https://pypi.org/project/yfinance/) – Fetch institutional holding data
- [`pandas`](https://pandas.pydata.org/) – Handle dataframes
- [`networkx`](https://networkx.org/) – Build and analyze the graph
- [`matplotlib`](https://matplotlib.org/) – Visualization

---

## 📦 Installation

```bash
git clone https://github.com/codefixxx/dowjones-investor-network.git
cd dowjones-network-graph
pip install -r requirements.txt
```

---

## 🚀 How to Run

```bash
python dow_jones_graph.py
```

*Make sure you are connected to the internet while fetching data.*

---

## 🖼️ Output Preview

The generated graph will:

- 🟥 Highlight companies in **red**
- 🟨 Highlight institutional holders in **yellow**
- 📏 Use edge thickness to reflect **value of shares held**
- 📈 Use node size to reflect **number of connections**

---

## 🗂️ Project Structure

```
dowjones-network-graph/
├── dow_jones_graph.py       # Main Python script
├── requirements.txt         # Python dependencies
├── README.md                # This file
└── LICENSE                  # MIT License
```

---

## 📄 License

This project is licensed under the **MIT License** – see the [LICENSE](./LICENSE) file for details.

---

## 👤 Author

**Your Name**  
GitHub: [@codefixxx](https://github.com/codefixxx)

---

## 🌟 Show Some Love

If you found this project helpful or interesting, feel free to ⭐ star the repo and share it!
