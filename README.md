"---------------------------------------------------------------------------------------------------------   
"---------------------------------------------------------------------------------------------------------      
"---------------------------------------------------------------------------------------------------------      

001 - 

Exercise Statement: Salary Bonus Calculator in SAP ABAP

You have been assigned to develop a SAP ABAP program to calculate salary bonuses based on specific criteria for a company. The program should interact with the user, prompting for the input of an employee's annual salary and the currency in which the salary is expressed.

The bonus should be calculated according to the following table:

Annual Salary < 50000: 5% Bonus
Annual Salary between 50000 and 100000: 10% Bonus
Annual Salary > 100000: 15% Bonus
Additionally, the program should validate user input, ensuring that the salary is a positive value. The provided currency should be checked to accept only 'USD', 'EUR', or 'GBP'.

The program should display the following information to the user:

Original Salary
Bonus Amount
New Salary (Original Salary + Bonus)
Provide informative messages in case of errors, indicating whether the provided salary is negative or if the currency is not supported.

Develop the program using available control flow structures and mathematical operators in ABAP. Use constants to represent fixed values and comment your code appropriately. Test the program with different salary and currency values to ensure the accuracy of calculations and the robustness of the implemented logic.

"---------------------------------------------------------------------------------------------------------   
"---------------------------------------------------------------------------------------------------------      
"---------------------------------------------------------------------------------------------------------      

002 - 

Exercise Statement: Enhanced Salary Bonus Calculator in SAP ABAP

You have been tasked with developing a SAP ABAP program to calculate salary bonuses, taking the challenge to include additional considerations. The program should interact with the user to obtain an employee's annual salary and the corresponding currency, with the bonus calculated based on the company's specific criteria:

Annual Salary < 50000: 5% Bonus
Annual Salary between 50000 and 100000: 10% Bonus
Annual Salary > 100000: 15% Bonus
However, the program now needs to include the following complexities:

Currency Conversion:

Users should be able to provide the salary in different currencies, including 'USD,' 'EUR,' and 'GBP.' The program should automatically convert the salary to the company's standard currency ('USD') before calculating the bonus.
Additional Validation:

In addition to ensuring that the salary is positive, the program must now validate whether the salary is below or above limits specified by the company. If the salary is outside these limits, an informative message should be displayed.
Bonus History:

The program should maintain a record of bonuses granted to employees. Each time a new bonus is calculated, the program should display the accumulated bonus history for the employee.
User Interface Enhancements:

Develop a more user-friendly interface, allowing users to choose the currency to be used and providing clear visual information about bonus calculation and accumulated history.
Ensure that the program is designed to handle unforeseen situations, such as unsupported currencies, extreme salary values, or invalid inputs. Utilize advanced control flow structures, string manipulation, and additional considerations to make the program robust and efficient. Test the program extensively with a variety of scenarios to ensure its functionality and accuracy.

"---------------------------------------------------------------------------------------------------------   
"---------------------------------------------------------------------------------------------------------      
"---------------------------------------------------------------------------------------------------------      
