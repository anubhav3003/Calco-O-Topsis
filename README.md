# Topsis-102003551
Topsis-102003551 is a Python package implementing Topsis method for multi-criteria decision analysis.
Topsis stands for Technique for Order of Preference by Similarity to Ideal Solution

Just provide your input attributes and it will give you the results


## Installation

$ pip install topsis-102003551

## Usage
In the commandline, you can write as -
    $ python <package_name> <path to input_data_file_name> <weights as strings> <impacts as strings> <result_file_name>

E.g for input data file as data.csv, command will be like
    $ python topsis.py data.csv "1,1,2,1,2" "+,-,+,-,+" output.csv

This will print all the output attribute values along with the Rank column, in a tabular format

## Example

data.csv
    
Fund Name	P1	 P2	  P3  P4   P5
M1	        0.6	 0.36 7	  52.2 15.04
M2	        0.72 0.52 3.2 67.9 18.09
M3	        0.67 0.45 6.7 30.3 9.53
M4	        0.82 0.67 4.2 42.5 12.05
M5	        0.69 0.48 3.7 35.5 10.09
M6	        0.78 0.61 3.3 32.1 9.2
M7	        0.61 0.37 6.8 40.3 12.02
M8	        0.67 0.45 5.6 56.5 15.81
    
weights vector = [ 0.25 , 0.25 , 0.50 , 0.25 , 0.50 ]
impacts vector = [ + , - , + , - , + ]

## License
MIT
