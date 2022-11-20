# HelpForSeniors_App
This is the HelpForSeniors_App I used making python.

print("Hello! Welcome to the HelpForSeniors App Verson 1.0")

name = input("Enter your name: ")

print("Hello " + name)

age = int(input("Now, enter your age: "))

if age != int(age):
    print("Error")

if age < 55:
    print("HelpForSeniors is only for senior citizens (55+).")

else:
    print("Welcome to HelpForSeniors")
    print("What type of help do you need?")
    print("1. Snow Cleaning")
    print("2. Yardwork/Lawn Mowing")
    print("3. Running Errands")
    print("4. House Cleaning")
    print("5. Cooking")
    print("6. Lifting/Carrying Boxes/Packages")
    print("7. Technology Help")

print()

answer = int(input("Enter a number 1-7: "))

while answer > 7:
    answer = int(input("Enter a number 1-7: "))

if answer == 1:
    print("Searching for Snow Cleaning volunteers...")

    import time

    time.sleep(3)

    print("YOUR VOLUNTEER")

    print()

    import random

    volunteer = random.randint(1, 5)

    if volunteer == 1:
        print("Jack Jackman")
        print("DESCRIPTION: Hi, my name is Jack and I love to help my community. I am ready to shovel your snow!")

    if volunteer == 2:
        print("Malisa Sylvester")
        print("DESCRIPTION: Hello! My name is Malisa and I will can help you shovel your snow!")
    if volunteer == 3:
        print("Laura Stewart")
        print("DESCRIPTION: My name is Laura Stewart, I am a college student and would be happy to shovel snow for you!")

    if volunteer == 4:
        print("Levi Lynch")
        print("DESCRIPTION: Hello, I am ready to shovel some snow.")

    if volunteer == 5:
        print("Priya Joshi")
        print("Hello there! I can help you shovel snow.")

    print()

    address = input("Enter your address for the volunteer: ")

    date = input("Enter date you want help on: ")

    print("AVAILABLE TIMES")
    print("1. 10:00am")
    print("2. 11:30am")
    print("3. 2:00pm")
    print("4. 3:00pm")
    print("5. 4:30pm")
    print("6. 7:00pm")

    time = int(input("Enter number 1-6. If none of these times work for you, type 0. "))

    while time > 6:
        time = int(input("Enter number 1-6. If none of these times work for you, type 0. "))

    if time == 0:
        print("Thank you for your interest in HelpForSeniors")
        exit()

    print()

    request = input("Type request to send a help request to the volunteer. ")

    while request != "request":
        request = input("Please type request to send a help request to the volunteer. ")

    import time

    if request == "request":
        print("Sending request...")
        time.sleep(2)

        print("Request successfully sent!")



if answer == 2:
    print("Searching for Yardwork/Lawn Mowing volunteers...")

    import time

    time.sleep(3)

    print("YOUR VOLUNTEER")

    print()

    import random

    volunteer = random.randint(1, 5)

    if volunteer == 1:
        print("Malinda Lavish")
        print("DESCRIPTION: Hi, I would love to help you with yardwork and lawn mowing!")

    if volunteer == 2:
        print("Trevor McMartin")
        print("DESCRIPTION: Hello! My name is Trevor. I am very experienced in lawn mowing and I would be happy to help!")

    if volunteer == 3:
        print("Boris Vitas")
        print("DESCRIPTION: My name is Boris, call me if you need any yardwork done.")

    if volunteer == 4:
        print("Demarcus Morant")
        print("DESCRIPTION: Hi, I am Demarcus. I love helping people so give me a call!")

    if volunteer == 5:
        print("Lara Cyvekia")
        print("DESCRIPTION: Hi, I am a hardworking parent ready to help!")

    print()

    address = input("Enter your address for the volunteer: ")

    date = input("Enter date you want help on: ")

    print("AVAILABLE TIMES")
    print("1. 10:00am")
    print("2. 11:30am")
    print("3. 2:00pm")
    print("4. 3:00pm")
    print("5. 4:30pm")
    print("6. 7:00pm")

    time = int(input("Enter number 1-6. If none of these times work for you, type 0. "))

    while time > 6:
        time = int(input("Enter number 1-6. If none of these times work for you, type 0. "))

    if time == 0:
        print("Thank you for your interest in HelpForSeniors")
        exit()

    print()

    import time

    request = input("Type request to send a help request to the volunteer. ")

    while request != "request":
        request = input("Please type request to send a help request to the volunteer. ")

    if request == "request":
        print("Sending request...")
        time.sleep(2)

        print("Request successfully sent!")


