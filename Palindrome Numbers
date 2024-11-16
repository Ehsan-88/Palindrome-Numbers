def palindrome(number):
    str_number = str(number)  # Convert the number to a string
    reversed_str = str_number[::-1]  # Reverse the string
    return str_number == reversed_str  # Check if the original string is the same as the reversed one

while True:
    user_input = input("Type a number: ")
    if user_input.isdigit():
        number = int(user_input)
        
        if palindrome(number):  # Check if the number is a palindrome and print the result
            print(f"{number} is a palindrome.")
        else:
            print(f"{number} is not a palindrome.")  # Result if number is NOT a palindrome number
        break

input("Press Enter to exit...")
