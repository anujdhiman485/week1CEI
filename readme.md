# Basic Data Exploration and Cleaning using Pandas

## Project Objective
This project demonstrates basic data exploration and cleaning using Python and Pandas.

The dataset was loaded from a CSV file and several preprocessing operations were performed to clean and analyze the data.

---

## Technologies Used
- Python
- Pandas
- Jupyter Notebook
- VS Code

---

## Dataset Information
The dataset contains shopping transaction details such as:
- Order ID
- Customer Name
- Product
- Category
- Price
- Quantity
- Date
- Payment Method

---

## Tasks Performed

### 1. Loaded CSV Dataset
The shopping dataset was loaded into a Pandas DataFrame.

### 2. Explored Dataset
Performed:
- head()
- tail()
- shape
- columns
- dtypes
- info()
- describe()

### 3. Handled Missing Values
Checked and handled missing values using Pandas functions.

### 4. Filtered Data
Selected specific columns and filtered rows based on conditions.

### 5. Removed Duplicate Records
Duplicate rows were identified and removed.

### 6. Created Derived Column
Created a new column:

```python
total_amount = price * quantity
```

### 7. Saved Cleaned Dataset
The cleaned dataset was exported as a new CSV file.

---

## Project Structure

```text
Basic-Data-Cleaning-Pandas/
│
├── data/
│   ├── shopping.csv
│   └── cleaned_shopping.csv
│
├── notebook/
│   └── data_cleaning.ipynb
│
├── README.md
└── requirements.txt
```

---

## Output Files
- data_cleaning.ipynb
- cleaned_shopping.csv

---

## Author
Anuj