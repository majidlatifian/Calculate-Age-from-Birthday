# Calculate Age from Birthday
This Python code calculates a person's age based on their birthday. It utilizes the **date** module from the **datetime** library to access the current date and perform the calculation.
## Code Explanation
1. The code begins by importing the date class from the datetime module.
2. The user is prompted to input their birthday in the format YYYY/MM/DD. The input value is stored as a list of strings using the split() method.
3. The code checks if the entered month (birthday[1]) is greater than 12 or the entered day (birthday[2]) is greater than 31. If either condition is true, it prints 'WRONG' to indicate an invalid date.
4. If the date is valid, the current date is retrieved using the today() method of the date class.
5. The person's age is calculated by subtracting their birth year (int(birthday[0])) from the current year and adjusting for cases where the birthday has not yet occurred in the current year ((today.month, today.day) < (int(birthday[1]), int(birthday[2]))).
6. The calculated age is printed.
## Usage
1. Run the code.
2. Enter your birthday in the format **YYYY/MM/DD**.
3. If the entered date is valid, the code will display your age. If the date is invalid (e.g., the month is greater than 12 or the day is greater than 31), it will print '**WRONG**'.

