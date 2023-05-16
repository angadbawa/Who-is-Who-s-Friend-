# Who-is-Who-s-Friend-
 Friend Recommendation  in PySpark

This is a PySpark project that recommends friends for users based on their mutual friends. It takes as input a text file containing a list of users and their friends, and outputs a list of recommended friends for each user.

## Requirements

Python 3.6 or later
PySpark 3.0.1 or later
Apache Spark 3.0.1 or later

## Installation
```
To run this project, you will need to install PySpark. You can do this using pip:

pip install pyspark
```

## Usage
```
1. Clone the repository: git clone https://github.com/angadbawa/Who-is-Who-s-Friend-.git
2. Open the friend_recommend.ipynb Jupyter Notebook.
3. Modify the input file path in the first code cell to point to your input file.
4. Run the remaining code cells to generate the recommendations.
5. The output will be saved in the Result directory in text format.
```


## Input
```
The output will be a text file containing a list of recommended friends for each user. The file will be located in the 'Result'  directory and will be named part-*, where * is a number indicating the partition number. Each line in the file will contain a string in the following format:
'friend_data.txt' is the input file containing the social network graph.
```

## Output
```
The output will be a text file containing a list of recommended friends for each user. The file will be located in the 'Result'  directory and will be named part-*, where * is a number indicating the partition number. Each line in the file will contain a string in the following format:
``` 

```
(USER_ID, [REC_0, REC_1, ... REC_9])
```

For example:
```
(3124, [2345, 9213, 9129, 3923, 3227, 1346, 6857, 7512, 4314, 1217])
```

