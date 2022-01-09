print("Enter your username and password")
count = 0

while count < 3:
    user = input("Enter username: ")
    password = input("Enter password: ")
    if user == "Victor" and password == "Pass123":
        print("Welcome to my awesome app")
        break
    else:
        print("Access denied. Try again.")
        count += 1
