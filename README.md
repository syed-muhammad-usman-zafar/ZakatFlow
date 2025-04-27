# Zakatify - Automated Zakat Computation System

Zakatify is a web app built to help individuals easily calculate their Zakat obligations based on their total wealth, gold, silver, investments, and liabilities. It helps users determine whether they meet the Nisab threshold and calculates how much Zakat they owe, all using the latest currency exchange rates.

## Features

- **Currency Conversion**: Allows users to input their wealth and liabilities in different currencies (PKR, GBP, AED, USD).
- **Precious Metals Pricing**: Users can input the current prices of gold and silver in PKR.
- **Zakat Calculation**: Based on the user's inputs, the app calculates the total wealth, compares it to the Nisab threshold, and computes the Zakat due.
- **Wealth Distribution Visualization**: Displays a pie chart showing the distribution of the user's wealth across various categories (e.g., Cash, Gold, Silver, etc.).

## How to Use

1. **Select Currency**: Choose the currency you want to use from the dropdown (PKR, GBP, AED, or USD).
2. **Enter Your Assets and Liabilities**: Fill in the values for your cash, gold, silver, investments, business merchandise, property, receivables, and debts.
3. **Enter Current Gold and Silver Prices**: Input the current price of gold and silver per gram in PKR.
4. **Click "Calculate Zakat"**: Press the button to calculate your Zakat. The app will display:
    - Total Net Wealth
    - Nisab Threshold
    - Zakat Due (if applicable)
    - A pie chart showing the wealth distribution.

## App Demo

You can access the live demo of this app here: https://zakatify.streamlit.app/

## Tech Stack

- **Streamlit**: For building and deploying the web app.
- **Plotly**: For creating interactive visualizations (pie chart showing wealth distribution).
- **Forex Python**: For fetching live currency exchange rates.
- **Python**: The backend logic and computations for Zakat calculations.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/syed-muhammad-usman-zafar/Zakatify.git
    cd Zakatify
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Run the app locally:

    ```bash
    streamlit run zakatify.py
    ```

4. The app will be available at `http://localhost:8501` on your browser.

## Dependencies

The following dependencies are required to run the app:

- streamlit
- plotly
- forex-python

You can install them using the command:

```bash
pip install streamlit plotly forex-python
 ```

## License
This project is open source and available under the MIT License.

## Created by
Usman Zafar

LinkedIn: https://www.linkedin.com/in/usman--zafar/
