# Loan Application

## Description
The application utilizes calculations of month debt ratio, loan to value ratio and `data_rate_sheet.csv` to extract information for which loan the user qualifies for. The application will ask for the user's information to compare with other loans from different banks. Once the application has all available loans, it will generate the loans the user is qualified for in `qualified_loans.csv`


---


## Installation Guide
Both tools use python 3.7:  

[Python Fire](https://github.com/google/python-fire) - is utilized to create CLI in Python  

[Questionary](https://pypi.org/project/questionary/) - is a library allowing users to utilize CLI in Python  

### Installing Pyhton Fire and Questionary  
Open Git Bash or Terminal and type the commands below:  

Python Fire  

```Pip install fire```
  
Questionary  

```Pip install questionary```

---
## Run the application

To run the application:

- Clone respository using Git Bash or Terminal  
- Open the `loan_qualifier_app` application
- In git bash, terminal or vscode run:
   
   ```python app.py```


