# Functions and Built-in Python Tools

---

- **What are Functions?**

> ***Technical Term:-** A block of code designed to perform a particular task; they are very useful in making code simplified and manageable.*
> 
- **Example 1:** Take an example of **products on amazon** and how they are stored, and how much amount of code is there to manage that thing.
- **Example 2:** Take the **example of teams** that work on specific functionality of an e-commerce site, and then we can connect them later**, and** co-relate it with functions.
- **Example 3: Old TVs Vs. New TVs**, In old TVs, you have to go to channel numbers 1, 2, and 3 if you want to go to channel 4 using a Knob, but in new TVs, I can directly go to a channel by just pressing the button on the remote.

![tv](https://github.com/user-attachments/assets/f850a2d7-010a-41f0-9f26-155383e0d07e)


- **Example 4:** Take them to **Amazon and show them that if I click on a page multiple times, it will open that same page multiple times.**

# Pattern

What do you think when you hear the word Pattern
The pattern is something or a series of something is repeated in sequence.

The pattern you have seen before in colors, shapes, music, and even Maths.

```python
"hand-wash"
"eat-dinner"
"hand-wash"

"hand-wash"
"eat-dinner"
"hand-wash"

"hand-wash"
"eat-dinner"
"hand-wash"

"hand-wash"
"eat-dinner"
"hand-wash"

"hand-wash"
"eat-dinner"
"hand-wash"

def getDinner():
  "hand-wash"
  "eat-dinner"
  "hand-wash"

# here we are repeating the activities like hand-wash,eat-dinner, hand-wash multiple times
# so we have created this function which we call again and again and this will reduce the repetitions of activity
```

## Function

The function is a way by which you can control your code.

You perform a function in your day-to-day life.

Suppose whenever you go to Mall or School. You tie your shoes. Tying shoes is a daily activity you every day do. 

![Untitled](https://github.com/user-attachments/assets/a473af32-80de-48a9-a4c9-02079d2d434a)


In Tying shoes, there are certain steps, such as

1- Gather Laces

2- Knot

3- Loop

4- Swoop

5- Pull Tight
 

And you follow these steps on a daily basis

Now, suppose the same activity you assigned to the computer or a system to perform

![Untitled 1](https://github.com/user-attachments/assets/339a0f9c-2cc7-41fe-a5f5-fdbcb7e8271f)


So what you will do you repeat the same steps every day on the computer or a machine.

Here, for your help, there is an effective tool known as a function, which will follow the steps whenever you call it.

```python
def product() # will have the Product page code.
def payment() # will have the Payments page code.
def cart()   # will have the cart page code.

```

- Take them to **REPLIT** for some examples.
- Explain the syntax of a function declaration.

```python
#def declaration syntax.

def  name_of_function():

```

- Take an example of printing a name.

```python
/* 
1. Print your name using a function
2. First, show them how you can print without using function
3. Then declare a def and put the code inside the function.
4. Either you can take the TV channel and button pressing on 
	 remote example or a friend taking your stuff and now you 
	 have to call him to get the stuff.
*/

def channel_1():
	  x="Masai";
	  print(x)

#To get this thing to work you have to call the function
channel_1(); # Output will be "Masai"
```

- What will happen if i call the function multiple times.

```python
def channel_1():
	   x="Masai";
	   print(x);

channel_1()
channel_1()
channel_1()
channel_1()

#This will print "Masai" 4 times as I have called the def 4 times.
```

- Dry run this code for better understanding.
- Take two example of adding two numbers and subtracting 2 numbers without using functions.

```python
#Add without using the function
a=10;
b=15;
sum=a+b;
print(sum); # 25

#Subtract without using the function
x=10;
y=5;
difference=x-y;
print(difference);  # 5
```

- Convert the **above** example in **functions** by just putting the above code in two separate functions, **first show the output without calling them then, call them one by one.**

```python
#Add using the function
def superman():
	 a=10;
	 b=15;
	 sum=a+b;
   print(sum);

#Subtract using the function
def batman():
	x=10;
	y=5;
	difference=x-y;
	print(difference);  # 5

superman(); # 25
batman();  # 5
```

- **Activity Time:-** Create 4 functions to do **Addition, Subtraction, Multiplication, Division.**

```python
#Add using the function
def superman():
   	a=10;
	  b=15;
	 sum=a+b;
	 print(sum);

#Subtract using the function
def batman():
	  x=10;
	  y=5;
	difference=x-y;
	print(difference);

#Multiplication using the function
def spiderman():
	x=5;
	y=2;
	mult=x*y;
	print(mult);

#Division using the function
def ironman():
	x=10;
	y=5;
	div=x/y;
	print(div);

superman(); # 25
batman(); # 5
spiderman(); # 10 
ironman(); # 2
```

- Calling functions inside a loop.

```python
def superman():
	 a=10;
	 b=15;
   sum=a+b;
	 print(sum);

for i in range(5):
     superman()

/*

25
25
25
25
25

*/
```

- Explain about **Parameters** by giving them the calling superman for help example.

```python
def superman(a,b):
	sum_val=a+b
	print(sum_val)

x=4;
y=5;
superman(x,y); # 9
A=5;
ar B=10
superman(A,B); # 15
```

- **Activity Time:-** Create 4 functions to do **Addition, Subtraction, Multiplication, and Division** using **Parameters.**

```python
#Add using the function
def superman(a,b):
 sum=a+b;
 print(sum);

# Subtract using the function
def batman(x,y):
	difference=x-y;
	print(difference);

#Multiplication using the function
def spiderman(x,y):
	mult=x*y;
	print(mult);

#Division using the function
def ironman(x,y):
	div=x/y;
  print(div);

superman(10,15);  #25
batman(10,5);  # 5
spiderman(2,5);  # 10 
ironman(10,5); # 2
```

- Do the dry run of the above code for proper visualization.
- Introduce **Return** to them.

> Take the example of **Superman's function** to explain the concept of **Return**. Here **AMMI JAAN = SUPERMAN.**
> 

![Untitled 2](https://github.com/user-attachments/assets/aef45ea3-bbe9-4dfc-82cb-13a2f31b9019)


```python
#Addition using a def and return statement

def superman(a,b):
	sum=a+b;
	return sum;

  bucket=superman(10,15);
  print(bucket); # 25
```

- **Activity Time:-** Create four functions for **Addition, Subtraction, Multiplication, and Division** using **Parameters & Return** statements**.**
- **IMPORTANCE OF RETURN BY TAKING AN EXAMPLE**

> **Step 1: Superman** plans to **add** two numbers and send the answer to Batman.
> 

> **Step 2: Batman** will take the answer from **Superman, square** it and send it to Aqua man.
> 

> **Step 3:** **Aqua man** will take the answer from **Batman** and divide it by 10.
> 

```python
def superman(a,b):
	sum=a+b;
	return sum;

def batman(x):
	 square=x*x;
	return square 

def aquaman(y):
	div=y/10;
	return div;

step1=superman(10,15); 

step2=batman(step1);

step3=aquaman(step2);

print(step3);  #62.5

```

> Can also give an example of amazon when we add something to the cart and it will take us to the payment page, how they are linked to each other.
> 
- **Return** vs. **print()**

![Untitled 3](https://github.com/user-attachments/assets/aa9fee3f-00ed-4722-9a42-4ed082dc3fc1)


- Talk about **Global Scope** and **Local Scope.**

> Give an example of a Personal Phone and a Public Phone (PCO).
> 

![Capture](https://github.com/user-attachments/assets/277be441-7d19-4b22-b091-3417f38a084b)


- Give an example for this on **REPLIT**.
- Now, it’s time to do the **WE assignment.**

> **Problem 1:** Create a function to check if a number is prime or not. (Do the code on REPLIT and Dry run of it.)
> 

```python
def check_prime(n):
  flag = False
  for i in range(2,n):
    if n%i==0:
      flag = True
      break
  if flag == True:
    print("not prime")
  else:
    print("prime")

x=check_prime(13)

```

- Do the dry run of the above code for better understanding.

> **Problem 2:** Use the Above code to print Primes from 2 to a given limit.
> 

```python
#using the above check_prime() function I am checking the prime numbers
#in a given limit.

for i in range(lower_limit,upper_limit+1):
  x=check_prime(i);
  if(x==True):
    print(i,"is a Prime Number");
  else:
    print(i, "is Not a Prime Number");

```

- Do the dry run of the above code for better understanding.

---

### Inbuilt Functions

**Definition:** Inbuilt functions are those functions that are created by JavaScript developers and you use them to make your job easy.

- **Number:** Used to convert a string into a number.

```python
x="12";
y="24";
print(x+y); # 1224

num1=int(x);
num2=float(y);
print(num1+num2); # 36
```

- **toString:** Used to convert to string.

```python
 num1=12;
 num2=36;
print(num1+num2); # 48

x=str(num1)
y=str(num2)
print(x+y);    # 1236
```

- Talk about **append** and **Pop**, They were also inbuilt functions to perform their specific task in case of arrays.
- Introduce them to documentation, to show them the logic behind these functions and also to show them some more inbuilt functions.
- Take them to python Docs, and make them familiar.
- What is **Documentation?**
    1. Documentation is the true source of information about the tech that you want to use, wrote by the developers, who created them.
    1. Best way is to read the documentation if you want to know about the tech that you are using.
    1. These are like best notes already written for you, that you can see and learn many things.
    1. It is not important to learn everything, whenever you want to use these things just go and refer the documentation.
- For python documentation, we can refer to [**Python docs**](https://docs.python.org/3.9/)
- **Go to List section.**
    - append**():- Adds an element at the end of the list**
    - **pop():- It returns the removed element from the List.**
    - **rindex():- It returns the last index where that particular element is present after searching.**
    - **index():- It returns the first appearance of the searched value.**
    - **insert():**  method inserts the specified value at the specified position.
    
    ```python
    fruits = ['apple', 'banana', 'cherry']
    
    fruits.insert(1, "orange")
    ```
    
    - **del():-** It  removes the element from the specified index:
    - **join():-It will join the elements of the list with the thing that you have passed in it (separator).**
    
    ```jsx
    #This will be an activity basically.
    #Before this ask them how to join the following list to get an output
    #something like "chunnumunnutunnu";
    list =["chunnu","munnu","tunnu"];
    
    #we can basically use concatenation
    
    bag=""
    for i in range(len(list)):
    	bag=bag+list[i];
    
    print(bag); # chunnumunnutunnu
    ```
    
    Now explain to them the inbuilt join() function.
    
    ```python
    list =["chunnu","munnu","tunnu"];
    x= "".join(list)
    
    print(x); # chunnumunnutunnu
    ```
    
    - **slice():-** The `slice()`  function returns a slice object.
    
    A slice object is used to specify how to slice a sequence. You can specify where to start the slicing, and where to end. You can also specify the step, which allows you to e.g. slice only every other item.
    
- **Go to Strings Section.**
    - **upper().**
    - **lower().**
    - **split():- It** splits a string into a list. You can specify the separator, default separator is any whitespace.
    
    ```python
    txt = "hello, my name is Peter, I am 26 years old"
    x = txt.split(", ")
    print(x)
    
    # ['hello', 'my name is Peter', 'I am 26 years old']
    ```
    

**Problem 1: Create our own Split function .**

```python
str="the quick brown fox jumps";
def mysplit(str):
  bag=""
  output=[];
  for i in range(len(str)):
    if str[i]!=" ":
		    bag=bag+str[i]
    else:
      if(bag!=""): 
        output.append(bag);
        bag="";	
  print(output)
	
  
mysplit(str)
```
