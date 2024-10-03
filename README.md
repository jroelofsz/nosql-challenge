# nosql-challenge

## Description

The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. You've been contracted by the editors of a food magazine, Eat Safe, Love, to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles.

## Setup


### Dependencies

This project uses MongoDB, please make sure you have it installed for your respective OS.

[MongoDB Install Instructions](https://www.mongodb.com/docs/manual/installation/)

This project also uses Pandas, please install it using the code below (if you don't have conda, you may have to research how to install it for your OS)

```shell
conda install pandas
```

## Overview

This project has 2 deliverables. 

```NoSQL_setup.ipynb```

    This file will setup the MongoDB for the uk_food collection. We then go through and add a document to the collection, and then transform the data types into more accessible types.

```NoSQL_analysis.ipynb```

    This file has multiple pipeline queries that analyze the amount of documents that match certain criteria. 


## Documentation

- [MongoDB Documentation](https://www.mongodb.com/docs/manual/)
- [pandas Documentation](https://pandas.pydata.org/docs/)
