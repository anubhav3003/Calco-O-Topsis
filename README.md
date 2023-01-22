# Topsis-102003551
Topsis-102003551 is a Python package implementing Topsis method for multi-criteria decision analysis.
Topsis stands for Technique for Order of Preference by Similarity to Ideal Solution

Just provide your input attributes and it will give you the results


## Installation

$ pip install topsis-102003551==1.0.0

## Usage
In the commandline, you can write as -
    $ python <package_name> <path to input_data_file_name> <weights as strings> <impacts as strings> <result_file_name>

E.g for input data file as (102003551-data.csv), command will be like
...
    $ python topsis.py data.csv "1,1,1,1,1" "+,-,+,-,+" output.csv
...
This will print all the output attribute values along with the Rank column, in a tabular format

## Example

102003551-data.csv
    
Fund Name	P1	P2	P3	P4	P5
M1	0.84	0.71	6.7	42.1	12.59
M2	0.91	0.83	7	31.7	10.11
M3	0.79	0.62	4.8	46.7	13.23
M4	0.78	0.61	6.4	42.4	12.55
M5	0.94	0.88	3.6	62.2	16.91
M6	0.88	0.77	6.5	51.5	14.91
M7	0.66	0.44	5.3	48.9	13.83
M8	0.93	0.86	3.4	37	10.55
    
weights vector = [ 0.50 , 0.50 , 0.50 , 0.50 , 0.50 ]
impacts vector = [ + , - , + , - , + ]

## License
MIT  
