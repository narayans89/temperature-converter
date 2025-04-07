# Temperature Converter 🌡️  

This repository has a simple script that converts Celsius to Fahrenheit and vice versa.  

## Code in This Repo  
```python
temp = float(input("Enter your temperature: "))  
unit = input("Is this in (C)elsius or (F)ahrenheit? ").strip().lower()  

if unit == "c":  
    converted = (temp * 9/5) + 32  
    print(f"{temp}°C is {converted}°F")  
elif unit == "f":  
    converted = (temp - 32) * 5/9  
    print(f"{temp}°F is {converted}°C")  
else:  
    print("Invalid input! Please enter C or F.")
