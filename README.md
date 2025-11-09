# Exploring Multi-Armed Bandits in Recommendation System

This project explores how **Multi-Armed Bandit (MAB)** algorithms can be applied to **recommendation systems** to balance exploration and exploitation, especially in cold-start and nonstationary user behavior.

---

## 🧠 Overview
We implement and compare several MAB algorithms — both **contextual** and **non-contextual** — on:
- **MovieLens 1M Dataset**
- **Zozo Dataset**

Key metrics such as **CTR (Click-Through Rate)**, **cumulative reward**, and **regret** are used for evaluation through **offline replay simulation**.

---

## 📁 Repository Structure
```

├─ MainCode_MovieLens1MDataset.ipynb
├─ MainCode_MovieLens1MDataset_FineTuned.ipynb
├─ MainCode_ZoZoDataset.ipynb
├─ ProjectReport.pdf
├─ Presentation PPT.pdf
└─ requirements.txt

````

---

## ⚙️ Setup
```bash
git clone https://github.com/Kishan4311/Exploring-Multi-Armed-Bandits-in-Recommendation-System.git
cd Exploring-Multi-Armed-Bandits-in-Recommendation-System
pip install -r requirements.txt
````

---

## 🚀 How to Run

1. Open any of the Jupyter notebooks.
2. Run cells sequentially to:

   * Load dataset
   * Initialize MAB policies (ε-greedy, UCB, LinUCB, etc.)
   * Evaluate using offline replay method
3. Visualize cumulative rewards and CTR trends.

---

## 📊 Results

* Contextual bandits (e.g., LinUCB) outperform simple ε-greedy in most cases.
* MovieLens experiments show faster convergence and higher CTR.
* Detailed metrics and plots are in the notebooks & report.

---

## 📚 Files

* **ProjectReport.pdf** – detailed methodology and results.
* **Presentation PPT.pdf** – concise slide deck summary.

---

## 👨‍💻 Author

**Kishan Kumar Upadhyay**
*M.Sc. (IIT Bombay)*
GitHub: [@Kishan4311](https://github.com/Kishan4311)

---

## 🪪 License

This project is released for academic and research use.

```

---

Would you like me to make a **slightly extended version (with badges and dataset download instructions)** or keep this short version as your final `README.md`?
```

