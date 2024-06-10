# Count Astra DB Tables in Notebooks

This repository contains a Jupyter Notebook that demonstrates how to use DSBulk to count the number of records in a table on Astra DB. The notebook includes steps to download, extract, and run DSBulk with user-provided credentials and necessary configurations.

## Prerequisites

- A Notebook environment such as Jupyter or Google Colab
- [Astra DB account](https://www.datastax.com/products/datastax-astra)
- Secure connect bundle for your Astra DB instance

## Notebook Overview
The notebook will do the following:
- Download the dsbulk tool
- Obtain the username/password (client ID/Secret)
- Run the dsbulk count command to obtain the count

## Why Use DSBulk?

Counting large tables in Astra DB can be challenging because the `SELECT count(*)` query will time out for large datasets. DSBulk is specifically designed to handle large volumes of data efficiently and is required to perform this operation without running into timeouts.

## Steps in the Notebook

1. **Download the DSBulk Tool**: The notebook includes commands to download and extract the DSBulk tool.
2. **Set Up Credentials**: Instructions for obtaining and setting up your Astra DB credentials.
3. **Prepare the Secure Connect Bundle**: Guidance on uploading the secure connect bundle to the Jupyter Notebook environment.
4. **Run DSBulk Count Command**: Steps to run the DSBulk count command to get the number of records in your table.

For detailed instructions, please refer to the notebook included in this repository.
