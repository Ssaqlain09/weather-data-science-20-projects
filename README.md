# WEATHER DATA SCIENCE — 20 COMPLETED PROJECTS

20 executed Google Colab notebooks, all using the same attached weather dataset.

**Dataset:** `Combined12_0_4op7.csv` — 533,312 rows, 8 columns: Pressure, global_radiation, temp_mean(c), temp_min(c), temp_max(c), Wind_Speed, Wind_Bearing, normalized_label (0: 239,241 / 44.86%, 1: 155,709 / 29.20%, 2: 87,533 / 16.41%, 3: 50,829 / 9.53%). No missing values in the original file; 16,264 duplicate rows.

**Dataset path in every notebook (Colab):** `/content/drive/MyDrive/Weather_Projects/Dataset/Combined12_0_4op7.csv`

**Google Drive folder:** [Weather_Projects](https://drive.google.com/drive/folders/1dc5KdWkizBm8hkqe_BihHJT-IdmIV8Ar)

**Final PDF (25 pages, original statements + all 20 Colab links):** [Weather_Projects_Complete_Documentation.pdf](https://drive.google.com/file/d/1Id77tIgGuI_CBr2NG5Xq4afR4t_VTKof/view?usp=drivesdk)

**Verification:** All 20 notebooks were executed end-to-end with 0 cell errors, at least 1 embedded plot each, including SHAP in Project 4 (shap 0.54.1), Optuna Bayesian optimisation in Project 14 (optuna 5.0.0), and UMAP in Project 17 (umap-learn 0.5.12). Notebooks were verified locally with `jupyter nbconvert --execute`; each notebook still contains `drive.mount('/content/drive')` and the Drive dataset path above, so opening a Colab link and running it there uses the Drive dataset.

**Dataset file:** The 19 MB CSV is not in this repo (it lives in Drive at `Weather_Projects/Dataset/Combined12_0_4op7.csv`). Copy it to that Drive path before running a notebook in Colab.

## Contents

| # | Project | Open in Colab | Preview on GitHub |
|---:|---|---|---|
| 01 | Data Leakage Detection Lab | [Open in Colab](https://colab.research.google.com/drive/1__0GtI5TzTlYxQ4PTCgtfTpz-PMdcOnZ) | [Preview](https://github.com/Ssaqlain09/weather-data-science-20-projects/blob/main/Projects/Project%2001/Project_01_Data_Leakage_Detection_Lab.ipynb) |
| 02 | Missing Data Mechanism Analysis | [Open in Colab](https://colab.research.google.com/drive/1GVGDEST01u9VFucz-kFozyO0HQjwej28) | [Preview](https://github.com/Ssaqlain09/weather-data-science-20-projects/blob/main/Projects/Project%2002/Project_02_Missing_Data_Mechanism_Analysis.ipynb) |
| 03 | Feature Stability Under Distribution Shift | [Open in Colab](https://colab.research.google.com/drive/1czi_7obCqX5dVtf_6E-o09CjoE0f6SIf) | [Preview](https://github.com/Ssaqlain09/weather-data-science-20-projects/blob/main/Projects/Project%2003/Project_03_Feature_Stability_Under_Distribution_Shift.ipynb) |
| 04 | Model Explainability vs Performance Tradeoff | [Open in Colab](https://colab.research.google.com/drive/15LvufX01H-Z0jlZTyEEbDmIzU9V6u9-A) | [Preview](https://github.com/Ssaqlain09/weather-data-science-20-projects/blob/main/Projects/Project%2004/Project_04_Model_Explainability_vs_Performance_Tradeoff.ipynb) |
| 05 | Custom Cross-Validation Strategy | [Open in Colab](https://colab.research.google.com/drive/15fxr99BVklcdhej4_umyIFvjb8IIjhNx) | [Preview](https://github.com/Ssaqlain09/weather-data-science-20-projects/blob/main/Projects/Project%2005/Project_05_Custom_Cross_Validation_Strategy.ipynb) |
| 06 | Bias & Fairness Evaluation Lab | [Open in Colab](https://colab.research.google.com/drive/1ihicfcu6Jyshv7u2M4a0-ilXVMvsZA2H) | [Preview](https://github.com/Ssaqlain09/weather-data-science-20-projects/blob/main/Projects/Project%2006/Project_06_Bias_Fairness_Evaluation_Lab.ipynb) |
| 07 | High-Dimensional Feature Selection | [Open in Colab](https://colab.research.google.com/drive/1x7EJw2HW5N6wxO1dmtkOI5Xg8117Psi9) | [Preview](https://github.com/Ssaqlain09/weather-data-science-20-projects/blob/main/Projects/Project%2007/Project_07_High_Dimensional_Feature_Selection.ipynb) |
| 08 | Anomaly Detection with No Labels | [Open in Colab](https://colab.research.google.com/drive/14uYtWbcP4xfZAsAqXKmYuKJ57vmogaqX) | [Preview](https://github.com/Ssaqlain09/weather-data-science-20-projects/blob/main/Projects/Project%2008/Project_08_Anomaly_Detection_with_No_Labels.ipynb) |
| 09 | Time-Series Forecasting Under Concept Drift | [Open in Colab](https://colab.research.google.com/drive/1KK2saIk_zOlSLUnpjMQ-4wKiU1n9zsqq) | [Preview](https://github.com/Ssaqlain09/weather-data-science-20-projects/blob/main/Projects/Project%2009/Project_09_Time_Series_Forecasting_Under_Concept_Drift.ipynb) |
| 10 | Class Imbalance Strategy Comparison | [Open in Colab](https://colab.research.google.com/drive/1XVvZJSH8i1yrPsbBKM9uvbv24ts-tcrt) | [Preview](https://github.com/Ssaqlain09/weather-data-science-20-projects/blob/main/Projects/Project%2010/Project_10_Class_Imbalance_Strategy_Comparison.ipynb) |
| 11 | Feature Engineering from Raw Text Logs | [Open in Colab](https://colab.research.google.com/drive/1x5uy7zLejaX7E6HjJQsype6V3HhaJjDy) | [Preview](https://github.com/Ssaqlain09/weather-data-science-20-projects/blob/main/Projects/Project%2011/Project_11_Feature_Engineering_from_Raw_Text_Logs.ipynb) |
| 12 | Model Calibration Lab | [Open in Colab](https://colab.research.google.com/drive/1Ym_eQHo7KMrOyz9rJr74oXXXtTTIVTCK) | [Preview](https://github.com/Ssaqlain09/weather-data-science-20-projects/blob/main/Projects/Project%2012/Project_12_Model_Calibration_Lab.ipynb) |
| 13 | Causal Inference vs Prediction | [Open in Colab](https://colab.research.google.com/drive/16EDbUPgtHPrhAjTFHswN9gTN89I6Hsl3) | [Preview](https://github.com/Ssaqlain09/weather-data-science-20-projects/blob/main/Projects/Project%2013/Project_13_Causal_Inference_vs_Prediction.ipynb) |
| 14 | Hyperparameter Search Efficiency | [Open in Colab](https://colab.research.google.com/drive/1ZQTMWZwR3yAlMSplcBf8Jm77wv_onQ1U) | [Preview](https://github.com/Ssaqlain09/weather-data-science-20-projects/blob/main/Projects/Project%2014/Project_14_Hyperparameter_Search_Efficiency.ipynb) |
| 15 | Model Robustness to Noise Injection | [Open in Colab](https://colab.research.google.com/drive/1Js55ahuXEhWLMQ0C7GQUzfQPCHHihB2n) | [Preview](https://github.com/Ssaqlain09/weather-data-science-20-projects/blob/main/Projects/Project%2015/Project_15_Model_Robustness_to_Noise_Injection.ipynb) |
| 16 | Ensemble Diversity Analysis | [Open in Colab](https://colab.research.google.com/drive/12kpIDig5P-t73uPHuM-NV_NsKGTXE0dQ) | [Preview](https://github.com/Ssaqlain09/weather-data-science-20-projects/blob/main/Projects/Project%2016/Project_16_Ensemble_Diversity_Analysis.ipynb) |
| 17 | Dimensionality Reduction for Visualization | [Open in Colab](https://colab.research.google.com/drive/15fRXLIajVqmpTzAD9hYJpC0_4zG3xJal) | [Preview](https://github.com/Ssaqlain09/weather-data-science-20-projects/blob/main/Projects/Project%2017/Project_17_Dimensionality_Reduction_for_Visualization.ipynb) |
| 18 | Streaming Data Simulation Lab | [Open in Colab](https://colab.research.google.com/drive/1NZM784oclvh0Gv1yxIlB5h3-gWRMMnU3) | [Preview](https://github.com/Ssaqlain09/weather-data-science-20-projects/blob/main/Projects/Project%2018/Project_18_Streaming_Data_Simulation_Lab.ipynb) |
| 19 | Error Analysis & Model Debugging | [Open in Colab](https://colab.research.google.com/drive/1JzFlJqUihq_AJTHBaf7b-qG42yZ15G6s) | [Preview](https://github.com/Ssaqlain09/weather-data-science-20-projects/blob/main/Projects/Project%2019/Project_19_Error_Analysis_Model_Debugging.ipynb) |
| 20 | End-to-End ML System Design | [Open in Colab](https://colab.research.google.com/drive/1FTRFwZfZ8-Oj3hNMn4p3_GHcBjZBJeJH) | [Preview](https://github.com/Ssaqlain09/weather-data-science-20-projects/blob/main/Projects/Project%2020/Project_20_End_to_End_ML_System_Design.ipynb) |

**Repository structure:** `README.md` at the root, and a `Projects/` folder with 20 subfolders — `Project 1`, `Project 2`, …, `Project 20` — each holding that project's executed notebook.

## How to use

1. Open a project in Colab using its link above, or preview it on GitHub using its Preview link.
2. In Colab, mount Drive and make sure the dataset is at `/content/drive/MyDrive/Weather_Projects/Dataset/Combined12_0_4op7.csv`.
3. Run all cells in order. Each notebook already has executed outputs and plots saved in it.

## Project 01: Data Leakage Detection Lab

**Original project statement:** You are given a tabular dataset with timestamps, target labels, and engineered features. Task: Identify potential sources of data leakage; propose programmatic checks to detect leakage; rebuild the pipeline to prevent it; quantify performance difference before vs after correction.

**Implementation:** RandomForest on a 30,000-row stratified sample; synthetic target-derived leaked feature (demonstration only), duplicate-group split, and scaler-fit check.

**Verified results:** Baseline random-split accuracy 0.9148; leaky accuracy 1.0000; corrected group-split accuracy 0.9185; leakage inflation 0.0815. Scaler-all vs train-only logistic accuracy both 0.788.

**Completion status:** Completed — verified. Adaptation: no timestamp in this file, so time-based leakage is not claimed; the leaked feature is synthetic and is not in the original file.

**Open in Colab:** https://colab.research.google.com/drive/1__0GtI5TzTlYxQ4PTCgtfTpz-PMdcOnZ

**Preview on GitHub:** https://github.com/Ssaqlain09/weather-data-science-20-projects/blob/main/Projects/Project%2001/Project_01_Data_Leakage_Detection_Lab.ipynb

**Notebook file:** `Projects/Project 01/Project_01_Data_Leakage_Detection_Lab.ipynb` — shared in Drive as Anyone with the link, Viewer.

## Project 02: Missing Data Mechanism Analysis

**Original project statement:** A dataset contains multiple patterns of missing values. Task: Determine whether missingness is MCAR, MAR, or MNAR; use statistical tests and visual diagnostics; implement two imputation strategies and compare downstream model impact.

**Implementation:** MCAR/MAR/MNAR injection at documented rates, t-test diagnostics, mean / median / KNN (k=5) imputation, RandomForest downstream evaluation.

**Verified results:** Original file: 0 missing values. Injected MCAR 10.15%, MAR 17.42% (Wind_Speed 16.11 missing vs 11.04 observed, p ~6e-266), MNAR 9.44% (observed temp_max mean 16.206 vs true 16.966). Downstream accuracy: mean 0.8512, median 0.8506, KNN 0.8564; complete-data reference 0.8832.

**Completion status:** Completed — verified. Adaptation: missingness was injected for comparison because the original file is complete; injected patterns are not claimed to be original.

**Open in Colab:** https://colab.research.google.com/drive/1GVGDEST01u9VFucz-kFozyO0HQjwej28

**Preview on GitHub:** https://github.com/Ssaqlain09/weather-data-science-20-projects/blob/main/Projects/Project%2002/Project_02_Missing_Data_Mechanism_Analysis.ipynb

**Notebook file:** `Projects/Project 02/Project_02_Missing_Data_Mechanism_Analysis.ipynb` — shared in Drive as Anyone with the link, Viewer.

## Project 03: Feature Stability Under Distribution Shift

**Original project statement:** Train a model on historical data and evaluate on a future time slice with degraded performance. Task: Detect covariate shift; identify unstable features; retrain using only stable features and justify selection.

**Implementation:** Wind_Bearing domain split (<180 vs >=180), Kolmogorov-Smirnov and standardised mean-shift diagnostics, RandomForest source vs target evaluation, stable-feature retraining.

**Verified results:** Unstable: Wind_Bearing shift 2.849, Wind_Speed 0.211; all other features <0.02. All features: source 0.8871, target 0.8795 (drop 0.0076). Stable-only (5 features): source 0.6714, target 0.6333 (drop 0.0382) — stable-only was worse in this run, reported honestly.

**Completion status:** Completed — verified. Adaptation: bearing-domain shift, not a dated future slice, because the file has no timestamp.

**Open in Colab:** https://colab.research.google.com/drive/1czi_7obCqX5dVtf_6E-o09CjoE0f6SIf

**Preview on GitHub:** https://github.com/Ssaqlain09/weather-data-science-20-projects/blob/main/Projects/Project%2003/Project_03_Feature_Stability_Under_Distribution_Shift.ipynb

**Notebook file:** `Projects/Project 03/Project_03_Feature_Stability_Under_Distribution_Shift.ipynb` — shared in Drive as Anyone with the link, Viewer.

## Project 04: Model Explainability vs Performance Tradeoff

**Original project statement:** Given a black-box model with high accuracy: Task: Apply SHAP and permutation importance; replace it with an interpretable model; quantify performance loss and explainability gain.

**Implementation:** LogisticRegression, DecisionTree (depth 4), RandomForest, HistGradientBoosting; permutation importance; SHAP executed (TreeExplainer, shap 0.54.1, 500 test rows, auto-install cell for Colab).

**Verified results:** Logistic 0.7874, tree 0.7706, RandomForest 0.8994, HistGB 0.8627 (accuracy). Performance loss (best black-box minus tree) 0.1288. Permutation importance top: Wind_Speed 0.3364, global_radiation 0.2765. SHAP mean |value| (500 rows): Wind_Speed 0.1875, global_radiation 0.0862, temp_min(c) 0.0357, temp_max(c) 0.0328, temp_mean(c) 0.0232, Pressure 0.0175, Wind_Bearing 0.0064.

**Completion status:** Completed — verified, including SHAP. SHAP was executed with shap 0.54.1 (TreeExplainer, 500 test rows); values above are from that executed run, not a fallback.

**Open in Colab:** https://colab.research.google.com/drive/15LvufX01H-Z0jlZTyEEbDmIzU9V6u9-A

**Preview on GitHub:** https://github.com/Ssaqlain09/weather-data-science-20-projects/blob/main/Projects/Project%2004/Project_04_Model_Explainability_vs_Performance_Tradeoff.ipynb

**Notebook file:** `Projects/Project 04/Project_04_Model_Explainability_vs_Performance_Tradeoff.ipynb` — shared in Drive as Anyone with the link, Viewer.

## Project 05: Custom Cross-Validation Strategy

**Original project statement:** You are given grouped, time-ordered observations. Task: Design a valid cross-validation scheme; implement it manually in Python; show why standard K-fold is invalid here.

**Implementation:** Hand-implemented blocked expanding-window pseudo-time split and duplicate-group split, compared with shuffled StratifiedKFold; RandomForest.

**Verified results:** Shuffled K-fold mean 0.8897; blocked pseudo-time mean 0.8548; duplicate-group mean 0.8876. Shuffled test duplicate-group leakage fraction 0.0022 (group split forces 0).

**Completion status:** Completed — verified. Adaptation: pseudo-time is row order and groups are exact duplicate rows; there is no timestamp or original group ID.

**Open in Colab:** https://colab.research.google.com/drive/15fxr99BVklcdhej4_umyIFvjb8IIjhNx

**Preview on GitHub:** https://github.com/Ssaqlain09/weather-data-science-20-projects/blob/main/Projects/Project%2005/Project_05_Custom_Cross_Validation_Strategy.ipynb

**Notebook file:** `Projects/Project 05/Project_05_Custom_Cross_Validation_Strategy.ipynb` — shared in Drive as Anyone with the link, Viewer.

## Project 06: Bias & Fairness Evaluation Lab

**Original project statement:** A binary classifier predicts loan approval. Task: Measure demographic parity, equalized odds; identify bias sources; apply at least one fairness mitigation technique and evaluate impact.

**Implementation:** Wind_Bearing quadrant proxy groups, one-vs-rest positive = class 3, demographic parity and equalized-odds (TPR/FPR) gaps, reweighting mitigation, RandomForest.

**Verified results:** Overall accuracy 0.9161 before, 0.9101 after reweighting. Parity gap (class-3 pred rate, max-min) 0.0416 before, 0.0424 after — reweighting did not shrink the gap in this run. TPR range 0.0413, FPR range 0.0101 before.

**Completion status:** Completed — verified. Adaptation: NO demographic or loan data exist in this file; quadrant is a labelled proxy only and this is not a demographic fairness finding.

**Open in Colab:** https://colab.research.google.com/drive/1ihicfcu6Jyshv7u2M4a0-ilXVMvsZA2H

**Preview on GitHub:** https://github.com/Ssaqlain09/weather-data-science-20-projects/blob/main/Projects/Project%2006/Project_06_Bias_Fairness_Evaluation_Lab.ipynb

**Notebook file:** `Projects/Project 06/Project_06_Bias_Fairness_Evaluation_Lab.ipynb` — shared in Drive as Anyone with the link, Viewer.

## Project 07: High-Dimensional Feature Selection

**Original project statement:** Dataset has 10,000+ features and 500 samples. Task: Apply multiple feature selection techniques; compare stability and model performance; justify final feature subset statistically.

**Implementation:** Polynomial degree-3 expansion of 7 base features to 119 features; SelectKBest (ANOVA F), L1 logistic, RandomForest evaluation; stability by Jaccard across halves.

**Verified results:** All expanded (119) accuracy 0.8200; SelectKBest k=20 0.7685; k=10 0.6980; L1-selected (78) 0.8085; base-7 only 0.8395 — base-7 beat the expanded sets in this run. SelectKBest stability Jaccard 1.0.

**Completion status:** Completed — verified. Adaptation: the file has only 7 predictors, not 10,000; 119 is the documented polynomial expansion, never claimed as original features.

**Open in Colab:** https://colab.research.google.com/drive/1x7EJw2HW5N6wxO1dmtkOI5Xg8117Psi9

**Preview on GitHub:** https://github.com/Ssaqlain09/weather-data-science-20-projects/blob/main/Projects/Project%2007/Project_07_High_Dimensional_Feature_Selection.ipynb

**Notebook file:** `Projects/Project 07/Project_07_High_Dimensional_Feature_Selection.ipynb` — shared in Drive as Anyone with the link, Viewer.

## Project 08: Anomaly Detection with No Labels

**Original project statement:** You receive system log data with unknown anomalies. Task: Implement at least two unsupervised methods; compare detection overlap; validate anomalies using proxy metrics.

**Implementation:** IsolationForest (contamination 0.05, 10,000 rows) and LocalOutlierFactor (5,000 rows), overlap Jaccard, proxy feature-extremeness comparison.

**Verified results:** Both methods rate 0.05; overlap Jaccard 0.3085 (both flag 112, either 363). Anomaly means vs normal: temp_min 4.468 vs 9.032, Wind_Speed 16.315 vs 11.743. Label shares among anomalies are descriptive only.

**Completion status:** Completed — verified. Adaptation: no system logs and no anomaly labels; labels were never used for training, only for post-hoc description.

**Open in Colab:** https://colab.research.google.com/drive/14uYtWbcP4xfZAsAqXKmYuKJ57vmogaqX

**Preview on GitHub:** https://github.com/Ssaqlain09/weather-data-science-20-projects/blob/main/Projects/Project%2008/Project_08_Anomaly_Detection_with_No_Labels.ipynb

**Notebook file:** `Projects/Project 08/Project_08_Anomaly_Detection_with_No_Labels.ipynb` — shared in Drive as Anyone with the link, Viewer.

## Project 09: Time-Series Forecasting Under Concept Drift

**Original project statement:** Forecast demand where seasonal patterns change mid-series. Task: Detect drift; retrain adaptively; compare static vs rolling models.

**Implementation:** Row-order pseudo-time, lag 1/2/3 and rolling-mean-5 features, target temp_mean(c), naive / LinearRegression / RandomForest, static vs rolling retraining on the first 150,000 rows.

**Verified results:** Rolling mean by third: 9.772, 11.448, 12.200. Final-segment RMSE: naive lag1 1.2338, LinearRegression 1.2247, static RandomForest 3.2728. Rolling RandomForest 3.1258 vs static RandomForest same period 3.1670 — rolling beats static RF slightly, but both RF models are worse than linear/naive (trees do not extrapolate the trend).

**Completion status:** Completed — verified. Adaptation: pseudo-time, weather target not demand, no seasonality claimed; stream is the first 150,000 rows for runtime.

**Open in Colab:** https://colab.research.google.com/drive/1KK2saIk_zOlSLUnpjMQ-4wKiU1n9zsqq

**Preview on GitHub:** https://github.com/Ssaqlain09/weather-data-science-20-projects/blob/main/Projects/Project%2009/Project_09_Time_Series_Forecasting_Under_Concept_Drift.ipynb

**Notebook file:** `Projects/Project 09/Project_09_Time_Series_Forecasting_Under_Concept_Drift.ipynb` — shared in Drive as Anyone with the link, Viewer.

## Project 10: Class Imbalance Strategy Comparison

**Original project statement:** Target class frequency is <2%. Task: Compare resampling, class weighting, and threshold tuning; evaluate with appropriate metrics; argue for the best production strategy.

**Implementation:** Baseline, class-weight balanced, random oversampling, random undersampling RandomForest; threshold tuning for class 3; macro-F1, balanced accuracy, per-class recall.

**Verified results:** Baseline: accuracy 0.9161, balanced accuracy 0.8767, macro-F1 0.8844, class-3 P/R/F1 0.8466/0.7260/0.7817. Class-weight: 0.9063/0.8805/0.8835, class-3 0.8336/0.7822/0.8071. Oversampling: 0.9128/0.8804/0.8863. Undersampling: 0.8360/0.8256/0.8226. Threshold 0.1: class-3 precision 0.4721, recall 0.9849; threshold 0.5: 0.8348/0.7822.

**Completion status:** Completed — verified. Adaptation: the true minority rate is class 3 at 9.53% (50,829 of 533,312), not <2%; all comparisons focus on class 3 with true rates reported.

**Open in Colab:** https://colab.research.google.com/drive/1XVvZJSH8i1yrPsbBKM9uvbv24ts-tcrt

**Preview on GitHub:** https://github.com/Ssaqlain09/weather-data-science-20-projects/blob/main/Projects/Project%2010/Project_10_Class_Imbalance_Strategy_Comparison.ipynb

**Notebook file:** `Projects/Project 10/Project_10_Class_Imbalance_Strategy_Comparison.ipynb` — shared in Drive as Anyone with the link, Viewer.

## Project 11: Feature Engineering from Raw Text Logs

**Original project statement:** Given raw server logs: Task: Extract structured features; reduce dimensionality; evaluate contribution of text-derived features.

**Implementation:** Binned weather bands and combined log-like codes (temp band + wind direction + pressure band + radiation band), one-hot ablation vs numeric-only RandomForest.

**Verified results:** 64 distinct log-like codes. Numeric only: 0.9163 / macro-F1 0.8850. Numeric + binned one-hot (20 features): 0.8809 / 0.8525. Log-code one-hot only (64): 0.5625 / 0.3182. Numeric + log-code (71): 0.8499 / 0.8236. Binning did not help over raw numbers in this run.

**Completion status:** Completed — verified. Adaptation: there is no raw text or server log in this file; codes are derived from binned numeric fields and are labelled as analogues.

**Open in Colab:** https://colab.research.google.com/drive/1x5uy7zLejaX7E6HjJQsype6V3HhaJjDy

**Preview on GitHub:** https://github.com/Ssaqlain09/weather-data-science-20-projects/blob/main/Projects/Project%2011/Project_11_Feature_Engineering_from_Raw_Text_Logs.ipynb

**Notebook file:** `Projects/Project 11/Project_11_Feature_Engineering_from_Raw_Text_Logs.ipynb` — shared in Drive as Anyone with the link, Viewer.

## Project 12: Model Calibration Lab

**Original project statement:** A classifier outputs probabilities. Task: Assess calibration; apply Platt scaling and isotonic regression; measure calibration improvement quantitatively.

**Implementation:** LogisticRegression and RandomForest; Platt (sigmoid) and isotonic calibration via CalibratedClassifierCV (cv=3, as sklearn 1.9 removed cv='prefit'); multiclass Brier, log-loss and ECE (confidence bins).

**Verified results:** Uncalibrated: Logistic 0.7924 / log-loss 0.4698 / Brier 0.2947 / ECE 0.0181; RandomForest 0.8884 / 0.3073 / 0.1799 / 0.0688. RF sigmoid: 0.8224 / 0.4500 / 0.2588 / ECE 0.0154. RF isotonic: 0.8182 / 0.4318 / 0.2599 / ECE 0.0128 (lowest ECE, lower accuracy). Logistic sigmoid: 0.6036 / 0.7750 / 0.4699 / ECE 0.0760; Logistic isotonic: 0.6512 / 0.6827 / 0.4380 / ECE 0.0935. Calibration improved ECE for RandomForest only, at an accuracy/log-loss cost; uncalibrated Logistic was best on log-loss/ECE overall — do not calibrate blindly.

**Completion status:** Completed — verified. Note the non-improvement above is reported, not hidden.

**Open in Colab:** https://colab.research.google.com/drive/1Ym_eQHo7KMrOyz9rJr74oXXXtTTIVTCK

**Preview on GitHub:** https://github.com/Ssaqlain09/weather-data-science-20-projects/blob/main/Projects/Project%2012/Project_12_Model_Calibration_Lab.ipynb

**Notebook file:** `Projects/Project 12/Project_12_Model_Calibration_Lab.ipynb` — shared in Drive as Anyone with the link, Viewer.

## Project 13: Causal Inference vs Prediction

**Original project statement:** Given observational data on a marketing campaign: Task: Estimate causal effect using matching or regression; compare with predictive model results; explain discrepancies.

**Implementation:** Observational analogue: treatment = high Wind_Speed (median split), outcome temp_mean(c), confounders Pressure, global_radiation, Wind_Bearing; regression adjustment, propensity stratification, nearest-neighbour matching; predictive RandomForest for comparison.

**Verified results:** Naive difference -0.3704; regression-adjusted -0.037; propensity-stratified -0.1138; matching -0.1885. Predictive RandomForest accuracy for normalized_label 0.8986, Wind_Speed importance 0.3785. Predictive importance is not a causal effect.

**Completion status:** Completed — verified. Adaptation: no marketing campaign or randomised treatment; no causal effect is claimed as proven, unmeasured confounding remains possible.

**Open in Colab:** https://colab.research.google.com/drive/16EDbUPgtHPrhAjTFHswN9gTN89I6Hsl3

**Preview on GitHub:** https://github.com/Ssaqlain09/weather-data-science-20-projects/blob/main/Projects/Project%2013/Project_13_Causal_Inference_vs_Prediction.ipynb

**Notebook file:** `Projects/Project 13/Project_13_Causal_Inference_vs_Prediction.ipynb` — shared in Drive as Anyone with the link, Viewer.

## Project 14: Hyperparameter Search Efficiency

**Original project statement:** You must tune a complex model under limited compute. Task: Compare grid search, random search, Bayesian optimization; measure convergence efficiency; recommend a production strategy.

**Implementation:** GridSearchCV, RandomizedSearchCV (8 samples) and Optuna Bayesian optimisation (TPE sampler, seed 42, 8 trials, optuna 5.0.0, auto-install cell for Colab); RandomForest; time and CV score tracked.

**Verified results:** Grid best CV 0.8465 (19.7 s, test 0.8664). Random best CV 0.8490 (41.4 s, test 0.8707). Optuna Bayesian best CV 0.8319, best params n_estimators=87, max_depth=24, min_samples_leaf=3; trial values in order [0.8319, 0.8086, 0.8316, 0.7872, 0.8129, 0.8179, 0.8181, 0.8211] — Optuna did not beat random search on this budget in this run.

**Completion status:** Completed — verified, including Optuna Bayesian optimisation. Optuna values above are from the executed run.

**Open in Colab:** https://colab.research.google.com/drive/1ZQTMWZwR3yAlMSplcBf8Jm77wv_onQ1U

**Preview on GitHub:** https://github.com/Ssaqlain09/weather-data-science-20-projects/blob/main/Projects/Project%2014/Project_14_Hyperparameter_Search_Efficiency.ipynb

**Notebook file:** `Projects/Project 14/Project_14_Hyperparameter_Search_Efficiency.ipynb` — shared in Drive as Anyone with the link, Viewer.

## Project 15: Model Robustness to Noise Injection

**Original project statement:** Inject noise into features and labels. Task: Measure robustness degradation; identify sensitive features; improve robustness via regularization or data augmentation.

**Implementation:** Gaussian feature noise at 0.10x / 0.25x / 0.50x std, label flips at 5% / 10%, per-feature noise sensitivity, regularised (depth 10) and noisy-augmented RandomForest.

**Verified results:** Baseline 0.8846. Feature noise: 0.10x -> 0.7796; 0.25x -> 0.7054; 0.50x -> 0.6162. Label flips: 5% -> 0.8768; 10% -> 0.8708. Most sensitive single feature at 0.25x: Wind_Speed (drop 0.0530); least: Wind_Bearing (0.0014). Regularised: clean 0.8242 / noisy 0.7224. Augmented: clean 0.8752 / noisy 0.7262.

**Completion status:** Completed — verified. Adaptation: noise was injected synthetically for this experiment; the original file was not altered.

**Open in Colab:** https://colab.research.google.com/drive/1Js55ahuXEhWLMQ0C7GQUzfQPCHHihB2n

**Preview on GitHub:** https://github.com/Ssaqlain09/weather-data-science-20-projects/blob/main/Projects/Project%2015/Project_15_Model_Robustness_to_Noise_Injection.ipynb

**Notebook file:** `Projects/Project 15/Project_15_Model_Robustness_to_Noise_Injection.ipynb` — shared in Drive as Anyone with the link, Viewer.

## Project 16: Ensemble Diversity Analysis

**Original project statement:** Build an ensemble of models. Task: Measure model correlation; remove redundant models; evaluate ensemble performance change.

**Implementation:** LogisticRegression, DecisionTree, RandomForest, ExtraTrees, HistGradientBoosting; prediction correlation, soft voting, stacking.

**Verified results:** Individual accuracy: Logistic 0.7846, tree 0.8476, RandomForest 0.8846, ExtraTrees 0.8520, HistGB 0.8498. Soft voting all 0.8784; stacking 0.8978 (best). Most redundant: RandomForest (mean correlation 0.9439); voting without it 0.8764 (drop 0.0020).

**Completion status:** Completed — verified.

**Open in Colab:** https://colab.research.google.com/drive/12kpIDig5P-t73uPHuM-NV_NsKGTXE0dQ

**Preview on GitHub:** https://github.com/Ssaqlain09/weather-data-science-20-projects/blob/main/Projects/Project%2016/Project_16_Ensemble_Diversity_Analysis.ipynb

**Notebook file:** `Projects/Project 16/Project_16_Ensemble_Diversity_Analysis.ipynb` — shared in Drive as Anyone with the link, Viewer.

## Project 17: Dimensionality Reduction for Visualization

**Original project statement:** High-dimensional labeled data is given. Task: Apply PCA, t-SNE, and UMAP; compare class separability; justify visualization choice analytically.

**Implementation:** PCA (2 components), t-SNE (perplexity 30) and UMAP (umap-learn 0.5.12, auto-install cell for Colab) on a 3,000-row sample; silhouette and trustworthiness.

**Verified results:** PCA explained variance [0.4950, 0.1769], total 0.6719; PCA silhouette 0.0133, trustworthiness 0.8722. t-SNE silhouette -0.0004, trustworthiness 0.9920. UMAP silhouette 0.0068, trustworthiness 0.9685 — UMAP trustworthiness sits between PCA and t-SNE on this sample.

**Completion status:** Completed — verified, including UMAP. UMAP values and plot above are from the executed run. Adaptation: the file has only 7 features, not high-dimensional data.

**Open in Colab:** https://colab.research.google.com/drive/15fRXLIajVqmpTzAD9hYJpC0_4zG3xJal

**Preview on GitHub:** https://github.com/Ssaqlain09/weather-data-science-20-projects/blob/main/Projects/Project%2017/Project_17_Dimensionality_Reduction_for_Visualization.ipynb

**Notebook file:** `Projects/Project 17/Project_17_Dimensionality_Reduction_for_Visualization.ipynb` — shared in Drive as Anyone with the link, Viewer.

## Project 18: Streaming Data Simulation Lab

**Original project statement:** Simulate real-time incoming data. Task: Update model incrementally; detect performance decay; trigger retraining automatically.

**Implementation:** First 30,000 rows in file order as a simulated stream, batches of 2,000, SGDClassifier partial_fit, prequential accuracy, fixed trigger (2-batch rolling mean <0.60), retraining on a recent window.

**Verified results:** Prequential accuracies (batches 1-14): 0.6575, 0.5955, 0.7055, 0.6980, 0.7885, 0.7040, 0.6400, 0.6865, 0.6720, 0.7540, 0.5440, 0.7465, 0.5095, 0.6320. Trigger fired at batch 14. Retrained RandomForest on recent window: test accuracy 0.9993 — note: this is a recent-window test on a homogeneous early-stream segment, not a general test accuracy.

**Completion status:** Completed — verified. Adaptation: simulated stream, not live data.

**Open in Colab:** https://colab.research.google.com/drive/1NZM784oclvh0Gv1yxIlB5h3-gWRMMnU3

**Preview on GitHub:** https://github.com/Ssaqlain09/weather-data-science-20-projects/blob/main/Projects/Project%2018/Project_18_Streaming_Data_Simulation_Lab.ipynb

**Notebook file:** `Projects/Project 18/Project_18_Streaming_Data_Simulation_Lab.ipynb` — shared in Drive as Anyone with the link, Viewer.

## Project 19: Error Analysis & Model Debugging

**Original project statement:** Model performance plateaus. Task: Perform systematic error analysis; identify failure modes; propose data or model fixes and validate them.

**Implementation:** RandomForest baseline, confusion matrix, error rates by wind quadrant and temperature band, correct vs incorrect feature means, two fixes validated on the same split.

**Verified results:** Baseline accuracy 0.8994, macro-F1 0.87 (test 6,250). Most confused pairs: true 1 -> pred 0 (261), true 3 -> pred 2 (192), true 0 -> pred 1 (101). Error rates: quadrant 0.098-0.105; temp band cold 0.1073, mild 0.1146, warm 0.0856, hot 0.0000 (n=84). Incorrect examples: Wind_Speed 14.285 vs 11.657 correct, temp_min 7.582 vs 8.751. Fixes: class-weight balanced 0.8934 / 0.8686 (no improvement); +temp_range 0.9048 / 0.8722 (small improvement).

**Completion status:** Completed — verified.

**Open in Colab:** https://colab.research.google.com/drive/1JzFlJqUihq_AJTHBaf7b-qG42yZ15G6s

**Preview on GitHub:** https://github.com/Ssaqlain09/weather-data-science-20-projects/blob/main/Projects/Project%2019/Project_19_Error_Analysis_Model_Debugging.ipynb

**Notebook file:** `Projects/Project 19/Project_19_Error_Analysis_Model_Debugging.ipynb` — shared in Drive as Anyone with the link, Viewer.

## Project 20: End-to-End ML System Design

**Original project statement:** Given a vague business problem: Task: Translate into ML formulation; design data pipeline; select models and metrics; justify all assumptions and tradeoffs.

**Implementation:** Problem translated as: predict normalized_label (0-3) from 7 weather measurements for a weather-monitoring dashboard. Pipeline: StandardScaler + RandomForest, predict_weather_label() inference function, batch serving simulation, drift monitoring, retraining trigger design.

**Verified results:** Pipeline test accuracy 0.916, macro-F1 0.8842 (test 7,500). Example prediction matched true label 0 with probabilities 0.9467 / 0.0533 / 0 / 0. Batch inference: 1,000 rows in 0.046 s (0.05 ms/row). Drift check: no feature >0.5 std shift, alert list empty.

**Completion status:** Completed — verified. Adaptation: the business problem is the weather-label formulation above; no external business, loan or marketing outcome is claimed.

**Open in Colab:** https://colab.research.google.com/drive/1FTRFwZfZ8-Oj3hNMn4p3_GHcBjZBJeJH

**Preview on GitHub:** https://github.com/Ssaqlain09/weather-data-science-20-projects/blob/main/Projects/Project%2020/Project_20_End_to_End_ML_System_Design.ipynb

**Notebook file:** `Projects/Project 20/Project_20_End_to_End_ML_System_Design.ipynb` — shared in Drive as Anyone with the link, Viewer.

## Notes and honest limitations

- The original project statement PDF says "Do only any 15 problems" (15 marks, due 28 January 2026). The user explicitly instructed ALL 20 projects, so all 20 were completed.
- Only the attached weather dataset was used. Where an original problem assumes data this file lacks (timestamps, text logs, demographics, loan/marketing data, 10,000 features, a <2% class), the notebook implements the closest valid analogue and states the limitation in the notebook and in that project's section above. No columns, timestamps, demographics or other datasets were invented.
- Several results are non-improvements and are reported as such: stable-only retraining (Project 3), reweighting parity gap (Project 6), expanded feature selection vs base-7 (Project 7), binned features vs raw numbers (Project 11), and calibration for LogisticRegression (Project 12).
