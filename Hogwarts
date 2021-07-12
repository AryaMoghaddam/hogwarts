# hogwarts.py
building a list that coherently prompts the user for their desired house of Harry Potter.
import csv

houses ={
    "Gryf": 0,
    "Huf":0,
    "Raven": 0,
    "Slyt": 0,
}

with open ("Sorting Hat(Responses) - Form responses 1.csv" , "r") as file:  
    reader = csv.reader(file)
    next(reader)
    for row in reader:
        house = row[1]
        houses[house] += 1
    
for house in houses:
    print(f"{house}: {houses[house]}")
    # TODO: write code...
