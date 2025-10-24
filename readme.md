# 📘 ML from Books — Machine Learning & Finance Notes

A structured learning project exploring **Machine Learning**, **Statistical Learning**, and **Quantitative Finance**, built by studying key textbooks and implementing every concept from scratch.

This repository blends:

* Clear **mathematical intuition**
* **Code implementations** in Python (via Jupyter notebooks)
* **Practical financial datasets**
* And a clean, navigable **documentation site** powered by [MkDocs Material](https://squidfunk.github.io/mkdocs-material/)

---

## 🧩 Learning Sources

This project consolidates ideas from some of the most influential ML and finance texts:

* *Introduction to Statistical Learning (ISLP)*
* *The Elements of Statistical Learning (ESL)*
* *Probabilistic Machine Learning* — David Barber
* *Machine Learning for Algorithmic Trading* — Stefan Jansen
* *Machine Learning in Finance* — Matthew Dixon et al.

Each topic combines theoretical summaries, derivations, and applied implementations.

---

## 🧱 Repository Structure

```
ml-from-books/
│
├── docs/                    # Markdown notes rendered via MkDocs
│   ├── index.md
│   ├── regression/
│   ├── classification/
│   ├── finance/
│   └── ...
│
├── notebooks/               # Jupyter notebooks with code demos
│   ├── regression/
│   ├── classification/
│   ├── finance/
│   └── ...
│
├── datasets/                # Public or synthetic datasets
│
├── scripts/                 # Utility Python modules (plotting, data loading, etc.)
│
├── mkdocs.yml               # MkDocs configuration
├── requirements.txt         # Dependencies
└── README.md
```

---

## 🚀 View the Notes Online

The entire site is built automatically and hosted on GitHub Pages:

👉 **[https://simranjeetsinghwork.github.io/ml-from-books/](https://simranjeetsinghwork.github.io/ml-from-books/)**

---

## 💡 Example Topics

| Category             | Example Topic                               | Notebook                                             |
| -------------------- | ------------------------------------------- | ---------------------------------------------------- |
| Regression           | Linear Regression, Ridge, Lasso             | `notebooks/regression/linear_regression.ipynb`       |
| Classification       | Logistic Regression, SVM                    | `notebooks/classification/logistic_regression.ipynb` |
| Probabilistic Models | Bayesian Regression, EM Algorithm           | `notebooks/probabilistic/em_algorithm.ipynb`         |
| Finance              | CAPM, Factor Models, Portfolio Optimization | `notebooks/finance/capm_estimation.ipynb`            |

---

## 📊 Datasets

Where possible, datasets come from realistic yet freely available sources such as:

* [FRED](https://fred.stlouisfed.org/)
* [Ember Climate](https://ember-climate.org/data/)
* [ENTSO-E Transparency Platform](https://transparency.entsoe.eu/)
* [Kaggle small open datasets](https://www.kaggle.com/)
* Synthetic time series generated to mimic market dynamics

Each notebook includes a reproducible data-loading script.

---

## 🛠️ Local Setup

Clone and install dependencies:

```bash
git clone https://github.com/simranjeetsinghwork/ml-from-books.git
cd ml-from-books
pip install -r requirements.txt
```

Run the local site preview:

```bash
mkdocs serve
```

Then open: **[http://127.0.0.1:8000](http://127.0.0.1:8000)**

---

## 🧠 Guiding Principles

* Build intuition before code.
* Recreate core ML algorithms by hand.
* Apply them to real financial or energy data.
* Keep the explanations minimal, visual, and concept-first.
* Ensure full reproducibility and open access.

---

## ✨ Author

**Simranjeet Singh**
Master’s in Applied Computational Science and Engineering, Imperial College London
Focus: *Machine Learning, Quant Finance, and Statistical Modeling*

📫 [LinkedIn](https://www.linkedin.com/in/simranjeet-singh-362824250)
🐙 [GitHub](https://github.com/simranjeetsinghwork)

---

## 🧾 License

This repository is released under the [MIT License](LICENSE).
Feel free to fork, study, and adapt for your own learning journey.
