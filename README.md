# JPMC Task 1
Starter repo for task 1 of the JPMC software engineering program
---

# Stock Price Data Feed Integration for Trader's Dashboard

This project enhances a trader's dashboard with features to monitor two correlated stocks and visualize potential trading opportunities based on their historical price movements.

## Objective

The objective is to develop a tool that allows traders to:
- Monitor two historically correlated stocks.
- Visualize when the correlation weakens, suggesting potential trading strategies.
- Implement trade strategies such as buying the relatively underperforming stock and selling the outperforming stock, anticipating price convergence.

## Requirements

1. **Data Feed Integration**:
   - Interface with a financial data feed to retrieve real-time or near-real-time stock prices.
   - Ensure reliability and accuracy of data fetched.

2. **Correlation Analysis**:
   - Calculate and monitor the historical correlation coefficient between two selected stocks.
   - Detect when the correlation weakens, indicating potential divergence in stock price movements.

3. **Visualization**:
   - Utilize JPMorgan Chase's Perspective data visualization software.
   - Create interactive charts to display the correlation trends over time.
   - Highlight periods of divergence to assist traders in identifying trade opportunities.

4. **Trade Strategy Implementation**:
   - Provide insights into potential trading strategies based on correlation analysis.
   - Alert traders when significant divergence is detected, suggesting possible trade actions.

## Implementation Steps

1. **Data Fetching**:
   - Implement mechanisms to fetch stock prices from reliable financial data sources.
   - Ensure robust error handling and data validation.

2. **Correlation Calculation**:
   - Develop algorithms to compute the correlation coefficient between selected stock pairs.
   - Implement rolling window calculations for dynamic correlation updates.

3. **Visualization Setup**:
   - Configure Perspective data visualization software.
   - Customize charts to visualize correlation trends effectively.
   - Ensure interactive features for user-friendly exploration of data.

4. **Testing and Validation**:
   - Conduct thorough testing to validate data fetching, correlation calculations, and visualization outputs.
   - Verify the accuracy of trade strategy suggestions based on historical data analysis.

## Usage

1. Clone the repository:
   ```bash
   git https://github.com/sujalkamanna/forage-jpmc-swe-task-1.git
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the file:
   ```bash
   python client3.py and server3.py
   ```

## Resources

- [Perspective Data Visualization Software](https://github.com/jpmorganchase/perspective)

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your enhancements.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

---
