# Count Astra DB tables in Notebooks

This repository contains a Jupyter Notebook that demonstrates how to use DSBulk to count the number of records in a table on Astra DB. The notebook includes steps to download, extract, and run DSBulk with user-provided credentials and necessary configurations.

## Prerequisites

- Jupyter Notebook
- Astra DB account
- Secure connect bundle for your Astra DB instance

## Notebook Overview
The notebook will do the following:
- Download the dsbulk tool
- Obtain the username/password (client ID/Secret)
- Run the dsbulk count command to obtain the count
