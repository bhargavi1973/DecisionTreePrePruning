# Decision Tree Pre-Pruning

This repository demonstrates **pre-pruning** techniques on a Decision Tree model. Pre-pruning stops the tree's growth *early* by imposing constraints like minimum samples per leaf or maximum depth, preventing overfitting by design.

---

## 🧠 What Is Pre‑Pruning?

Pre-pruning is applied *during* tree construction. By setting hyperparameters such as:
- `max_depth`
- `min_samples_split`
- `min_samples_leaf`
- `max_leaf_nodes`

you restrict the growth of the tree to reduce variance and improve generalization performance :contentReference[oaicite:1]{index=1}.

---

## 🚀 What's Inside

- **`DecisionTreePrePruning.ipynb`** – Jupyter Notebook showcasing:
  - Data loading and preprocessing
  - Training a Decision Tree with various pre-pruning hyperparameters
  - Visualizing and analyzing how tree structure and performance metrics change
  - Guiding users on how to tune parameters for best model performance

---

## 📋 How to Use

1. **Clone the repository:**

   ```bash
   git clone https://github.com/bhargavi1973/DecisionTreePrePruning.git
