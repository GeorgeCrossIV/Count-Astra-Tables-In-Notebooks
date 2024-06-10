# Count Astra DB tables in Notebooks

This repository contains a Jupyter Notebook that demonstrates how to use DSBulk to count the number of records in a table on Astra DB. The notebook includes steps to download, extract, and run DSBulk with user-provided credentials and necessary configurations.

## Prerequisites

- Jupyter Notebook
- Astra DB account
- Secure connect bundle for your Astra DB instance

## Notebook Overview

### 1. Download DSBulk

The notebook starts by downloading the DSBulk tool from DataStax.

```python
# Download DSBulk
!wget https://downloads.datastax.com/dsbulk/dsbulk.tar.gz

# Extract DSBulk
!tar -xvf dsbulk.tar.gz

# Make dsbulk executable
!chmod +x dsbulk-1.11.0/bin/dsbulk
