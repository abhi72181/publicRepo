# Introduction to Python & Variables, Data Types

### Student Activity [10 min]: Word Search Puzzle

  Search Top IT Companies.

![searchPuzzle.png](searchPuzzle.png)

![Screenshot (281).png](Screenshot_(281).png)

## What is Python?

![Screenshot (282).png](Screenshot_(282).png)

- Python is an **interpreted**, **object-oriented**, **high-level** programming language with dynamic semantics.
- It was created by **Guido van Rossum** and released in **1991** at **CWI [Centrum Wiskunde and Informatica] Research Center, Netherlands**.

- It is a general-purpose language, meaning **it can be used to create a variety of different programs and isn't specialized for any specific problems.**

## Why the name Python?

- **Guido van Rossum** was reading the script of a popular BBC comedy series "**Monty Python's Flying Circus**". It was late on-air 1970s.
- Van Rossum wanted to select a name that said unique, sort, and mysterious. So, he decided to select naming **Python** after **"Monty Python's Flying Circus"** for their newly created programming language.
- The comedy series was **creative** and **well random**. It talks about everything. Thus, it is slow and unpredictable, which made it very interesting.

## Why Python?

- **Simple and Easy to Learn**
- **Dynamic**
- **Platform Independent**
- **Free and Open Source**
- **Interpreted (bytecode-compiled)**
- **Rich Library Support (more than 1,37,000 third-party python libraries)**
- **Embeddable and Extensible**
- **Portable**
- **Robust**
- **Exception Handling**

![Untitled](Untitled.png)

## [Instructor task: 5min] Discuss Indentation

discuss briefly with examples.

## Setup Replit[2-3 min]

- Go to [https://replit.com](https://replit.com/)
- Sign up with your Gmail account.
- Choose **Python** and it will open a window asking you to create a repl.
- Press create repl.
- A new window will open, On the **left side**, you will find the **code editor** and on the **right side** is the **terminal** where we can see our **output**.

![35 Best Funny Python Programming Memes _ CodeItBro (1).jpg](35_Best_Funny_Python_Programming_Memes___CodeItBro_(1).jpg)

## How to print or get output in Python?

### ***print( )***➖

The `print()` function prints the specified message to the screen or other standard output device.

The message can be **a string** or **any other object**, the object will be converted into a string before being written to the screen.

![Untitled](Untitled%201.png)

## **Python Comments**

- Comments can be used to explain Python code.
- They make the code more readable.
- They prevent execution when testing code.
- Comments are of two types:

## Variables

Variables are containers for storing data values.

### Creating Variables

Python has no command for declaring a variable.

A variable is created when you first assign a value to it.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/ff94b4dd-cb13-4ede-8019-d6a8215bf3d5/acaefdc0-a98e-4215-a7df-bbb9ba091bbe/Untitled.png)

### Instructor Task (3 mins): Show how we can print variables and values, 
Show live demo on Replit

- To know what is present inside the box, we need to use **print()**.

### Get the Type

You can get the data type of a variable with the `type()` function.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/ff94b4dd-cb13-4ede-8019-d6a8215bf3d5/b88979d3-5a39-4311-b85d-6327204bdad3/Untitled.png)

### Student Task (5 mins): Print some values and variables.

### Student Activity (ice breaker) [10 min]:  Showing you some images, give the English names of those.         [Link](https://recipes.timesofindia.com/articles/features/20-common-household-utensils-and-their-english-names/photostory/64015979.cms?picid=64016014)

## Variables

### Instructor Task (10 mins): Talk about variables

- Let's try to understand with a story
    - There was a child who once decided to leave his home and move to a different place. He does his packing.
    - There was a lot of stuff that needs to be packed. So, What he did, He arrange some boxes and In each box, he used to put some set of things For ex: Pictures, Shoes, Shirts, pillows, books, toys, etc.
        
        
        ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/ff94b4dd-cb13-4ede-8019-d6a8215bf3d5/6397ee92-4a9a-4c96-8051-bdea477896e2/Untitled.png)
        

