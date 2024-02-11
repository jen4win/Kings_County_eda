# Kings_County_eda

## Context and Objective
This project is centered around exploratory data analysis and stakeholder presentation. It focuses the King County Housing Dataset and aims to recommend houses for the client.
The dataset contains information about houses in King County (USA), which needs to be shaped to meet the requirements of a client. 

__The client__

Here the client is Jacob Phillips. He wants to buy a house with 4+ bathrooms, which has a big lot for a tennis court and a pool. His budget is unlimited, which makes the price a subordinate characteristic. It should not be at the waterfront. As he is a golf enthusiast, he wants a golf resort nearby. The historical character of the house is optional.

## Usage
- The data is retrieved from the Postgres database SQL-Playground, which is the content of the notebook `Fetching_from_SQL.ipynb`.
- All steps for answering the hypothesis by descriptive statistics and plotting are done in the notebook `main.ipynb`.
- Data Cleaning can be followed in detail in the `Data_Cleaning.ipynb` notebook.  
- Some graphs are stored in the `graphs`-directory.

## Note
To execute the code correctly the appropriate environment needs to be installed. All required packages are given in `requirements.txt`.

```bash
pyenv local 3.11.3
python -m venv .venv
source .venv/Scripts/activate
pip install --upgrade pip
pip install -r requirements.txt
```