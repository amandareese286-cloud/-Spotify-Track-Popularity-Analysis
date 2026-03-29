This project explores what factors influence song popularity on Spotify using audio features and categorical metadata.
The analysis prioritizes interpretability, feature engineering, and model diagnostics rather than black-box prediction.

Data

Source: Spotify track audio features dataset

Target Variable: track_popularity (continuous)

Key Features: Danceability, Energy (including nonlinear transformations), Tempo, Liveness (log-transformed), Playlist genre (categorical), Mode (major/minor)

Methods & Techniques

Exploratory Data Analysis (EDA) to assess feature distributions and relationships
Feature engineering, including polynomial and log transformations
Interaction terms between audio features and categorical variables
Multiple linear regression implemented using statsmodels
Model diagnostics:

Residual analysis
Predicted vs. observed comparisons
Coefficient interpretation
Key Findings

Several audio features demonstrate nonlinear relationships with song popularity
The influence of features such as energy and danceability varies significantly by genre
Incorporating interaction terms improved both model interpretability and overall model fit
Visual diagnostics played a critical role in identifying model limitations and assessing assumptions
