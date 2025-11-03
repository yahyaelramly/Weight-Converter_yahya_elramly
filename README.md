weight = int(input("Enter your weight: "))
units = input("lbs or kg: ")
if units.lower() == "lbs":
    converted=weight*0.45
    print(f"Your weight is {converted} kg")
else:
    converted=weight/0.45
    print(f"Your weight is {converted} lbs")
