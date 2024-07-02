# My_Project_
Survival Duration Calculator Project

This project calculates the duration of a person's life in different time units based on their age. I defined a class SurvivalDurationCalculator that takes the age as input and has a method calculate_duration that calculates the duration in the chosen time unit.

I used a simple multiplication logic to calculate the duration in each time unit. For example, to calculate the duration in months, I multiplied the age by 12.

I tested the code with an age of 10 and it outputted the correct duration in months (120).

I hope this project meets the requirements.








Defining the class or method for calculating the survival duration ?

class SurvivalDurationCalculator:
    def __init__(self, age):
        self.age = age

    def calculate_duration(self, time_unit):
        # logic for calculating duration goes here
        pass

Defining the logic for calculating the duration in 6 units ?

class SurvivalDurationCalculator:
    def __init__(self, age):
        self.age = age

    def calculate_duration(self, time_unit):
        if time_unit == 'months' or time_unit == 'm':
            return self.age * 12
        elif time_unit == 'weeks' or time_unit == 'w':
            return self.age * 52
        elif time_unit == 'days' or time_unit == 'd':
            return self.age * 365
        elif time_unit == 'hours' or time_unit == 'h':
            return self.age * 8760
        elif time_unit == 'minutes' or time_unit == 'min':
            return self.age * 525600
        elif time_unit == 'seconds' or time_unit == 's':
            return self.age * 31536000
        else:
            return "Invalid time unit"

 Successful execution of the app without any errors, and giving the output ?

calculator = SurvivalDurationCalculator(10)
print(calculator.calculate_duration('months'))  # Output: 120




