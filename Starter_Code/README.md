# Crypto Abritrage Analysis

To the Vice President of Data Analysis,

Through tireless endeavours, I present to you the possible arbitrage opporunities present with Bitcoin. Utilizing historical data from two of the most prominent US-based Centralized Exchanges (Coinbase, Bitstamp), we have many paths to a profitable future in the Crypto trading economy.

---

## Technologies

I have utilized Python with the Pandas and Pathlib libraries for seemless data transfer, expedient math calculations, and accurate data visualization.

---
---

## Installation Guide

To begin using the notebook in Jupyter Labs:

### Part 1
1. Open "crypto_arbitrage.ipynb".
2. Look for the following:
    ```python
    bitstamp_df = pd.read_csv(
        Path("Resources/bitstamp.csv"),
        index_col = "Timestamp",
        parse_dates = True,
        infer_datetime_format = True
    )
    ```
3. Ensure that "Path()" has the correct .csv file you are utilizing for data manipulation.
4. If correct .csv file is unavailable, transfer the .csv file into the "Resources" folder located within this parent folder.
5. Replace "bistamp_df" and "bitstamp.csv" with the correct Exchange and .csv file name. NOTE: Make sure to add ".csv" to the file name.
6. If necessary, repeat steps 1-5 with the second exchange to be compared with.

### Part 2
1. Once the necessary changes have been made, click "Run All" at the top navigation bar.
2. Witness the data form before your eyes.

---

## Documentation
Please reference the following screenshots for guidance with any changes within the code:

### (Demonstration) Using data from Binance

![Alt text] (https://github.com/antonmaliksi/FinTechModule3Challenge/blob/main/Starter_Code/README%20Resources/parent_folder.PNG)

![Alt text] (https://github.com/antonmaliksi/FinTechModule3Challenge/blob/main/Starter_Code/README%20Resources/resources.PNG)

![Alt text] (https://github.com/antonmaliksi/FinTechModule3Challenge/blob/main/Starter_Code/README%20Resources/using_binance.PNG)

---

## Contributors
All work was completed by Anton Maliksi.

---

## License
No licenses were used for this notebook.
