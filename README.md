🎵 Spotify Music Popularity Prediction

This R project analyzes Spotify track data to predict song popularity based on features like danceability, energy, loudness, valence, and tempo. It includes data cleaning, visualization, and a linear regression model.

🧰 Tools & Libraries

R, tidyverse, caret, corrplot, GGally, ggthemes

⚙️ Workflow

Load and clean Spotify dataset

Perform EDA and visualize correlations

Train linear regression model

Evaluate with RMSE

Visualize top artists and feature trends

📈 Key Insight

Danceability, energy, and valence strongly influence song popularity.

🚀 Run
install.packages(c("tidyverse","caret","corrplot","GGally","ggthemes"))
source("spotify_music_prediction.R")
