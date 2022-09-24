![GitHub](https://img.shields.io/github/license/aliasgharheidaricom/Wavelet-PM2.5-Prediction-System)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/aliasgharheidaricom/Wavelet-PM2.5-Prediction-System)
![GitHub repo size](https://img.shields.io/github/repo-size/aliasgharheidaricom/Wavelet-PM2.5-Prediction-System)
![GitHub language count](https://img.shields.io/github/languages/count/aliasgharheidaricom/Wavelet-PM2.5-Prediction-System)
![GitHub last commit](https://img.shields.io/github/last-commit/aliasgharheidaricom/Wavelet-PM2.5-Prediction-System)
# A wavelet PM2.5 prediction system using optimized kernel extreme learning with Boruta-XGBoost feature selection

<div align="center">
  <img src="Flowchart of the proposed system.png">
</div>



Abstract

Fine Particulate Matter (PM2.5) concentration has been a vital source of info and an essential indicator for measuring and studying the concentration of other air pollutants. It is crucial to realize more accurate predictions of PM2.5 and establish a high-accuracy PM2.5 prediction model due to their social impacts and cross-field applications in geospatial engineering. To further boost the accuracy of PM2.5  prediction results, this paper proposes a new wavelet PM2.5 prediction system (shortly called WD-OSMSSA-KELM model) based on a new, improved variant of the salp swarm algorithm (OSMSSA), kernel extreme learning machine (KELM), and wavelet decomposition and Boruta-XGBoost (B-XGB) feature selection. First, we have applied the B-XGB feature selection to realize the best features for predicting hourly PM2.5 concentrations. Then, we applied the wavelet decomposition (WD) algorithm to reach the multi-scale decomposition results and single-branch reconstruction of PM2.5 concentrations to mitigate the prediction error produced by time-series data. In the next stage, we optimized the parameters of the KELM model under each reconstructed component. An improved version of the SSA has been proposed to reach higher performance for the basic SSA optimizer and avoid local stagnation problems. In this work, we propose new operators based on oppositional-based learning and simplex-based search to mitigate the core problems of the conventional SSA. In addition, we utilize a time-varying parameter instead of the main parameter of the SSA. To further boost the exploration trends of SSA, we propose using the random leaders to guide the swarm towards new regions of the feature space based on a conditional structure. After optimizing the model, the optimized model was utilized to predict the PM2.5 concentrations, and different error metrics were applied to evaluate the model's performance and accuracy. The proposed model has been evaluated based on an hourly database, 6 air pollutants, and 6 meteorological features collected from the Beijing Municipal Environmental Monitoring Center. \textcolor{blue}{The experimental results show that the proposed WD-OLMSSA-KELM model can predict the PM2.5 concentration with superior performance (R: 0.995029, RMSE: 11.906, MdAE: 2.424, MAPE: 9.768, KGE: 0.963$, R2: 0.990) compared to WD-CatBoost, WD-LightGBM, WD-Xgboost, and WD-Ridge methods.

Features and results

<div align="center">
  <img src="Structure of the decomposed input data.png">
</div>
 
 <div align="center">
  <img src=" Feature selection outputs.png">
</div>

 
<div align="center">
  <img src="Scatter plots of different optimized KELM models.png">
</div>

<div align="center">
  <img src="Scatter plots of different machine learning models.png">
</div>