if answer == 3:
    print("Searching for Running Errands volunteers...")

    import time

    time.sleep(3)

    print("YOUR VOLUNTEER")

    print()

    import random

    volunteer = random.randint(1, 5)

    if volunteer == 1:
        print("Sarah Yasmine")
        print("DESCRIPTION: Hi! I can help you with many errands like grocery shopping and laundry.")

    if volunteer == 2:
        print("JuJu John-Jason")
        print("DESCRIPTION: My name is JuJu, I'm a college student, and I'm ready to help you!")

    if volunteer == 3:
        print("Itti Annamalai")
        print("DESCRIPTION: Hello, my name is Itti. I would love to help you run some errands.")

    if volunteer == 4:
        print("Kiki Leary")
        print("DESCRIPTION: Hi, as someone with a grandpa in his 90's, I love helping senior citizens!")

    if volunteer == 5:
        print("Bon Marson")
        print("DESCRIPTION: Hello, Bon Marson is here to help!")

    print()

    address = input("Enter your address for the volunteer: ")

    date = input("Enter date you want help on: ")

    print("AVAILABLE TIMES")
    print("1. 10:00am")
    print("2. 11:30am")
    print("3. 2:00pm")
    print("4. 3:00pm")
    print("5. 4:30pm")
    print("6. 7:00pm")

    time = int(input("Enter number 1-6. If none of these times work for you, type 0. "))

    while time > 6:
        time = int(input("Enter number 1-6. If none of these times work for you, type 0. "))

    if time == 0:
        print("Thank you for your interest in HelpForSeniors")
        exit()

    print()

    import time

    request = input("Type request to send a help request to the volunteer. ")

    while request != "request":
        request = input("Please type request to send a help request to the volunteer. ")

    if request == "request":
        print("Sending request...")
        time.sleep(2)

        print("Request successfully sent!")



if answer == 4:
    print("Searching for House Cleaning volunteers...")

    import time

    time.sleep(3)

    print("YOUR VOLUNTEER")

    print()

    import random

    volunteer = random.randint(1, 5)

    if volunteer == 1:
        print("Leo Tran")
        print("DESCRIPTION: Hi, my name is Leo and I am great at cleaning houses!")

    if volunteer == 2:
        print("Travis Georgio")
        print("DESCRIPTION: The name's Travis. I would love to clean your house.")

    if volunteer == 3:
        print("Changle Chan")
        print("DESCRIPTION: My name is Changle Chan. I can help clean your house.")

    if volunteer == 4:
        print("Lela")
        print("DESCRIPTION: Hello, I have helped several people clean their house, and I would love to help you as well!")

    if volunteer == 5:
        print("John Pierre")
        print("DESCRIPTION: Bonjour! I am from France. I would be happy to clean your house for you.")

    print()

    address = input("Enter your address for the volunteer: ")

    date = input("Enter date you want help on: ")

    print("AVAILABLE TIMES")
    print("1. 10:00am")
    print("2. 11:30am")
    print("3. 2:00pm")
    print("4. 3:00pm")
    print("5. 4:30pm")
    print("6. 7:00pm")

    time = int(input("Enter number 1-6. If none of these times work for you, type 0. "))

    while time > 6:
        time = int(input("Enter number 1-6. If none of these times work for you, type 0. "))

    if time == 0:
        print("Thank you for your interest in HelpForSeniors")
        exit()

    print()

    import time

    request = input("Type request to send a help request to the volunteer. ")

    while request != "request":
        request = input("Please type request to send a help request to the volunteer. ")

    if request == "request":
        print("Sending request...")
        time.sleep(2)

        print("Request successfully sent!")


