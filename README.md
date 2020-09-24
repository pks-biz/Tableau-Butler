# Tableau-Butler

This code is about automating some Self-Service tasks on a Tableau installation through the use of Tableau's APIs.
To begin with you need some pre-reqs

## Pre-requisites
1. Install Python on your system. This can be done in multiple ways but my preferred method is with Anaconda and you can find instructions to do the same here (https://docs.google.com/document/d/1Vg2IUihYZbGyz7D6uJoagGMRB7rFvjDXy6wTXcZlLj8/edit?usp=sharing).
2. Download the Jupyter Notebook (remove_users.ipynb) in this repository and open it with Jupyter Lab in Anaconda.
3. Your Server login details with Server Administrator or Site Administrator access.
3. The code will require a Tableau workbook connecting to the Postgres Database of the relevant Server.
4. After the Tableau workbook is ready use the attached notebook code to remove users.

## Connecting to the Postgres database
To connect to the Postgres database you will require a username and password which can be enabled using the instructions in this Tableau Help article (https://help.tableau.com/current/server/en-us/perf_collect_server_repo.htm).
You can use the Tableau Server Data Dictionary to find other tables to connect to and get more information about the Tableau Server (https://tableau.github.io/tableau-data-dictionary/2020.3/data_dictionary.htm)
