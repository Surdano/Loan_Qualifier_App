# Loan Qualifier Application

![A scale, with a bag of money named loan on one side and a image of a house on the other.](https://assets.telegraphindia.com/telegraph/2021/Sep/1631050353_shutterstock_1219076071.jpg)
 
---
## What it does

This is a python command-line-interface(CLI) that allows users to see qualifying loans from lenders quickly and easily. The application works by taking in a `daily_rate_sheet` of loan criteria from various loan providers, asking the user a number of questions to evaluate their loan eligibility, and then returning to them a list of qualifying loans. It also asks if the user wishes to save the returned list of qualifying loans.

---

## Technologies

This application runs on python 3.7 and python 3.8 with the following packages:

* [fire](https://github.com/google/python-fire) - For the command line interface, help page, and entrypoint.

* [questionary](https://github.com/tmbo/questionary) - For interactive user prompts and dialogs

---

## Installation Guide

Before running the application first install the following dependencies.

```python
  pip install fire
  pip install questionary
```

---

## Usage

To use the loan qualifier application simply clone the repository and run the **app.py** with:

```python
python app.py
```
It will then promt the user to input the following .csv file path:

```python
data/daily_rate_sheet.csv
```

Upon launching the loan qualifier application the user will be greeted with the following prompts:

![Screen shot of promts with examples as enrties](https://user-images.githubusercontent.com/89755088/136319694-5f0d1290-b696-4d9b-bd2d-298eac9d56da.png) 

It then leads the user through additional promts to save the results as a .csv file:

![Screen shot of promts to save returned results as a .csv](https://user-images.githubusercontent.com/89755088/136486007-0ef8eb9e-763f-4eae-9876-214d57dae80b.png)

Here is the application run through all promts:

![Screen shot of all application promts and return](https://user-images.githubusercontent.com/89755088/136484577-37ad8535-6e32-4a75-9873-91041c141c5d.png)


---

## Contributors

This code was created from © 2020 - 2021 Trilogy Education Services, a 2U, Inc. brand. 

Additional code was added for applicationusability by Thomas Leahy, thomasleahy6@gmail.com

---

## License

MIT Licence

2021 Thomas Leahy