# plp-python-week6
Python error handling Assignment
This assignment demonstrates how to use python error handling (try and except) to prevent program from crashing when errors occur.

#function explanation

Safe_divide: This function divides one number by another. if the second number is zero, it catches the ZeroDivisiovError and return "cannot divide by zero"
Safe_number: This function convert text into a whole number using int().If the texts contain invalid characters, such as "abc", it catches the ValueError and returns " Not a number"
Safe_get: This function searches for a specific key in a dictionary and return its value. If the key does not exist, it catches the keyError and returns "field not found"

An if statement can check conditions, but it cannot automatically catch errors that happen during number conversion. When Python tries to convert "abc" into an integer using int(), it raises a ValueError. We use try and except to handle this error safely.

File descriptions
Safe_tool.py: contain the three functions and test statement
README.md : contain the assignment title, projection descriptions, function explanations, and the explanations of error handling.
