🚀 Advanced Regression & Predictive Modeling Portfolio
Welcome to my predictive analytics and statistical inference portfolio! This repository showcases end-to-end Machine Learning workflows, starting from raw exploratory data analysis (EDA) to feature engineering, automated feature selection, and rigorous statistical validation of classical regression assumptions.

📁 Projects Overview
🚗 Project 1: Used Car Price Prediction (Cars4U Start-up)
Developed an automated pricing model for a tech startup to optimize pre-owned vehicle pricing and strategy.

The Challenge: Evaluate high-uncertainty vehicle pricing across India and devise differential pricing strategies.
Methodology:
Implemented robust multi-level missing value imputation using class-grouped medians (Brand + Model medians).
Handled heavy target skewness with advanced log-transformations.
Built and compared two high-dimensional Linear Regression models (one keeping all 200+ encoded models, another excluding them to prevent overfitting).
Core Technologies: pandas, seaborn, Scikit-Learn.
Business Impact: Balanced model complexity against accuracy, delivering a predictive pricing engine capable of explaining variance up to ~74% with localized market insight mappings.
🎬 Project 2: Content Rating Engine & Semantic Genre Extraction (Streamist)
Engineered a semantic text-mining and predictive model to analyze viewer sentiment and determine rating contributors for anime.

The Challenge: Identify key drivers of entertainment ratings and handle missing metadata constraints.
Feature Engineering Innovation (NLP + Metadata Blending):
Developed a customized text-mining parser that scans plot synopses to map representations across 8 core semantic genres (including a custom-built Inspirational category).
Blended description keyword counts with explicit database tags using a weighted score-allocation algorithm to construct a normalized global distribution.
Advanced Modeling (Forward Feature Selection):
Implemented wrapper-based feature selection utilizing Sequential Feature Selector (SFS) with 5-fold cross-validation.
Reduced dimensionality by more than 57% (from 71 features down to the 30 most impactful predictors) while maintaining statistical robustness.
Core Technologies: mlxtend, statsmodels, Scikit-Learn, NLP (Text Parsing).
🏡 Project 3: Boston Housing Market & Statistical Diagnostics
Applied strict econometric validation to home valuation predictions, validating regression assumptions.

The Challenge: Build a highly stable linear model to predict median housing prices and isolate the most significant socio-economic predictors.
Rigorous Econometric Testing:
Multicollinearity: Calculated Variance Inflation Factors (VIF) to identify extreme collinearity ($Cond.\,No. > 11,000$$Cond.\,No. > 11,000$), systematically dropping overlapping variables (TAX vs RAD).
Normality: Conducted the Shapiro-Wilk test and constructed Q-Q plots to evaluate residual normality, implementing target log-transformations to resolve right-skewness.
Heteroscedasticity: Executed the Goldfeld-Quandt test (p = 0.097) to mathematically prove constant variance (homoscedasticity).
Independence: Confirmed error independence using the Durbin-Watson statistic (~1.8) and residual plots.
Core Technologies: statsmodels, scipy.stats, scipy.
🛠️ Key Technical Highlights Demonstrated
Advanced Imputation Strategies: Moving beyond global mean/median fills to group-level, hierarchical conditional imputation.
Automated Feature Selection: Hands-on experience using wrapper-based SFS to control overfitting, enhance model speed, and optimize memory footprint.
Rigorous Statistical Inference: In-depth knowledge of validating Ordinary Least Squares (OLS) assumptions (Multicollinearity, Normality, Homoscedasticity, and Independence) beyond simple metric evaluation.
Recruiter-Ready Code Quality: Clean, functional programming structures utilizing custom Python functions for modular visualization pipelines (histogram_boxplot, labeled_barplot).
