# QuantenMarkov-Trend

A **quantum-inspired Markov trend model** for financial market analysis.  
QuantenMarkov-Trend combines discrete market regime classification with quantum-inspired probabilistic modeling to visualize and analyze market dynamics.

---

## 🚀 Overview

- **State Assignment:** Each time interval (e.g., hourly) is classified as "rising", "falling", or "stagnating" based on customizable thresholds for price changes.
- **Quantum-Inspired Evolution:** Simulates the probability evolution of market states using a Hamiltonian operator and unitary quantum dynamics.
- **Visualization:** Plots dynamic probabilities for each regime, helping to uncover hidden patterns and regime transitions in financial time series.

---

## 📂 Features

- Works with standard OHLCV financial data (CSV).
- Easily adjustable parameters (state thresholds, Hamiltonian, time step).
- Modular, well-documented Python code.

---

## 📦 Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/Julianj34/QuantenMarkov-Trend.git
    cd QuantenMarkov-Trend
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
    *(Requirements: pandas, numpy, matplotlib, scipy)*

---

## 🛠️ Usage

1. Place your OHLCV CSV file (columns: `Close Time`, `Close`, `High`, `Low`, `Volume`) in the project folder.
2. Edit the script (`quantenmarkov_trend.py`) and set the `csv_file` variable to your filename.
3. Run the script:
    ```bash
    python quantenmarkov_trend.py
    ```
4. The script will display a plot of the regime probabilities over time.

---

## 📊 Example Output

![Sample QuantenMarkov-Trend Output](example_plot.png)

---

## 📖 How it Works

1. The script assigns a state label to each time step in your price data (rising, falling, stagnating).
2. It then uses a quantum-inspired Hamiltonian (3x3 matrix) to simulate how the probability of each state evolves over time, following unitary dynamics from quantum mechanics.
3. The resulting state probabilities are visualized as time series, revealing dynamic market patterns and transitions.


## 🔬 Research & Background

QuantenMarkov-Trend is inspired by interdisciplinary research at the intersection of quantitative finance and quantum theory.  
The project is designed for experimentation, prototyping, and further development by researchers, quants, and enthusiasts.

---

## 📄 License

MIT License – free for personal, academic, and commercial use.

---

**Author:** [Julianj34](https://github.com/Julianj34)  
Feel free to fork, contribute, and share your results!

