# Number Sequence Predictor

This project is a web-based number sequence predictor. It is designed for experimenting with predicting tokens or number sequences, such as those found in games, lotteries, or other applications where forecasting the next set of numbers is desired.

## Features
- Input historical number sequences (one per line, hyphen-separated)
- Multiple prediction models: Linear Regression, Persistence, Most Frequent, Random
- Confidence estimates for predictions (Most Frequent model)
- Chart visualization of past trends and predictions
- Export predictions and input data to CSV
- Local persistence of input data (localStorage)
- Clear/reset button for easy interaction

## Usage

### Running Locally
1. Open `index.html` in your web browser.
2. Enter your historical sequences and select a prediction model.
3. Click "Forecast Next Sequence" to generate a prediction.
4. Use the export, chart, and clear features as needed.

### Deploying (e.g., on Vercel)
- Ensure your main file is named `index.html` and is in the root directory.
- Deploy the project folder to Vercel as a static site.
- The app will be available at your Vercel deployment URL.

## For Future Updates & Development
- This app is intended for experimenting with token/number prediction.
- You can extend it by adding new models, improving the UI, or integrating with APIs.
- For feature requests or contributions, fork the project and submit a pull request.
- Ideas for future development:
  - Add authentication for user-specific data
  - Integrate with blockchain/token APIs
  - Add more advanced ML models
  - Improve mobile responsiveness

## Disclaimer
This tool is for educational and experimental purposes only. Predictions for random processes (like lotteries) are not reliable.

---

Feel free to modify and extend this project for your own use case! 