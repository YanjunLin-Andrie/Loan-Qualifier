
![](https://www.mtgprofessor.com/images/canstockphoto18796600.jpg)
# Loan Qualifier App

>This App is designed to be mainly used by loan institutions and their customers to quickly narrowing down a list of potential banks that would approve their loan applications based on customer's **credit score**, **current debt**, **monthly income**, **loan amount**, and their **current home value**.
---

## Technologies

This project leverages python 3.7 with the following packages:

* [fire](https://github.com/google/python-fire) - For the command line interface, help page, and entry-point.

* [questionary](https://github.com/tmbo/questionary) - For interactive user prompts and dialogs

---

## Installation Guide

Before running the application first install the following dependencies in Terminal or Bash.

```python
  pip install fire
  pip install questionary
```

---

## Usage

To use the Loan Qualifier application, users will conduct a series of **CLI** (Command Line Interface) interactions. Simply clone the repositor. Open Terminal or Bash and use `cd` to change directory to where the **app.py** file is located. Then type

```python
python app.py
```
to launch the app. Users will need to answer a flow of questions, such as shown below. 

![Loan Qualifier Prompts](images/loan_qualifier.png)


Upon finishing, users will get a result of their **DTI** (monthly debt to income) ratio, **LTV** (loan to value) ratio, number of qualifying loans, as well as the list of offering banks saved in their desired folder.


---

## Contributors

Brought you by **Yanjun Lin Andrie**

* yanjun.lin.andrie@gmail.com

* https://www.linkedin.com/in/yanjun-linked



---

## License

MIT
