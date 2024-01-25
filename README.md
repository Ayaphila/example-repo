# example-repo
# This function calculates the factorial of a given number
def factorial(n):
    result = 1  # Initialize the result variable to 1

    # Loop through numbers from 1 to n (inclusive)
    for i in range(1, n + 1):
        result *= i  # Multiply the current result by the current loop variable

    return result  # Return the final factorial result

# Example usage:
num = 5
result = factorial(num)
print(f"The factorial of {num} is {result}")
