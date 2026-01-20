# TOPSIS Implementation using Python (Colab)

This repository contains a **Google Colab notebook** implementing the
**TOPSIS (Technique for Order Preference by Similarity to Ideal Solution)** method.

The implementation follows a **command-line style interface** using `sys.argv` and supports **Excel (.xlsx)** input files.

---

##  Features

* Implements TOPSIS decision-making method
* Accepts weights and impacts as command-line arguments
* Performs required validations:

  * File existence
  * Minimum column count
  * Numeric criteria validation
  * Weights and impacts length check
* Generates TOPSIS score and rank



##  Usage (Command-Line Logic)

```bash
python topsis.py data.xlsx "1,1,1,2,1" "+,+,-,+,+" output-result.xlsx
```



---

##  Requirements

* Python 3
* pandas
* numpy
* openpyxl

---

##  Author

ISHWIN
