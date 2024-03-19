# Financial Fraud Analysis

## Overview
Financial Fraud Analysis is a project aimed at analyzing fraud in financial payment services using a large dataset. Inspired by a JP Morgan Cybersecurity Study Case via Forage, this project delves into the detection and prevention of fraudulent activities within the financial sector.

## Scenario
As a cybersecurity analyst participating in the JP Morgan Cybersecurity virtual internship via Forage, you are tasked with analyzing a large dataset of financial transactions. The dataset includes various transaction types such as deposits, withdrawals, payments, and transfers, providing a comprehensive view of transactional activities within financial institutions.

## Process
1. **Read the Dataset**: Read the dataset ('transactions.csv') as a Pandas dataframe, where the first row contains column names.
2. **Extract Column Names**: Extract the column names as a list from the dataframe.
3. **Explore Data**: Retrieve the first k rows from the dataframe to gain an initial understanding of the data. Obtain a random sample of k rows from the dataframe for further exploration.
4. **Visualization**: Create visualizations, such as scatter plots, to analyze specific transaction types and identify patterns or anomalies, such as the Origin account balance delta vs. Destination account balance delta for Cash Out transactions.
5. **Fraud Detection**: Utilize fraud detection mechanisms to identify and analyze fraudulent transactions flagged by the system, distinguishing between flagged frauds and actual frauds.

## How to Use
1. Clone the repository to your local machine.
2. Open `task1.ipynb` in Google Colab or any Jupyter notebook environment.
3. Run the notebook cells to execute the code and analyze the data.

## Resources
- [Forage](https://www.theforage.com/?ref=g45XpK5j36bJjxWdA)

## License
This project is licensed under the MIT License. See the [LICENSE](https://github.com/AhsanA3/Financial-Fraud-Analysis/blob/main/LICENSE) file for details.

## Contributors
- [Ahsan Akoshile](https://github.com/AhsanA3)
