# Bacic Calculater Code
 while True:
    print("Choose which operation you want from below:")
    print(" - multiply")
    print(" - divide")
    print(" - add")
    print(" - subtract")

    while True:
    print("Choose which operation you want from below:")
    print(" - multiply")
    print(" - divide")
    print(" - add")
    print(" - subtract")

    choice = input().lower()

    if choice in ['add', 'multiply', 'subtract', 'divide']:
        x = float(input("Enter your first number: "))
        y = float(input("Enter your second number: "))

        if choice == "add":
            print(f"The sum is: {x + y}")

        elif choice == "multiply":
            print(f"The product is: {x * y}")

        elif choice == "subtract":
            print(f"The difference is: {x - y}")

        elif choice == "divide":
            if y != 0:
                print(f"The quotient is: {x / y}")
            else:
                print("Error: Division by zero is not allowed.")
    else:
        print("Invalid choice. Please choose a valid operation.")

    continue_choice = input("Do you want to perform another operation? (yes/no): ").lower()
    if continue_choice != 'yes':
        break
        
#Improvements will be made 
