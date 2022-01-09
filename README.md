print("Enter your username and password")
count = 0

users = [
        {
         "username": "Victor",
         "password": "pass123"
         },

        {
         "username": "Vee",
         "password": "password123"
        },

        {
         "username": "Vice",
         "password": "vice123"
        }
    ]

while count < 3:
    enter_user = (input("Enter username: "))
    enter_pass = (input("Enter password: "))

    if enter_user and enter_pass in users:
        print("Welcome to my awesome app")
        break
    else:
        print("Access denied. Try again.")
        count += 1
