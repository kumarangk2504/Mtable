# Mtable
This Python script generates a multiplication table for a given number.

multiplication_table(n): This function takes an integer n as input and generates the multiplication table for that number. It iterates from 1 to 10 and calculates the product of n with each number in the range. Each row of the table is represented as a list containing the multiplicand, multiplier, and product.

if __name__ == "__main__":: This block of code ensures that the following code is only executed if the script is run directly (not imported as a module).

num = int(input("Enter a number to generate its multiplication table: ")): This line prompts the user to enter a number for which they want to generate the multiplication table and converts the input to an integer.

table = multiplication_table(num): This line calls the multiplication_table function with the user-provided number and stores the resulting multiplication table in the variable table.

print(f"Multiplication table for {num}:"): This line prints a header indicating the number for which the multiplication table is generated.

for row in table:: This loop iterates over each row in the multiplication table and prints it.

When you run this script, it will ask you to enter a number, then it will generate and print the multiplication table for that number.





