# Startup Health Scoring & Predictive Analysis
**A Machine Learning Approach to Evaluating Startup Potential**

---

## 📌 Overview
This project analyzes **100 fictional startups** to:
1. **Score startups (0-100)** based on key metrics (team experience, traction, burn rate, etc.).
2. **Predict high-potential startups** using ML models (XGBoost, Clustering, NLP).
3. **Generate actionable insights** for investors and founders.

**Key Features:**
- ✅ **Health Scoring Model** (Weighted Formula)
- ✅ **Machine Learning Predictions** (XGBoost, Clustering, NLP)
- ✅ **Interactive Visualizations** (Heatmaps, UMAP, SHAP)
- ✅ **Advanced Techniques** (GANs, Bayesian Time-Series, RL)

---

## 🛠️ Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/alwaysashutosh/TASK-1-Startup-Health-Scoring-Model
   cd startup-scoring
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

| File                              | Description                                                        |
| --------------------------------- | ------------------------------------------------------------------ |
| `Startup_Scoring_Dataset.csv`     | Core dataset with fictional startup metrics.                       |
| `health_scoring.ipynb`            | Jupyter notebook to calculate health scores and visualize results. |
| `startup_potential_predictor.pkl` | Pre-trained XGBoost model for predicting high-potential startups.  |

---

## 📊 Results
### Key Insights
1. **Top Performers**: Startups with high active users + low burn rates scored 80+.
2. **Failure Risk**: 15% of startups had <6 months of runway.
3. **Hidden Gems**: Clustering revealed undervalued startups with strong traction.


## 🔍 Methodology
### Scoring Formula
| Metric               | Weight | Logic                      |
|----------------------|--------|----------------------------|
| Team Experience      | 20%    | Critical for execution.    |
| Monthly Active Users | 25%    | Traction = Validation.     |
| Burn Rate            | 15%    | Inverted (lower = better). |

### Machine Learning
- **XGBoost**: 90% accuracy in predicting high-potential startups.
- **SHAP Analysis**: Found `monthly_active_users` most impactful.

---

---

## 📬 Contact
For questions or collaborations:
- **Email**: ashuranjan567@gmail.com
- **LinkedIn**: https://www.linkedin.com/in/alwaysashutosh
