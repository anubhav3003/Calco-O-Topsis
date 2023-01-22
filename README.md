# Topsis-102003551
Topsis-102003551 is a Python package implementing Topsis method for multi-criteria decision analysis.
Topsis stands for Technique for Order of Preference by Similarity to Ideal Solution

Just provide your input attributes and it will give you the results


## Installation

$ pip install topsis-102003551

In the commandline, you can write as -
    $ python <package_name> <path to input_data_file_name> <weights as strings> <impacts as strings> <result_file_name>

E.g for input data file as data.csv, command will be like
    $ python topsis.py data.csv "1,1,2,1,2" "+,-,+,-,+" output.csv

This will print all the output attribute values along with the Rank column, in a tabular format

License -> MIT
