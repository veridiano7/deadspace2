print("Presentor: GLEN VERIDIANO")
print("Section: ACT-1B")

print("*" * 100)
print("======== FUNDAMENTALS OF PROGRAMMING ======== ")
print("=" * 100)
print("")
input("Welcome to presentation, Enter yes to procede: ")
print("")
print("The OPTION below are the lesson you can tackle !")
print("and each semister has a different topic\n")

print("==========================================")
print("-----------SEMISTER OPTION----------------")
print("==========================================")
print("[1] PRELIM")
print("[2] MIDTERM")
print("[3] FINALS")
print("")

semister = input("Choose from the semister you want to tackle (1-2-3): ")


#PRELIM
if semister == "1":

    print()
    print("==========================================")
    print("                  PRELIM")
    print("==========================================")
    print("[1] Chapter 1 - Introduction to Programming")
    print("[2] Chapter 2 - Python Basic Syntax")
    print("[3] Chapter 3 - Arithmetic Operators and Expressions")
    print("[4] Chapter 4 - Basic Input and Output\n")
    

    topic = input("Choose a chapter: ")

# CHAPTER == 1
    if topic == "1":

        print("------------------------------------------")
        print("CHAPTER 1 - INTRODUCTION TO PROGRAMMING")
        print("------------------------------------------\n")
        print("A programming language is a special languange that")
        print("computer understand and use to perform.\n")
        
        print("Python is a widely used programming language that was ")
        print("created by Guido van Rossum in 1991.\n")

        print("=" * 100)

        print("Example:")
        print('print("Hello, World!")\n')
        print("Output:\n")
        print("Hello, World!\n")
        print("ACTIVITY:")
        print("Create a simple program that displays your name.\n")

        student_name = input("Enter your name: ")
        print("Hello,", student_name + "!")

# CHAPTER == 2
    elif topic == "2":

        print("------------------------------------------")
        print("CHAPTER 2 - PYTHON BASIC SYNTAX")
        print("------------------------------------------\n")

        print("Chapter 2 has 4 parts\n")

        print("1. PRINT FUNCTION")
        print("The print() display information on the screen.\n")

        print('Example: print("Hello")')
        print("Output: Hello\n")
        
        print("Incorrect example:")
        print('print("Hello)')
        print("The given example above is wrong bacause of grammar")
        print("and the text is also known as STRING.\n")

        print("The numbers can be print directly w/o quotation")
        print("Example: print(100)")
        print("Example: print(150)")
        print("Example: print(82)\n")

        print("2. COMMENTS")
        print("Comments are IGNORED by python.")
        print("The # symbol is used for comments.\n")
        
        print("Example:")
        print("# This is a comment")
        print('#print("Welcome to Python")\n')

        print("3. VARIABLES")
        print("Variables is a named STORAGE LOCATION.")
        print("used to keep data in a program.\n")

        print("Example: ")
        print('a = "I"')
        print('b = "Love"')
        print('c = "CCST"')
        print("print(a, b, c)")
        print("Output: I Love CCST\n")

        print("Another Example: ")
        print('shool = "Clark College"')
        print('Output: Clark College\n')


        print("4. DATA TYPES")
        print("These are the categories that tell python")
        print("what kind of data a variable store\n")

        print("int   - Integers Whole numbers")
        print("float - Decimal numbers")
        print("str   - Text or characters or words")
        print("bool  - for True or False\n")
    
        print('name = "Bruce"')
        print("age = 20")
        print("grade = 89.0")
        print("is_enrolled = True")
        print("The data used is STR, FLOAT, INT, and BOOL\n")

        print("ACTIVITY:")
        full_name = input("Enter your full name: ")
        age = input("Enter your age: ")
        subject = input("Enter your favorite subject: \n")

        print("STUDENT INFORMATION")
        print("Name:", full_name)
        print("Age:", age)
        print("Favorite Subject:", subject)

