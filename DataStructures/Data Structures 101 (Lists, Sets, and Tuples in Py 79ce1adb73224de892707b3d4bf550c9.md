![Untitled](https://github.com/user-attachments/assets/9fd29571-65e2-487f-a54c-789b05857330)# Data Structures 101 (Lists, Sets, and Tuples in Python)

---

- **Outline:**
    
    ### Lecture Script: Data Structures 101
    
    **Duration**: 1 hour and 40 minutes
    
    **Learning Objectives (LOs)**:
    
    - Lists in Python
    - Sets in Python
    - Tuples in Python
    
    ---
    
    ### Introduction to Data Structures (10 minutes)
    
    **Why:**
    
    Data structures are a fundamental part of programming. In Python, we use data structures to store, organize, and manage data. Understanding them is like understanding how to organize files in a cabinet. The type of cabinet (data structure) you choose will affect how quickly you can find, add, or remove a file (data).
    
    ---
    
    ### 1. **Lists in Python (25 minutes)**
    
    **What:**
    
    A list in Python is an ordered collection of items, which can be of any type (strings, numbers, etc.). Lists are mutable, meaning their items can be changed after creation.
    
    **Why:**
    
    Imagine you're managing a grocery list. As you shop, you may want to add or remove items. Lists in Python are like that—flexible, ordered, and easy to update.
    
    **Analogy:**
    
    Think of a list as a row of lockers, each with a unique position number (index). You can put any item in each locker, and you can open any locker to change or remove an item whenever you need.
    
    **Real-World Example:**
    
    Consider an app that manages tasks. Each task can be stored as an item in a list. You can add new tasks, remove completed ones, or update existing tasks.
    
    **Exercise:**
    
    1. Create a list of 5 tasks you plan to complete this week.
    2. Write Python code to:
        - Add a new task.
        - Remove a task you have completed.
        - Change a task's description.
        - Print the final list of tasks.
    
    ```python
    tasks = ["Buy groceries", "Complete homework", "Call a friend", "Go for a walk", "Read a book"]
    # Add a new task
    tasks.append("Visit a doctor")
    # Remove a completed task
    tasks.remove("Complete homework")
    # Update a task
    tasks[1] = "Call mom"
    # Print the list
    print(tasks)
    
    ```
    
    **Understanding Check:**
    
    - Why are lists useful when managing changing data?
    - What happens when you try to access an item that doesn’t exist in the list?
    
    ---
    
    ### 2. **Sets in Python (25 minutes)**
    
    **What:**
    
    A set is an unordered collection of unique items. Unlike lists, sets do not allow duplicates, and their elements cannot be accessed using indices.
    
    **Why:**
    
    If you're keeping track of a guest list for a party, you don't want to invite the same person twice. A set in Python helps ensure that each guest appears only once.
    
    **Analogy:**
    
    Imagine you're organizing an event where every attendee needs a unique ID. The set ensures that no ID is repeated, and it doesn't matter in which order the IDs are checked.
    
    **Real-World Example:**
    
    In an e-commerce website, a set can be used to track which unique products a user has viewed. No matter how many times they view the same product, it will only appear once in the list of viewed items.
    
    **Exercise:**
    
    1. Create a set of favorite books you’ve read.
    2. Add a new book to your set.
    3. Remove a book from your set.
    4. Check if a certain book is in your set.
    5. Print the final set of books.
    
    ```python
    books = {"1984", "To Kill a Mockingbird", "The Great Gatsby"}
    # Add a new book
    books.add("Brave New World")
    # Remove a book
    books.remove("1984")
    # Check if a book is in the set
    print("The Great Gatsby" in books)
    # Print the set
    print(books)
    
    ```
    
    **Understanding Check:**
    
    - How are sets different from lists in terms of performance and use cases?
    - What happens if you try to add a duplicate item to a set?
    
    ---
    
    ### 3. **Tuples in Python (25 minutes)**
    
    **What:**
    
    A tuple is an ordered collection of items, just like a list, but tuples are immutable, meaning once they are created, they cannot be modified.
    
    **Why:**
    
    Imagine a tuple as a travel itinerary. Once the trip is booked, you can’t change the destinations, but you can view them at any time. Tuples are useful when you want to ensure that data remains constant.
    
    **Analogy:**
    
    Think of a tuple like a set of legal documents—once signed, they cannot be altered. However, you can refer back to them as needed.
    
    **Real-World Example:**
    
    Tuples are ideal for storing information that should not change, like coordinates (latitude, longitude) of a city. Once the coordinates are set, they remain fixed.
    
    **Exercise:**
    
    1. Create a tuple that represents your travel itinerary (three cities you plan to visit).
    2. Try to update the second city and see what happens.
    3. Print the tuple of cities.
    
    ```python
    itinerary = ("New York", "London", "Tokyo")
    # Try to update the tuple (this will raise an error)
    # itinerary[1] = "Paris"
    # Print the tuple
    print(itinerary)
    
    ```
    
    **Understanding Check:**
    
    - Why would you use a tuple instead of a list?
    - What happens when you try to modify a tuple?
    
    ---
    
    ### **Conclusion & Summary (15 minutes)**
    
    **Recap:**
    
    - **Lists:** Ordered, mutable, and flexible—use them when you need to modify data frequently.
    - **Sets:** Unordered, unique, and efficient—use them when you need to ensure no duplicates.
    - **Tuples:** Ordered, immutable, and constant—use them when the data should not be changed.
    
    **Final Exercise:**
    
    1. Create a list of your top 5 movies.
    2. Convert this list into a set.
    3. Finally, convert the set into a tuple.
    
    ```python
    movies_list = ["Inception", "The Matrix", "Interstellar", "Inception", "The Matrix"]
    # Convert to set
    movies_set = set(movies_list)
    # Convert to tuple
    movies_tuple = tuple(movies_set)
    # Print final tuple
    print(movies_tuple)
    
    ```
    
    **Understanding Check:**
    
    - What were the differences in the behavior of the list, set, and tuple during the conversion?
    
    This structure will help students not only understand the different data structures but also gain hands-on experience with them through real-world analogies and practical exercises.
    
- **Notes:**
    
    # How do we store information? [10 min]
    
    ### Instructor Task (5 mins): Discuss the difference between variables and Lists.
    
    - We use variables to store the data.
    - For Example: If I said you want to store the name of Rahul’s Current girlfriend’s age.
    
    So you will simply make a girlfriend_age variable
    
    ```jsx
    girlfriend_age=18
    ```
    
    But if I said to you to store all his girlfriend's age till today
    
    To store 7 girlfriends’ ages, we need to declare 7 variables.
    
    ```python
    girlfriend3_age=25
    girlfriend2_age=20
    girlfriend4_age=21
    girlfriend5_age=20
    girlfriend6_age=28
    girlfriend1_age=21
    girlfriend7_age=24
    
    ```
    
    *Isn’t it possible that one variable will contain all names?*
    
    *Yes, It is possible with the Lists.*
    
    # Lists
    
    - can hold data of any data type and data object.
    - **Mutable** ⇒ Once the list is created you may➖
    - Terms➖
    
    - If I want to store all 5 names in a single variable, then it is possible through a list
    
    ### **Problem: Declare and print 3 students’ names using variables**
    
    ```python
    name1 = "Rahul";
    name2 = "Shubham";
    name3 = "Rishabh";
    print(name1);
    print(name2);
    print(name3);
    
    ```
    
    ### Problem**: Declare and Print 3 student’s names using an List**
    
    ```python
    names = [“Rahul”, Shubham”, “Rishabh”];
    print(names[0]);
    print(names[1]);
    print(names[2]);
    ```
    
    ### Problem: Solve the following problem
    
    **Perform the following tasks :**
    
    1. **Create a List of vegetables**
    1. **Store 3 vegetables**
    1. **Print all the vegetables**
    
    ```python
    vegetables = [“Tomato”, “Beans”, “Onion”];
    print(vegetables[0]);
    print(vegetables[1]);
    print(vegetables[2]);
    
    ```
    
    *Note: Don’t write vegetables[3] that will give* `IndexError: list index out of range`
    
    ### Problem: Solve the following problem
    
    This is NH-44 Highway which is passing through different states;
    
    Could you pls put this in a list and print it one by one;

    ![Untitled](https://github.com/user-attachments/assets/26ed11ff-777b-4061-ad7e-c149fa5a570a)

  
    
    ```python
    highways= [“Jammu-Kashmir”, “Karnataka”, “Tamil Nadu”];
    print(highways[0]);
    print(highways[1]);
    print(highways[2]);
    
    ```
    
    ## type()
    
    - The type of a Python object determines what kind of object it is; every object has a type. An object’s type is accessible as its [`__class__`](https://docs.python.org/3/library/stdtypes.html#instance.__class__)
     attribute or can be retrieved with `type(obj)`
    - What is the data type of a list?
    
    ## How to extract data from the list
    
    - **Indexing**
    - **Slicing**
    
    ## How to find the length of the list?
    
    - It means How many elements present in the list.
    - Use the `len()` function to calculate the length.
    
    ### Problem: **Find the length of the vegetable list.**
    
    ```python
     vegetables = [ ”Tomato”, “Beans”, “Onion”];
     print(len(vegetables));
    ```
    
    ### Problem: Solve the following problem
    
    **Perform the following tasks :**
    
    1. **Create a list of prices.**
    1. **Store the prices of 3 products in the list**
    1. **Print the price of the last product.**
    
    *Not a generic code :*
    
    ```python
     prices = [45, 71, 29];
     print(prices[2]);
    
    ```
    
    *Generic Code :*
    
    ```python
    prices = [45, 71, 29];
    last_index = len(prices) -1;
    print(prices[last_index])
    
    ```
    
    ## Operating Over Lists
    
    - **Add**
    - **Replace**
    - **Delete**
    
    ## How to print all elements using Loop?
    
    ### **Loop Through a List**
    
    - print all the elements using a loop.
    
    ### Problem**: print all the elements of the list using a loop.**
    
    ```python
    movies = [];
    movies.append("batman");
    movies.append("superman");
    movies.append("ironman");
    
    for i in range(len(movies)):
      print(movies[i])
    
    ```
    
    ### Problem**: Perform the following tasks :**
    
    1. **Create a List of movies and actors**
    1. **Print all the movies names with actors**
    
    ```python
     movies = ["bahuballi", "Spider-Man", "Iron Man", "Super Man"]
     actors = ["Prabhas", "Tom holland", "Robert Downey", "Henry Cavil"]
    
    for i in range(len(movies)):
      print(movies[i], actors[i])
    
    #Note: The length of both Lists should the be same
    ```
    
    ## List with Loop and Break
    
    ### Problem**: Print the first 3 items in the List using a loop.**
    
    ```python
    #First Way
    
    movies = ["bahuballi", "Spider-Man", "Iron Man", "Super Man"];
    for i in range(3):
    	print movies[i]
    ```
    
    ```python
    #Second Way [ Using Break ]
    
    movies = ["bahubali", "Spider-Man", "Iron Man", "Superman"]
    for i in range(len(movies)):
      if i==3:
        break
      print(movies[i]);
    ```
    
    ## Lists with Loop and Continue
    
    ### Problem**: Print all movies except the third movie.**
    
    ```python
    
    movies = ["bahubali", "Spider-Man", "Iron Man", "Superman"]
    for i in range(len(movies)):
      if i==2:
        continue
      print(movies[i]);
    ```
    
    ### Problem**: Print all movies except the third and fifth movies.**
    
    ```python
    
    movies = ["bahubali", "Spider-Man", "Iron Man","Superman","Thor", "Avengers"]
    for i in range(len(movies)):
      if i==2 or i==4:
        continue
      print(movies[i]);
    ```
    
    ### Problem**: Find the sum of all subject marks and average also.**
    
    ```python
    subject_marks = [10, 15, 19, 20, 21];
    sum_marks = 0;
    
    for i in range(len(subject_marks)):
    	sum_marks = sum_marks + subject_marks[i];
    
    average = math.floor(sum_marks/len(subject_marks))
    print("Total sum is ",sum_marks);
    print("Average is ",average);
    ```
    
    ---
    
    ### **What are Mutability and Immutability**
    
    ### **Mutability**
    
    In Python, mutability means you can directly modify an object after the creation
    . For example, a list is a mutable object. After creating a list, you can add, modify, or remove elements from it.
    
    ![Untitled_(3)](https://github.com/user-attachments/assets/1cdf1798-847d-4cb8-a3b7-79e2ede5ef3d)

    
    **ALT**
    
    ### **Immutability**
    
    In Python, immutability means you cannot directly modify an object after the creation
    . For example, Tuple is an immutable object. After creating a tuple, you cannot add, modify, or remove elements from it.
    
    ![Untitled_(4)](https://github.com/user-attachments/assets/6428e519-1bbe-4857-8406-138b6058f52b)

    
    **ALT**
    
    ### **Student task: Ask students to add some mutable & immutable things from real life.**
    
    ## Student task(10min)
    
    Suppose you are building an E-commerce website, Here are some of the operations you need to do in creating a website
    1- Track the transaction History
    
    2- Date and day showing on the website
    
    3- Deals and Discounts you will offer to the user
    
    4-User profile, Name, age address,and contact info
    
    Here in these four operations, you need to find the mutable and immutable objects
    
   ![Untitled 1](https://github.com/user-attachments/assets/0dce0124-c84b-43b6-bcba-68a65e71294b)

    
    ```python
    Such data types whose content can be changed are called 
    mutable objects;
    numbers = [1,2,3,4,5,7]
    print(numbers)
    numbers[2]= 9
    print(numbers)
    
    Such data types whose content can not be changed are called 
    immutable objects
    name = "aman"
    print(name)
    name[2]= "g"
    print(name)
    
    ```
    
    ```python
    name = "aman"
    name[2]= "g"
    print(name)
    #Not able to change the content
    ```
    
    # Sets
    
    - Sets are used to store multiple items in a single variable.
    - Sets are declared using { } without a colon.
    - Set items are unordered (which means that the items in a set do not have a defined order), unchangeable (meaning that we cannot change the items after the set has been created), and do not allow duplicate values.
    - No fetching possible (No Indexing and Slicing)
    - We can add or delete the data.
    - Data within the sets are automatically sorted.
    - They contain only unique data. (**Data Duplication not possible**)
    - **Syntax ⇒ `{** item1,item2, item3, ... }`
    - **Example➖**
    - Since Sets consist of sorted and unique data, searching for a particular element within the set is very quick.
    - **Searching in the set ⇒**
    
    ## Functions with Sets
    
    - To convert a list into a set
    - To add a new element to the set
    
    ## **Another method to create a Set**
    
    ```python
    t = set(("apple", "banana", "cherry")) # note the double parenthesis
    print(t)
    ```
    
    ## **To Access the elements**
    
    ```python
    t = {"apple", "banana", "cherry"}
    for x in t:
      print(x)
    ```
    
    ## **To add an item to the set**
    
    ### **Note➖ Once a set is created, you cannot change its items, but you can add new items.**
    
    ```python
    t = {"apple", "banana", "cherry"}
    t.add("kiwi")
    print(t)
    ```
    
    ## **To add list items in the set**
    
    ```python
    t = {"apple", "banana", "cherry"}
    l=["potato","chili","onion"]
    t.update(l)
    print(t)
    ```
    
    ## **To remove an item in a set,**
    
    - **use the `remove()`, or the `discard()` method.**
    - **remove()**➖If the item to remove does not exist, **`remove()`** will raise an error.
    - **discard()**➖ If the item to remove does not exist, **`discard()`** will **NOT** raise an error.
    
    ```python
    t = {"apple", "banana", "cherry"}
    t.remove("apple")
    t.discard("cherry")
    ```
    
    # Tuples
    
    - Sibling of List
    - **Immutable Data Object** ➖ Once you create the tuple, you can’t manipulate it. (no addition, deletion, or replacement)
    - We can
    - A safer option for data collection
    - When the objective is to collect the data and has no further objective of editing it ⇒ **Use TUPLE**
    
    ## Creating Tuple
    
    **To create a tuple, we use parenthesis (round bracket)**
    
    ```python
    t=(1,2,7,4,9)   # created tuple t
    print(t)        # OUTPUT => (1, 2, 7, 4, 9)
    ```
    
    ```python
    thistuple = ("apple", "banana", "cherry")
    print(thistuple)
    ```
    
    Tuple items are indexed, the first item has an index `[0]`
    
    ## Type of Tuple
    
    ```python
    t=(5,7,3,0,66)
    print(type(t))     # OUTPUT => <class 'tuple'>
    ```
    
    **NOTE ➖ `t.append()` `t.pop()` `t[0]=8`      All of these will give you error**
    
    ## Merge the Tuples into a new Tuple
    
    ```python
    t1=(6,9,3)
    t2=(8,5,2)
    t3=t1+t2
    print(t3)         # OUTPUT => (6, 9, 3, 8, 5, 2)
    ```
    
    ## Indexing and Slicing in Tuple
    
    Same as in the List
    
    ```python
    K=(1,6,7,40,0,4,66,46,33,89,"Danny",(1,4,3,5),[1,4,6])
    
    print(K[0:2:1])            #  (1, 6)      
    print(K[ :2])              #  (1, 6)               
    print(K[-7:-3])            #  (66, 46, 33, 89)            
    print(K[-7:-6])            #  (66,)  
    print(K[-2:-4])            #  ()
    print(K[-2:-4:-1])         #  ((1, 4, 3, 5), 'Danny') 
    print(K[ : :-1])  
    '''
    ([1, 4, 6], (1, 4, 3, 5), 'Danny', 89, 33, 46, 66, 4, 0, 40, 7, 6, 1)
    '''
    print(K[-1][:-1])          # [1, 4]
    print(K[-2][::-1])         # (5, 3, 4, 1)
    print(K[ : :-2])           # ([1, 4, 6], 'Danny', 33, 66, 0, 7, 1)
    print(K[-2][::-2])         # (5, 4)
    K[-1].append(9)
    print(K) # (1, 6, 7, 40, 0, 4, 66, 46, 33, 89, 'Danny', (1, 4, 3, 5), [1, 4, 6, 9])
    
    '''
    NOTE:- List inside Tuple can be manipulated 
    '''
    ```
    
    ## Need to Create tuples
    
    ![Untitled 2](https://github.com/user-attachments/assets/642e953b-5a5e-4e10-95c6-682039f5792b)

    
    • Sometimes you don’t want data to be modified. If the values in the collection are meant to remain program’s life, use the program, using a tuple instead of list guards against accidental modification.
    
    <img width="964" alt="Untitled 3" src="https://github.com/user-attachments/assets/de712d26-f3f9-40e2-add4-6abfa5b01bb5">

    
    <img width="944" alt="Untitled 4" src="https://github.com/user-attachments/assets/5a29b89c-dc8e-455c-b121-145c5151ecde">

    
    ```python
    subjects = ('dsa', 'frontend', 'development', 'communication-skills' )
    print(subjects)
    
    types_of_transaction = ('internet banking', "upi",'neft')
    print(types_of_transactions)
    
    ```
    
    **Note
    Tuples are very similar to a list but it is immutable -hence it does not support those operations of the list where the list gets changed.**
    
    ```python
    tup= (3,4,5,6,7,)
    x = tup[0]
    for i in range(len(tup)):
      print(tup[i])
    
    # length of the tuple
    print(len(tup))
    ''' Add item => first convert Tuple in list append it and 
    then change it back to a tuple.'''
    y=list(tup)
    y.append(34)
    tup=tuple(y)
    print(tup)
    
    ```
    
    # Interconvert List and Tuples
    
    ```python
    li = [1,3,5,6]
    x = tuple(li)
     print(x)
    
    tup = (1,2,3,7)
    x = list(tup)
    print(x)
    
    # examples of lists and tuples
    
    li = [23,34,45]
    
    if 65 in li:
       print("Found")
    else:
       print("Not Found")
    
    tup = (23,34,45)
    
    if 65 in tup:
       print("Found")
    else:
       print("Not Found")
    
    ```
    
    **Happy Coding!**
    

---

[data:image/gif;base64,R0lGODlhAQABAIAAAP///wAAACH5BAEAAAAALAAAAAABAAEAAAICRAEAOw==](data:image/gif;base64,R0lGODlhAQABAIAAAP///wAAACH5BAEAAAAALAAAAAABAAEAAAICRAEAOw==)

​

##
