This project explores what factors influence song popularity on Spotify using audio features and categorical metadata.
Developed as the final project for an Intro to Data-Centric Computing course, the analysis focuses on interpretable modeling, feature engineering, and model diagnostics rather than black-box prediction.

Data

Source: Spotify track audio features dataset

Observations: [insert # tracks]

Target Variable: track_popularity (continuous)

Key Features:

Danceability

Energy (including nonlinear transformations)

Tempo

Liveness (log-transformed)

Playlist genre (categorical)

Mode (major/minor)

Methods & Techniques

Exploratory Data Analysis (EDA)

Feature engineering (polynomial & log transformations)

Interaction terms with categorical variables

Multiple linear regression using statsmodels

Model diagnostics:

Residual plots

Predicted vs. observed analysis

Coefficient interpretation
Key Findings

Certain audio features have nonlinear relationships with popularity

The effect of features like energy and danceability varies significantly by genre

Including interaction terms improved interpretability and model performance

Visual diagnostics were critical in identifying model limitations
