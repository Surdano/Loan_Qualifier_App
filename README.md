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

Upon launching the loan qualifier application you will be greeted with the following prompts.

![Screen shot of promts with examples as enrties](https://user-images.githubusercontent.com/89755088/136319694-5f0d1290-b696-4d9b-bd2d-298eac9d56da.png) 



---

## Contributors

This code was created from © 2020 - 2021 Trilogy Education Services, a 2U, Inc. brand. 

Additional code was added for applicationusability by Thomas Leahy, thomasleahy6@gmail.com

---

## License

MIT Licence

2021 Thomas Leahy