- For Identification, He marked each box with a name Like a box containing pictures has the name pictures, the box which contains books marked as books, etc.
- We relate this story to the concept of variables,
    - The boxes are considered as variables where you can put your set of things.
    
    ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/ff94b4dd-cb13-4ede-8019-d6a8215bf3d5/63a491b4-1826-4001-840a-a05f66bbe955/Untitled.png)
    
    - It is used to ***hold data*** that you can choose later.
    - The variable is ***storage locations with assigned names***.

## Need of Variable

### Instructor Task (3 mins): Talk about why we need it and how is it used in real life.

- Different customers who log in to Amazon, Flipkart, or Facebook should see their name on the top, not a fixed name.
- The variable *"custName"* can be used to store the customer's name.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/ff94b4dd-cb13-4ede-8019-d6a8215bf3d5/cbfe7de9-6779-4764-a593-5f5342c457b4/Untitled.png)

- It is like a box holding different values depending on who is visiting and logged in to the website.
- In the front end, Using Forms we use to take the values for different variables like Facebook signup forms carrying different variables like name, age, etc.

## Rules for Declaring Variables

- A variable name must start with a letter or underscore character ( _ ).
- A variable name cannot start with a number.
- A variable name can only contain alphanumeric letters ( A-Z, a-z, 0-9 ) and an underscore ( _ ).
- Variable names are case-sensitive. (age ≠ Age ≠ AGE)

## **Multi Words Variable Names**

Variable names with more than one word are difficult to read.

**Various ways by which you can use to make them more readable**:

- **Camel Case**➖ Each word, except the first, starts with a capital letter.
    
          Examples➖ myCar, firstPriceValue, etc.
    
- **Pascal Case**➖ Each word starts with a capital letter:
    
          Examples➖ MyCar, FirstPriceValue, etc.
    
- **Snake Case**➖ Each word is separated by an underscore character.
    
          Examples➖ my_car , first_price_value, etc.
    

### Instructor Task (2 mins): Introduce Data types

Apart from the customer's name,  a website may also need to know the customer's age. This would be another variable "*custAge".*

While *custAge is* also a variable but it holds a number, not a word (called a *string* in Python). Variables can have different "data types".

## Datatype

### Instructor Task (10 mins): Talk about different Data types

