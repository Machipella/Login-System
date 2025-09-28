# Login-System
Got bored and created this simple login system just to remind myself about elif statements 
print("User Secure Login System")
Username = input("Enter your username: ")
Password = input("Enter your password: ")
if Username == "admin" and Password == "admin123":
    print("Login successful!How are you today Driss")
    print("Welcome to the system.Have a great day!")
elif Username == "user" and Password == "user123":
    print("Login successful!How are you today user")
    print("Welcome to the system.Have a great day!")
    print("Don't forget to wear you're glasses.")
else:
    print("Login failed! Invalid username or password.")
    print("Please try again or contact support if you need assistance.")

