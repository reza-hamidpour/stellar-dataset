# Stellar Dataset

We gathered this dataset from the Stellar Exchange network from Dec. 1, 2018 until Dec. 30, 2019.
These are sell and purchase offers and you can download them from [here](https://drive.google.com/drive/folders/19BlliamJnfxTQWerCqaEw9VzQjRcOEyi?usp=sharing). 


# How to Use this Dataset
These files are [MongoDB](https://www.mongodb.com/) exports. You should install MongoDB first and then import them into MongoDB.
After importing these files, you can run queries on them.

# 1- Installation
Install the version of MongoDB compatible with your OS, [here](https://docs.mongodb.com/manual/installation/).
# 2- Usage
Import datasets into your MongoDB database by the following mongoshell commands:
```bash
importmongodb --db=[YOUR_DATABSE_NAME] --collection=operation [OPERATION_FILE_NAME.json]
importmongodb --db=[YOUR_DATABSE_NAME] --collection=ledgers [LEDGER_FILE_NAME.json]
```
# Why Do We Use MongoDB as our Database?
MongoDB is an unstructured database which speeds up your performance and processing speed while you use unstructured data.
We had a huge data set with some null attributes.
If you would like to learn more about about indexing and improving query speed on this data set, you should use [indexing in MongoDB](https://docs.mongodb.com/manual/indexes/).

# How to Cite this Dataset?
Our published conference paper is [available from ResearchGate](https://www.researchgate.net/publication/349732142_Collection_and_Analysis_of_Financial_Exchange_Data_on_the_Stellar_Blockchain).

Citation: R. Hamidpour Badoe and S. Dorri Nogoorani, "Collection and Analysis of Financial Exchange Data on the Stellar Blockchain," _In Proceedings of the 6th International Conference on Distributed Computing and Big Data Processing_, Azarbaijan Shahid Madani University, Tabriz, Iran, Mar. 2021
