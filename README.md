import csv

class Stock:
    def __init__(self, filename)
    # open the Dow Data csv file
        with open(filename, "r") as file:
            reader = csv.DictReader(file)

print