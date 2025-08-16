# Crash Predictor — Under Count Strategy with Martingale

This is a Streamlit app to predict “Above” or “Under” in a crash game using the last 20 rounds’ under counts. Includes three betting strategies:

- **Flat Bet**: 0.01 SOL per 'Above'
- **Fixed Bet**: 0.02 SOL only when 'Above'
- **Martingale Bet**: Custom sequence 0.01 → 0.02 → 0.05, then stops until under average reaches 8

## Features

- Upload CSV history or manually input multipliers
- Predict based on under count threshold
- Track accuracy of predictions
- Monitor balances for flat, fixed, and martingale strategies
- Reset history and balances

## Run

```bash
pip install -r requirements.txt
streamlit run app.py
