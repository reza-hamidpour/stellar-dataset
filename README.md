# stellar-dataset

We ghatheread this dataset from Stellar Exchange network from Dec. 1st, 2018 until Dec. 30th 2019.
These are sell and purchrase offers, you can download these files from [here](https://drive.google.com/drive/folders/19BlliamJnfxTQWerCqaEw9VzQjRcOEyi?usp=sharing). 


# How to Use this Dataset
These files are [Mongodb](https://www.mongodb.com/) export, you should install mongodb first and then import theme into mongodb.
After importing these files, you can query on theme.

# 1- Installation
  install Mongodb based on your OS, [here](https://docs.mongodb.com/manual/installation/).
# 2- Usage
2- Import datasets into your Mongodb database by mongoshell commands.
```bash
importmongodb --db=[YOUR_DATABSE_NAME] --collection=operation [OPERATION_FILE_NAME.json]
importmongodb --db=[YOUR_DATABSE_NAME] --collection=ledgers [LEDGER_FILE_NAME.json]
```
# Why we use Mongodb as our database?
Mongodb is an unstructured database which facilate your performanse and processing speed while you use unstructured data.
We had a huge data set with some null attributes.
If you would like to learn [more](https://docs.mongodb.com/manual/indexes/) about indexing and improving query speed on this data set, you should use indexing in Mongodb.
