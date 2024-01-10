def login():
    username = input("Enter username: ")
    password = input("Enter password: ")

    if username == "Raam" and password == "0963@op":
        print("Login successful!")
        print("Redirecting to Telegram ID: @RAM_0P")
        # Add your code to navigate to your Telegram ID here
    else:
        print("Invalid username or password. Access denied.")

# Example usage
login()
