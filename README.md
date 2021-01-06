# Basal temperature method
Basal temperature method algorithm test implementation based on [wikipedia article](https://de.wikipedia.org/wiki/Temperaturmethode) description. With the basal temperature method the possible ovulation date can be calculated. The ovulation date is an important part of birth control, contraception, fertility control.
## Run script
The script was made only for testing purposes. To run the script just use python in command line
```shell
python ovulation_calculation.py
```
## Edit
The temperature and dates can be added manualy in the file ovulation_calculation.py. File includes couple list with example basal temperature sequence.
```python
temperature_list = (
    {'date': '2020-01-01', 'temperature': 36.6},
    {'date': '2020-01-02', 'temperature': 36.7},
    {'date': '2020-01-03', 'temperature': 36.5},
    {'date': '2020-01-04', 'temperature': 36.6},
    {'date': '2020-01-05', 'temperature': 37.4},
    {'date': '2020-01-06', 'temperature': 37.3},
    {'date': '2020-01-07', 'temperature': 36.8},
    {'date': '2020-01-08', 'temperature': 36.8},
    {'date': '2020-01-09', 'temperature': 36.9},
    {'date': '2020-01-10', 'temperature': 36.7},
    {'date': '2020-01-11', 'temperature': 36.8},
    {'date': '2020-01-12', 'temperature': 36.6},
    {'date': '2020-01-13', 'temperature': 36.6},
    {'date': '2020-01-14', 'temperature': 36.6},
    {'date': '2020-01-15', 'temperature': 36.5},
    {'date': '2020-01-16', 'temperature': 36.4},
    {'date': '2020-01-17', 'temperature': 36.7},
    {'date': '2020-01-18', 'temperature': 36.9},
    {'date': '2020-01-19', 'temperature': 37.1},
    {'date': '2020-01-20', 'temperature': 37.2},
    {'date': '2020-01-21', 'temperature': 37.2},
    {'date': '2020-01-22', 'temperature': 37.3},
    {'date': '2020-01-23', 'temperature': 37.0},
    {'date': '2020-01-24', 'temperature': 37.0},
    {'date': '2020-01-25', 'temperature': 37.1},
    {'date': '2020-01-26', 'temperature': 36.9},
    {'date': '2020-01-27', 'temperature': 37.0},
    {'date': '2020-01-28', 'temperature': 37.0},
    {'date': '2020-01-29', 'temperature': 36.9},
    {'date': '2020-01-30', 'temperature': 36.8},
)
```