if answer == 5:
    print("Searching for Cooking volunteers...")

    import time

    time.sleep(3)

    print("YOUR VOLUNTEER")

    print()

    import random

    volunteer = random.randint(1, 5)

    if volunteer == 1:
        print("Marcus Mann")
        print("DESCRIPTION: Hello there! I am a great chef and many have been satisfied with my cooking.")

    if volunteer == 2:
        print("Arjun Vijay")
        print("DESCRIPTION: Hello! I am very good at cooking, especially cooking Indian food!")

    if volunteer == 3:
        print("Charris Yana")
        print("DESCRIPTION: My name is Charris and it would be absolutely wonderful to help with cooking!")

    if volunteer == 4:
        print("K. Osborne")
        print("DESCRIPTION: Hi, I am an amazing chef!")

    if volunteer == 5:
        print("KJ Tupper")
        print("DESCRIPTION: Cooking and giving back to the community are passions of mine. So putting them together is amazing.")

    print()

    address = input("Enter your address for the volunteer: ")

    date = input("Enter date you want help on: ")

    print("AVAILABLE TIMES")
    print("1. 10:00am")
    print("2. 11:30am")
    print("3. 2:00pm")
    print("4. 3:00pm")
    print("5. 4:30pm")
    print("6. 7:00pm")

    time = int(input("Enter number 1-6. If none of these times work for you, type 0. "))

    while time > 6:
        time = int(input("Enter number 1-6. If none of these times work for you, type 0. "))

    if time == 0:
        print("Thank you for your interest in HelpForSeniors")
        exit()

    print()

    import time

    request = input("Type request to send a help request to the volunteer. ")

    while request != "request":
        request = input("Please type request to send a help request to the volunteer. ")

    if request == "request":
        print("Sending request...")
        time.sleep(2)

        print("Request successfully sent!")


if answer == 6:
    print("Searching for Lifting/Carrying Boxes/Packages volunteers...")

    import time

    time.sleep(3)

    print("YOUR VOLUNTEER")

    print()

    import random

    volunteer = random.randint(1, 5)

    if volunteer == 1:
        print("Aaron Rambuff")
        print("DESCRIPTION: I am a part-time bodybuilder and can lift packages of any size.")

    if volunteer == 2:
        print("Lilah Abramson")
        print("DESCRIPTION: My name is Lilah and I can help you lift some boxes!")

    if volunteer == 3:
        print("Perogi Wilson")
        print("DESCRIPTION: My name is Perogi. I am great at lifting heavy boxes.")

    if volunteer == 4:
        print("Russell Rolle")
        print("DESCRIPTION: Hi, I am a college student and can lift boxes for you.")

    if volunteer == 5:
        print("Chandler Chapp")
        print("DESCRIPTION: I would love to help you lift packages.")

    print()

    address = input("Enter your address for the volunteer: ")

    date = input("Enter date you want help on: ")

    print("AVAILABLE TIMES")
    print("1. 10:00am")
    print("2. 11:30am")
    print("3. 2:00pm")
    print("4. 3:00pm")
    print("5. 4:30pm")
    print("6. 7:00pm")

    time = int(input("Enter number 1-6. If none of these times work for you, type 0. "))

    while time > 6:
        time = int(input("Enter number 1-6. If none of these times work for you, type 0. "))

    if time == 0:
        print("Thank you for your interest in HelpForSeniors")
        exit()

    print()

    import time

    request = input("Type request to send a help request to the volunteer. ")

    while request != "request":
        request = input("Please type request to send a help request to the volunteer. ")

    if request == "request":
        print("Sending request...")
        time.sleep(2)

        print("Request successfully sent!")


if answer == 7:
    print("Searching for Technology Help volunteers...")

    import time

    time.sleep(3)

    print("YOUR VOLUNTEER")

    print()

    import random

    volunteer = random.randint(1, 5)

    if volunteer == 1:
        print("Scott Lee")
        print("DESCRIPTION: I am a computer scientist and I know a lot about technology :).")

    if volunteer == 2:
        print("Lily Lawrence")
        print("DESCRIPTION: Hi! I am studying computer science right now and I would love to help you with tech issues your having.")

    if volunteer == 3:
        print("Asa Sivakumar")
        print("DESCRIPTION: Hello my name is Asa. As a data scientist at Amazon, I know a lot about technology.")

    if volunteer == 4:
        print("Harris Ginger")
        print("DESCRIPTION: Hi, I am a high schooler and would love to help you with your technology.")

    if volunteer == 5:
        print("Riley Mostart")
        print("DESCRIPTION: A computer science major ready to help you!")

    print()

    address = input("Enter your address for the volunteer: ")

    date = input("Enter date you want help on: ")

    print("AVAILABLE TIMES")
    print("1. 10:00am")
    print("2. 11:30am")
    print("3. 2:00pm")
    print("4. 3:00pm")
    print("5. 4:30pm")
    print("6. 7:00pm")

    time = int(input("Enter number 1-6. If none of these times work for you, type 0. "))

    while time > 6:
        time = int(input("Enter number 1-6. If none of these times work for you, type 0. "))

    if time == 0:
        print("Thank you for your interest in HelpForSeniors")
        exit()

    print()

    import time

    request = input("Type request to send a help request to the volunteer. ")

    while request != "request":
        request = input("Please type request to send a help request to the volunteer. ")

    if request == "request":
        print("Sending request...")
        time.sleep(2)

        print("Request successfully sent!")