![Screenshot (293).png](https://prod-files-secure.s3.us-west-2.amazonaws.com/ff94b4dd-cb13-4ede-8019-d6a8215bf3d5/7892a1bc-94bc-42a8-a2b3-f9c934ebcc97/Screenshot_(293).png)

As we discussed earlier, **variables are like boxes/containers**. 

Above are three containers - What type of things will we store in the pencil holder? What type of things will we store in a water bottle? 

Can you store milk in a basket or can you use a bottle to store fruits?

We are using different types of containers to store different things. 

While the bottle can hold milk or water or juice, it will hold only liquids. 

Similarly, 

- A variable of type ***string*** (like the variable - *custName*), can store only strings.
- A variable of type **int** (like the variable - *custAge)* can store only integers.
- A variable of type **boolean** (like the variable - *custMaritalStatus)* can store either true or false.
- A variable of type **float** (like the variable - fruitWeight*)* can store only decimal values.

*The type of data a variable can hold is called its* **Data type**. It may be **int**, **string, boolean, float,** etc. (A variable of type Boolean can either be *True* or *False).*

## Int

![Screenshot (295).png](https://prod-files-secure.s3.us-west-2.amazonaws.com/ff94b4dd-cb13-4ede-8019-d6a8215bf3d5/a578f750-da4e-4993-9603-e0ab64d65dab/Screenshot_(295).png)

![Screenshot (294).png](https://prod-files-secure.s3.us-west-2.amazonaws.com/ff94b4dd-cb13-4ede-8019-d6a8215bf3d5/6ac4836a-a84c-4308-8f8b-00f8f5b78a08/Screenshot_(294).png)

## **String**

![String.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/ff94b4dd-cb13-4ede-8019-d6a8215bf3d5/55dc7241-4066-4d0e-9333-d9b0c8f402ab/String.png)

![str2.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/ff94b4dd-cb13-4ede-8019-d6a8215bf3d5/30e0cacc-18d2-4d9a-8452-10f5d7677811/str2.png)

### Student Task: Can they think of any other example like the car number plate, where a sequence of numbers is not important for their value?

One common example could be the Aadhaar card number. It is full of numbers but their “numerical value” is not how its used. We don’t say my Aadhaar number is "5 billion, 350 million …." We say it’s "5350…".

*var aadhaarNum = “535067543542”;*

vs

*var aadhaarNum = 535067543542;*

## Boolean

This datatype has only two values i.e. **True and False;**

- Some Questions are only answered in True or False :
    - For Ex :
        - Whether Student is Pass or Fail: Either True or False
        - Whether the Age is above 18 or not
- For Ex :
    - `driving = true;`
    - `smoke = false;`

### Real-World Example [5 min]

- When the user logged in to any platform like Amazon, Facebook, Gmail, etc. then the user needs to log in.
- When the user gets logged_in then in the backend the logged_in flag got true.
    - If user logged_in, then logged_in = true
    - If user logged_out , then logged_in = false

- During Shopping on the e-commerce platform. Some platform offers a 10% discount on the product only when you will use a credit card.
- Thus, the Credit card flag is set to true, only when you use a credit card.

![Screenshot (299).png](https://prod-files-secure.s3.us-west-2.amazonaws.com/ff94b4dd-cb13-4ede-8019-d6a8215bf3d5/e465cd02-3b6f-4ad7-8cbb-cb431ea5f4c4/Screenshot_(299).png)

![Screenshot (297).png](https://prod-files-secure.s3.us-west-2.amazonaws.com/ff94b4dd-cb13-4ede-8019-d6a8215bf3d5/c006ff11-f4a6-4354-822b-6ff9fff28022/Screenshot_(297).png)

### Student Task: Task to print the following information [ 5 min ]

- Name
- Age
- Gender
- has_driving_license
- citizen_of_india

## Float

![Screenshot (298).png](https://prod-files-secure.s3.us-west-2.amazonaws.com/ff94b4dd-cb13-4ede-8019-d6a8215bf3d5/c0842814-8cd5-45c1-bef3-7e1fe3553268/Screenshot_(298).png)

![Screenshot (296).png](https://prod-files-secure.s3.us-west-2.amazonaws.com/ff94b4dd-cb13-4ede-8019-d6a8215bf3d5/4a2c4498-5b38-4273-b7ab-9084618e3604/Screenshot_(296).png)

## How to declare a variable?

### Instructor Task (3 mins): Discuss how to declare a variable, Show them a live demo on Replit.

- In python, the variable is declared is as follows
    - x = 2;
    - y = "Masai";
    - z = 4.5 ;
    - w=True;
- **(CASE SENSITIVE)**
    
     x=2 
    
     X=3
    
     X ≠ x
    

### **Python is a fantastic language that automatically identifies the type of data for us**.

![Screenshot (300).png](https://prod-files-secure.s3.us-west-2.amazonaws.com/ff94b4dd-cb13-4ede-8019-d6a8215bf3d5/00749875-42ae-4838-b5e6-9a73e16daef3/Screenshot_(300).png)

### Student Task (5 mins): Perform the task

- Give a task to create a variable of their name, age, and gender and print the type of it on Replit.

## Many Values to Multiple Variables

Python allows you to assign values to multiple variables in one line.

Ex➖

```cpp
x,y,z= "box", "pencil", "eraser"

print(x)    # box 
print(z)    # pencil
print(y)    # eraser
# The number of variables matches the number of values, or else you will get an error
```

## One Value to Multiple Variables

Python allows you to assign the *same* value to multiple variables in one line.

Ex➖

```cpp
a=b=c="Maggi"
print(a)    # Maggi
print(b)    # Maggi
print(c)    # Maggi
```

## Type **Casting in Python**

Type Casting is the method to convert the variable data type into a certain data type in order to the operation required to be performed by users.

There can be two types of Type Casting in Python –

- Implicit Type Casting
- Explicit Type Casting

### Implicit Type Casting

In this, Python **converts the data type** into another data type **automatically**. In this process, users don’t have to involve in this process.

### Explicit Type Casting

In this, Python needs **user involvement to convert the variable data type** into a certain data type in order to the operation required.

Mainly type casting can be done with these data type functions:

- i**nt(): i**nt() function take float or string as an argument and return int type object.
- **float():** float() function takes int or string as an argument and returns float type object.
- **str():** str() function take float or int as an argument and return string type object.
- **bool():** str() function take float or int as an argument and return a boolean-type object.

![Screenshot (302).png](https://prod-files-secure.s3.us-west-2.amazonaws.com/ff94b4dd-cb13-4ede-8019-d6a8215bf3d5/f1e58a91-41b3-4ee1-afe4-bc8dbe07d225/Screenshot_(302).png)


---

## What are the basic mathematical operations?

![Screenshot (308).png](Screenshot_(308).png)

The common operators in Javascript are :

- **Addition**
- **Subtraction**
- **Multiplication**
- **Division**

### Student Task: Students need to solve a problem [ 3 min ]

Problem: Given a = 15, b = 25 . Calculate sum, difference, product, and division.

### Real-world example

![Untitled](Untitled%202.png)

- Visit amazon.com, and add some products to the cart.
- Adding products leads to an increase in the cart price.
- Manipulating the quantity or Adding the items affects the total price. This is how Mathematical operators are used behind the picture.

## Modulo Operator(%) [Remainder] [ 20 min ]

![Untitled](Untitled%203.png)

- When we divide a number into another, there are 4 terms that we need to understand
    - **quotient**
    - **divisor**
    - **dividend**
    - **remainder**
- Looking at the above picture, you will get clear about the above terms
- The remainder represents by **%**.
    - For Ex: var result = 75 % 4 [ Read as 75 Modulus 4 ]

### Instructor Task: Show demo to students, Explaining Modulus [10 min ]

**Let's take the analogy**: 

- There are many candidates who came to the company office to give interviews.
- Since there are more than **100 candidates**, **4 interview panel setups** where one interviewer is used to take the interviews.
- A **unique Id** is assigned to each candidate, starting from 1,2,3........to 100. If Interview Panel 1 is assigned to ID 1, Interview Panel is assigned to ID 2, and so on.
- Now, the question is Which Interview Panel will be assigned to Candidate 25?
    - The Solution Lies in Modulus: Just calculate **25 % 4** [ Since there are 4 Interview Panel]
    - Result = 25 % 4 = 1
    - Candidate 25 is assigned to Interview Panel 1.
    
    ![Screenshot (304).png](Screenshot_(304).png)
    

- **The power of % lies in distributing**

![Untitled](Untitled%204.png)

### Student Task: Google Server Analogy [ 5 min ]

Also, Using the same analogy of 4 Google servers and more than 1000 requests coming in a sequence.

Which server will process the 63rd request?

## Exponentiation Operator(**) [10 min ]

### Instructor Task: Explain the exponentiation operator with examples, Also discuss the difference between * and **

- It is used to compute the power of any number
    - a = 4
    - b = 2
    - c = a**b = 4**2 = 4*4 = 16

### **Difference between * and ****

![Screenshot (305).png](Screenshot_(305).png)

### Student Task: Find Square root using Exponentiation Operator [ 2 min ]

     Find the  Square root of 3 using the Exponentiation Operator

     **Solution :** result = 3**0.5

## How to Solve long expression? [ 5 min ]

![How.png](How.png)

### Instructor Task (5 mins): Discuss the steps to solve long expressions using brackets

- If you want to solve long expressions containing multiple operations then use brackets.
- Putting brackets also gives readability to code.
- For Ex :
    - **expr = ((a+b)*(c+d))/e**

### Student Task: Solve the Expression [ 5 min ]

- **For Ex** :
    
    **a = 3;**
    
    **b = 2;**
    
    **c = 4;**
    
    **sum = (a*2) + (b*2) + (c*2);     #(3*2)+(2*2)+(4*2)**
    
    **print(sum)      # 18 is the sum**
    

## String Concatenation

### Instructor Task (5 mins): Discuss examples of how to concatenate multiple strings

- Concatenation means a series of interconnected things.
- Use + to join two or more string

### Student Task: Students need to print their addresses. [ 5 min ]

- The problem statement is to store the following information into a unique variable i.e.
    - **House No**
    - **Area**
    - **City**
- The task is to print the complete address.

**Concatenation with Numbers**

```coffeescript
num1 = 2;
num2 = 3;
sum = num1 + num2;
print("Sum is ",sum);
```
