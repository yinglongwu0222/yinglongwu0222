<div align="center">
  <h1>Hi there, I'm Yinglong Wu 👋</h1>
  <h3>Quantitative Finance | Machine Learning | Data Science</h3>
  <p>Bridging Deep Learning with Computational Finance & Risk Management.</p>

  <p>
    <a href="https://linkedin.com/in/yinglongwu" target="_blank">
      <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
    <a href="https://wuyouan.substack.com" target="_blank">
      <img src="https://img.shields.io/badge/Substack-FF6719?style=for-the-badge&logo=substack&logoColor=white" alt="Substack" />
    </a>
  </p>
</div>

---

### 👨‍💻 About Me

I'm a quantitative researcher and data scientist currently based in Munich, pursuing my Master's in **Financial and Insurance Mathematics** at LMU Munich. I am passionate about building high-performance computational engines, complex statistical modeling, and algorithmic risk management.

- 🎓 **Education:** M.Sc. in Financial & Insurance Mathematics @ LMU Munich (Focus: Modern Quant Profile)
- 🚀 **Currently working on:** *Path-Dependent Option Pricing and Hedging within a Deep Learning Framework* (Master's Thesis)
- 💡 **Core Interests:** Differential Machine Learning, Extreme Value Theory (EVT), Stochastic Calculus, Numerical PDEs
- 💼 **Status:** Immediately available for full-time positions in Quant Research, Data Science, or ML Engineering

---

### 🛠️ Tech Stack & Toolbox

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" alt="SQL" />
  <img src="https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white" alt="R" />
  <img src="https://img.shields.io/badge/Scikit_Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white" alt="Scikit-Learn" />
  <img src="https://img.shields.io/badge/XGBoost-1798e8?style=flat-square&logo=xgboost&logoColor=white" alt="XGBoost" />
  <img src="https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white" alt="SciPy" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy" />
</p>

- **Quantitative Finance:** Stochastic Calculus (Itô's Lemma), Option Pricing (Asian/Vanilla), Autograd Greeks, Monte Carlo (Variance Reduction), Numerical PDEs (FDM), VaR/ES, Extreme Value Theory (EVT), Credit Risk Modeling
- **Machine Learning & Engineering:** Imbalanced Learning, Feature Engineering, Time Series (GARCH), Object-Oriented Programming (OOP), A/B Testing, Custom Objective Functions

---

### 🔭 Featured Open-Source Projects

#### 📈 Deep Learning Option Pricing & Hedging Engine *(Master's Thesis)*
> *An industrial-grade PyTorch framework for pricing and hedging non-Markovian Arithmetic Asian options via Differential Machine Learning (DML).*

- **⚡ High-Frequency Inference (≈ 3000x Speedup):** Architected a DML framework in PyTorch, slashing computational latency from 45.0 seconds (Monte Carlo) to **15.0 ms** for 10,000 market states, unlocking real-time algorithmic hedging capacities.
- **🧠 Unsupervised Sensitivities (Greeks):** Solved degenerate 2D PDEs by moving optimization into a Sobolev space $W^{1,2}$ using a strictly feedforward $C^{\infty}$ Softplus topology. Extracted exact first-order (Delta) and second-order (Gamma) sensitivities entirely unsupervised via the PyTorch computational Hessian matrix $\mathcal{H}_{1,1}$, achieving an out-of-sample $R^{2} > 0.9993$.
- **⚙️ High-Precision Data Engineering:** Built a `Float64` Monte Carlo pricing engine utilizing Scrambled Sobol Quasi-Monte Carlo (QMC) and Antithetic Variates. Generated mathematically rigorous training labels using the Broadie-Glasserman Pathwise Derivative method, eliminating finite-difference noise.
- **🛡️ Institutional Tail-Risk Control (EVT):** Upgraded risk management from average error metrics (MSE) to institutional worst-case bounds. Applied Extreme Value Theory (Pickands-Balkema-de Haan Theorem) to statistically guarantee the theoretical maximum absolute error ($L^{\infty}$-norm) remains strictly bounded at $\approx 0.0087$, satisfying strict quantitative risk limits.

#### 🏦 Corporate Credit Risk & Bankruptcy Prediction Engine
> *A highly robust, production-ready machine learning pipeline designed to predict corporate defaults on extremely imbalanced datasets.*

- **⚖️ Credit Risk Modeling & Custom Objective:** Evaluated XGBoost and Logistic Regression on an extremely imbalanced dataset (1:31 ratio). Formulated a custom asymmetric objective function to heavily penalize false negatives (missed defaults), minimizing potential financial exposure and boosting Mean AUC to **0.936**.
- **🔒 Strict Validation & Leakage Prevention:** Architected a rigorous evaluation framework, totally eliminating data leakage by isolating SMOTEENN hybrid resampling exclusively within the training folds via an `imblearn` DAG pipeline during Stratified 5-Fold CV.
- **📊 Statistical Feature Engineering:** Automated the elimination of multicollinearity using stateful Pearson correlation and Recursive VIF filters. Built an evaluation suite to auto-generate ROC curves, confusion matrices, and feature importance plots.
- **🧱 Production-Ready Architecture:** Structured the codebase using a modular, class-based Python architecture (`config`, `data`, `features`, `models`, `pipeline`, `evaluation`) to ensure enterprise-grade scalability and reproducibility.

---

### 💼 Professional Experience

*(Experience details are desensitized for privacy. Click to expand)*

<details>
<summary><b>Product Strategy Associate | Singapore-based Internet Securities Platform</b></summary>
<br>

- **Quantitative Factor Analysis:** Analyzed correlations between financial factors (Market Cap, Industry Trends) and stock performance. Improved Click-Through Rate (CTR) to 75% by identifying high-value trading signals using Python for statistical validation.
- **NLP Model Auditing:** Defined classification rules for financial news and developed Python scripts to audit Entity Recognition accuracy. Achieved 90%+ precision by systematically identifying and correcting training data errors.
- **Search Quality Benchmarking:** Queried large datasets using SQL to evaluate search results against 1,000+ financial keywords. Applied noise-filtering logic to optimize retrieval relevance to 85%+.
- **Data Process Optimization:** Standardized cross-regional data labeling workflows. Increased annotation efficiency by 40% by restructuring the logical guidelines for the operations team.
</details>

<details>
<summary><b>Product Operations Analyst | Leading Chinese Search Engine & AI Provider</b></summary>
<br>

- **Data Automation:** Built automated Python workflows to extract and analyze search traffic data, successfully identifying bottlenecks and reducing resource waste by 50%.
- **A/B Testing & Strategy:** Leveraged A/B testing and statistical analysis on advertising experiments, increasing Click-Through Rate (CTR) by 35%. Exceeded performance benchmarks by 120% and won the "Best Newcomer" award.
</details>

---

### 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=yinglongwu0222&show_icons=true&theme=radical&hide_border=true" width="48%" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=yinglongwu0222&layout=compact&theme=radical&hide_border=true" width="48%" alt="Top Languages" />
</div>