# 🎵 Spotify Premium Churn Prediction (Machine Learning)

## Overview
This project simulates and analyzes Spotify user data to predict Premium subscription churn. Built a Random Forest Classifier achieving **98.55% accuracy** in identifying high-risk users.

## Key Insights
The ML model identified that traditional engagement metrics (hours listened) do NOT drive retention. The top 3 features driving churn are:
1. **High Skip Rate (30%)** - Algorithmic frustration (Discover Weekly misalignment).
2. **Low Friend Connections (27%)** - Lack of social lock-in.
3. **Zero Playlists Created (26%)** - Low emotional/time investment in the platform.

## Tech Stack
- Python (Pandas, NumPy)
- Machine Learning (Scikit-Learn, Random Forest)
- Data Visualization (Seaborn, Matplotlib)

## Proposed Product Solutions
Based on the data, I proposed 3 product interventions to decrease churn:
- **"AI Vibe Reset"**: Real-time algorithm correction for users with a high skip-streak.
- **"Forced Social Onboarding"**: Gamified contact syncing to boost the social graph.
- **"1-Click Playlist Generator"**: Lowering the barrier to user investment.

*Full Product Teardown available on my Medium*
