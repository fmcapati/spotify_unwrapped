# spotify_unwrapped
*Exploring the audio features that drive Spotify's popularity score using interpretable tools and counterfactual analysis*

---

# Abstract
In the modern music streaming era, artists and producers often lack quantifiable guidance on which musical characteristics drive a song’s success. This study utilizes the *30000 Spotify Songs* dataset consisting of 32,833 songs sourced from the Spotify API to investigate the relationship between intrinsic audio metadata (e.g. danceability, energy, and loudness) and Spotify’s internal popularity metric. The research follows a structured machine learning pipeline including conducting exploratory data analysis (EDA), preprocessing and scaling features, and training multiple regression models. To ensure the results are actionable, the study employs SHAP (SHapley Additive exPlanations) to interpret feature contributions and DICE (Diverse Counterfactual Explanations) to perform counterfactual analysis. This dual approach allows for the identification of specific changes in a song's audio profile that could potentially increase its predicted popularity score. The findings provide data-driven insights that bridge the gap between creative music production and commercial success in the streaming landscape.

**Highlights**

1. Random Forest performed the best against different regression models in predicting the popularity score of songs.
2. SHAP interpretation revealed that instrumentalness, loudness, and energy are the top features that contribute to a song's popularity score.
3. Counterfactual analysis using DICE showed that adjusting features (i.e. having higher or lower values) can potentially impact a song's popularity score.

**Keywords**

Spotify API, Machine Learning, Popularity Prediction, SHAP, Counterfactual Analysis (DiCE), Interpretability.
