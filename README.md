# LinkedIn Followers Tracker

This Python script collects follower counts for multiple LinkedIn company pages and saves the data to an Excel file. It’s useful for tracking multiple companies’ followers on a daily basis.

## Technologies

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white) ![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white) 

## Features

- Authenticate with LinkedIn to access company profiles.
- Retrieve follower counts for specified companies.
- Save follower data to an Excel file, with each day’s data stored in a separate sheet.

## Requirements

- Python 3.x
- `linkedin-api` library
- `pandas` library
- `openpyxl` library

## Setup

1. **Update Login Credentials**: replace the `login_lkd` and `password_lkd` variables with your LinkedIn credentials.

2. **Define Company IDs**: update the `company_ids` dictionary with the LinkedIn company IDs you want to track. You can find a company’s ID by using the `api.get_company()` method and extracting the ID from the returned LinkedIn URL (e.g. https://www.linkedin.com/vsearch/p?f_CC=2029 -> id = 2029).
   


The script will create or append to an Excel file named `linkedin_followers_data.xlsx`.
         
## Next step

Automate the data extraction to save to a Google Sheets document daily at a predefined time.
Contributions are welcome! If you have any suggestions, bug reports or ideas, let's work together to make this a tool for tracking competitors on LinkedIn.
