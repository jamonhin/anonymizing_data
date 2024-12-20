# anonymizing_data

This project demonstrates how to anonymize sensitive customer data for a Data Science challenge at Commonwealth Bank. The data includes personal information such as names, addresses, emails, and credit card details, which are anonymized to protect customer privacy.

## Project Structure

```
.DS_Store
cb_data_anonymisation.ipynb
data/
    .DS_Store
    mobile_customers.xlsx
README.md
result/
    anonymized_mobile_customers.csv
```

- `cb_data_anonymisation.ipynb`: Jupyter notebook containing the code to anonymize the data.
- `data/mobile_customers.xlsx`: Excel file with the original customer data.
- `result/anonymized_mobile_customers.csv`: CSV file with the anonymized customer data.

## How to Run the Code

1. **Install the required libraries**:
   Make sure you have `pandas`, `openpyxl`, and `faker` installed. You can install them using pip:

   ```sh
   pip install pandas openpyxl faker
   ```

2. **Open the Jupyter Notebook**:
   Open `cb_data_anonymisation.ipynb` in Jupyter Notebook or JupyterLab.

3. **Run the Notebook**:
   Execute the cells in the notebook to read the original data, anonymize it, and save the anonymized data to `result/anonymized_mobile_customers.csv`.

4. **Check the Results**:
   The anonymized data will be saved in the `result` directory as `anonymized_mobile_customers.csv`.

## Example Usage

Here is an example of how to run the notebook:

```sh
jupyter notebook cb_data_anonymisation.ipynb
```

Open the notebook in your browser and run all cells to perform the data anonymization.

## License

This project is licensed under the MIT License.