# CHAPTER == 3
    elif topic == "3":

        print("------------------------------------------")
        print("CHAPTER 3 - ARITHMETIC OPERATORS AND EXPRESSIONS")
        print("------------------------------------------\n")

        print("Arithmetic operators are symbol used to perform mathematical.")
        print("calculations on numbers\n")

        print("Addition       (+)")
        print("Subtraction    (-)")
        print("Multiplication (*)")
        print("Division       (/)")
        print("Exponentiation (**)")
        print("Floor Division (//)")
        print("Modulo         (%)\n")

        a = 5
        b = 10

        print("Example values: a = 5 and b = 10")
        print("Addition:", a + b)
        print("Subtraction:", a - b)
        print("Multiplication:", a * b)
        print("Division:", a / b)
        print("Exponentiation:", a ** 2)
        print("Floor Division:", a // b)
        print("Modulo:", a % b)
        print()

        print("one more thing (PEMDAS)")
        print("P - Parentheses")
        print("E - Exponents")
        print("MD - Multiplication and Division")
        print("AS - Addition and Subtraction\n")

        print("Example expression:")
        print("(10 + 10) * 2 ** 2 / 4 - 5")
        result = (10 + 10) * 2 ** 2 / 4 - 5
        print("Answer:", result)
        print()
        print("ACTIVITY:")
        first_number = float(input("Enter the first number: "))
        second_number = float(input("Enter the second number: "))

        print("Addition:", first_number + second_number)
        print("Subtraction:", first_number - second_number)
        print("Multiplication:", first_number * second_number)

        if second_number != 0:
            print("Division:", first_number / second_number)
        else:
            print("Division is not possible because the second number is zero.")

# CHAPTER == 4
    elif topic == "4":

        print("------------------------------------------")
        print("CHAPTER 4 - BASIC INPUT AND OUTPUT")
        print("------------------------------------------\n")

        print("The input() function is to accepts information from the user.")
        print("The print() function displays information.\n")
        
        print("Example:")
        print('name = input("Enter your name: ")')
        print('print("Hello", name)\n')

        print("ACTIVITY 1 - PERSONAL INFORMATION")
        person_name = input("Enter your name: ")
        person_age = input("Enter your age: ")
        address = input("Enter your address:\n ")

        print("YOUR INFORMATION")
        print("Name:", person_name)
        print("Age:", person_age)
        print("Address:", address)
        print()

        print("ACTIVITY 2 - BODY MASS INDEX (BMI)")
        bmi_name = input("Enter your name: ")
        weight = float(input("Enter your weight in kilograms: "))
        height = float(input("Enter your height in meters: "))

        if height > 0:
            bmi = weight / (height ** 2)
            print()
            print("BMI RESULT")
            print("Name:", bmi_name)
            print("Weight:", weight, "kg")
            print("Height:", height, "m")
            print("Your BMI is:", round(bmi, 2))
        else:
            print("Height must be greater than zero.")

    else:
        print("Invalid chapter selection.")


# for MIDTERM section
elif semister == "2":

    print()
    print("==========================================")
    print("                  MIDTERM")
    print("==========================================")
    print("[1] Relational Operators")
    print("[2] The if Statement")
    print("[3] The if-else Statement")
    print("[4] The if-elif-else Statement")
    print("[5] Nested Conditions")
    print("[6] Logical Operations\n")
    

    topic = input("Choose a topic: ")

#TOPIC == 1
    if topic == "1":

        print("------------------------------------------")
        print("1. RELATIONAL OPERATORS")
        print("------------------------------------------\n")
        print("Also called as Comparison operators.")
        print("are used to compare two values.\n")
        
        print("==  Equal to")
        print("!=  Not equal to")
        print(">   Greater than")
        print("<   Less than")
        print(">=  Greater than or equal to")
        print("<=  Less than or equal to\n")

        a = 10
        b = 5

        print("Example: a = 10 and b = 5")
        print("a == b:", a == b)
        print("a != b:", a != b)
        print("a > b:", a > b)
        print("a < b:", a < b)
        print("a >= b:", a >= b)
        print("a <= b:", a <= b)
        print()

        print("ACTIVITY:")
        number1 = float(input("Enter the first number: "))
        number2 = float(input("Enter the second number: "))

        print("Equal:", number1 == number2)
        print("Not equal:", number1 != number2)
        print("Greater than:", number1 > number2)
        print("Less than:", number1 < number2)

# TOPIC == 2 
    elif topic == "2":

        print("------------------------------------------")
        print("2. THE IF STATEMENT")
        print("------------------------------------------\n")
        print("The if statement executes a block of code only")
        print("when codition are true.\n")
    
        print("Example:")
        print("age = 18")
        print("if age >= 18:")
        print('    print("You are an adult.")\n')

        age = int(input("Enter your age: "))

        if age >= 18:
            print("You are an adult.")

        print("Program finished.")

# TOPIC == 3
    elif topic == "3":

        print("------------------------------------------")
        print("3. THE IF-ELSE STATEMENT")
        print("------------------------------------------\n")
        print("The else statement provide an alternative.")
        print("when the if condition are false.\n")

        print("Example:")
        print("number = 7")
        print("if number == 7:")
        print('    print("Correct!")')
        print("else:")
        print('    print("Incorrect!")\n')

        number = int(input("Guess the secret number: "))

        if number == 7:
            print("Congratulations! Your answer is correct.")
        else:
            print("Incorrect! The secret number is 7.")

# TOPIC == 4
    elif topic == "4":

        print("------------------------------------------")
        print("4. THE IF-ELIF-ELSE STATEMENT")
        print("------------------------------------------\n")
        print("The elif statement is used when there multiple")
        print("conditions to evaluate\n")

        print("Example:")
        print("score = 75")
        print("if score >= 90:")
        print('    print("Excellent!")')
        print("elif score >= 75:")
        print('    print("Congratulations! You passed!")')
        print("else:")
        print('    print("You failed.")\n')


        score = float(input("Enter your score: "))

        if score >= 90:
            print("Excellent! You passed.")
        elif score >= 75:
            print("Congratulations! You passed.")
        else:
            print("You failed.")

# TOPIC == 5
    elif topic == "5":

        print("------------------------------------------")
        print("5. NESTED CONDITIONS")
        print("------------------------------------------\n")
        print("Nested conditions is a condition inside a condition\n")
        
        print("Example:")
        print("age = 20")
        print("has_id = True")
        print()
        print("if age >= 18:")
        print("    if has_id:")
        print('        print("You may enter.")')
        print("    else:")
        print('        print("You need an ID.")')
        print("else:")
        print('    print("You are too young.")\n')

        age = int(input("Enter your age: "))
        has_id = input("Do you have an ID? (yes/no): ")

        if age >= 18:
            if has_id.lower() == "yes":
                print("You may enter.")
            else:
                print("You need an ID.")
        else:
            print("You are too young.")

# TOPIC == 6
    elif topic == "6":

        print("------------------------------------------")
        print("6. LOGICAL OPERATIONS")
        print("------------------------------------------\n")
        print("Logical operators are used to combine or reverse conditions.\n")
        
        print("AND - True only when BOTH conditions are True.")
        print("OR  - True when AT LEAST ONE condition is True.")
        print("NOT - Reverses the truth value.\n")
        

        print("AND OPERATOR TRUTH TABLE")
        print("A       B       A and B")
        print("True    True    True")
        print("True    False   False")
        print("False   True    False")
        print("False   False   False\n")

        print("OR OPERATOR TRUTH TABLE")
        print("A       B       A or B")
        print("True    True    True")
        print("True    False   True")
        print("False   True    True")
        print("False   False   False\n")

        print("NOT OPERATOR TRUTH TABLE")
        print("A       not A")
        print("True    False")
        print("False   True")
        print()

        print("PYTHON EXAMPLE:")
        print("age = 20")
        print("has_id = True")
        print("banned = False\n")

        print("print(age >= 18 and has_id)")
        print("print(age >= 18 or has_id)")
        print("print(not banned)\n")

        age = int(input("Enter your age: "))
        has_id = input("Do you have an ID? (yes/no): ").lower() == "yes"

        print("AND result:", age >= 18 and has_id)
        print("OR result:", age >= 18 or has_id)
        print("NOT result:", not has_id)

    else:
        print("Invalid topic selection.")

# FINALe
elif semister == "3":

    print()
    print("==========================================")
    print("-----------------FINALS-------------------")
    print("==========================================\n")
    print("[1] Iteration")
    print("[2] Loop and While Loop\n")
    topic = input("Choose a topic: ")

# TOPIC == 1
    if topic == "1":

        print("==========================================")
        print("1. ITERATION")
        print("------------------------------------------\n")
        print("Iteration means repeating a process")
        print("means repeatedly executing a set of instruction.\n")
        print("and it allows a programm to perform the")
        print("same task.\n")

        print("EXAMPLE USING A LOOP:\n")
        print("for number in range(1, 6):")
        print('print("Number:", number)\n')
        print("OUTPUT:")

        for number in range(1, 6):
            print("Number:", number)

        print()
        print("ACTIVITY:")
        limit = int(input("Enter a number: "))

        print("Counting from 1 to", limit)

        for count in range(1, limit + 1):
            print(count)

# TOPIC == 2
    elif topic == "2":

        print("------------------------------------------")
        print("2. LOOP AND WHILE LOOP")
        print("------------------------------------------\n")
        print("for LOOP Repeats instruction for each items in sequence.")
        print("and WHILE LOOP repeats if condiiton is True\n")
        print("EXAMPLE:")
        print("count = 1\\n")
        print("while count <= 5:")
        print('    print("Count:", count)')
        print("    count = count + 1\n")
        print("OUTPUT:")

        count = 1

        while count <= 5:
            print("Count:", count)
            count = count + 1

        print("")
        print("ACTIVITY:")
        limit = int(input("Enter a positive number: "))

        if limit > 0:
            count = 1

            while count <= limit:
                print("Iteration:", count)
                count = count + 1
        else:
            print("Please enter a number greater than zero.")

    else:
        print("Invalid topic selection.")

else:
    print("Invalid semister selection.\n")

print("==========================================")
print("---------------THANK YOU------------------")
print("==========================================")
