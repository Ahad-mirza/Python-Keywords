```python
# Q1: Validate user login credentials using a username and password
name = input("Enter Username: ")
pass_input = int(input("Enter password for Login🔐: "))
password = 78047340

if pass_input == password:
    if name == "Ahad":
        print("Login Successful!🔓")
    else:
        print("Invalid credentials❌")
else:
    print("Invalid credentials❌")

# Q2: Suggest an activity or precaution based on the current temperature
temp = int(input("Enter the current temperature: "))

if temp >= 30:
    print("You need to stay hydrated.")
elif 20 < temp < 30:
    print("It's a nice day for a walk.")
else:
    print("Wear a jacket to keep warm.")

# Q3: Determine the tax rate based on annual income
income = int(input("Enter your annual income: "))

if income <= 50000:
    print("Your tax rate is 10%.")
elif 50000 < income <= 100000:
    print("Your tax rate is 20%.")
else:
    print("Your tax rate is 30%.")

# Q4: Identify if the input day is a weekend or a weekday
day = input("Enter day of the week: ").lower()

if day == "saturday" or day == "sunday":
    print("It's weekend.")
else:
    print("It's weekday.")

# Q5: Provide information about eligibility for a driving license based on age
age = int(input("Enter your age: "))

if age <= 16:
    print("You are too young to get a driving license.")
elif 16 < age <= 18:
    print("You need parental consent to get a driving license.")
else:
    print("You are eligible to get a driving license.")
```
