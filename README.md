# AI-Powered-Traffic-Management-for-Atlanta-s-FIFA-World-Cup-2026
Atlanta, Georgia will host 8 FIFA World Cup 2026 matches at Mercedes-Benz Stadium (June 15 – July 15, 2026), including a Semifinal. The city is chronically congested; without proactive management, match days risk gridlock on I-20, I-75/85, and I-285 — affecting fans, residents, and emergency services.
This notebook implements an end-to-end AI traffic prediction system using a dual-model ensemble:

LSTM Neural Network — learns time-series traffic patterns (hourly peaks, weekly cycles)
XGBoost Regressor — exploits structured features (event flags, weather, lag statistics)
Weighted Ensemble — combines both models for the final hourly congestion forecast
