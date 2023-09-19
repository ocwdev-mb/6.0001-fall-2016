---
content_type: page
description: This page contains in-class questions for Lecture 2.
learning_resource_types: []
ocw_type: CourseSection
parent_title: In-Class Questions and Video Solutions
parent_type: CourseSection
parent_uid: cc74bf5b-1a22-399e-2712-70abfff469d7
title: Lecture 2
uid: 666db218-db6d-8103-cdcf-41e2960132be
---
1.  ### Strings
    
      
    
    What is the value of variable &grave;u&grave; from the code below?
    
    ```
    once = "umbr"
    repeat = "ella"
    u = once + (repeat+" ")*4
    ```
    
    {{< quiz_multiple_choice questionId="Q1_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="true" >}}&nbsp;umbrella ella ella ella&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;umbrellaellaellaella&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;umbrella&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;umbrella4&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution / >}}{{< /quiz_multiple_choice >}}
  
3.  ### Comparisons
    
      
    
    What does the code below print?
    
    ```
    pset_time = 15
    sleep_time = 8
    print(sleep_time > pset_time)
    derive = True
    drink = False
    both = drink and derive
    print(both)
    ```
    
    {{< quiz_multiple_choice questionId="Q2_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="true" >}}&nbsp;False then False&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;False then True&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;True then False&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;True then True&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution >}}{{< resource 65aaf446-8cd3-99bb-e709-87a4b31ced35 >}}{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}
  
5.  ### Branching
    
      
    
    What's printed when x = 0 and y = 5?
    
    ```
    x = float(input("Enter a number for x: "))
    y = float(input("Enter a number for y: "))
    if x == y:
     if y != 0:
     print("x / y is", x/y)
    elif x < y:
     print("x is smaller")
    else:
     print("y is smaller") 
    ```
    
    {{< quiz_multiple_choice questionId="Q3_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="true" >}}&nbsp;x is smaller&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;y is smaller&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;x / y is 0.0&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution >}}{{< resource 2dad9223-a5aa-ebd8-e51e-7c5f6beeb3d8 >}}{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}
  
7.  ### While Loops
    
      
    
    In the code below from Lecture 2, what is printed when you type "Right"?
    
    ```
    n = input("You're in the Lost Forest. Go left or right? ")
    while n == "right":
     n = input("You're in the Lost Forest. Go left or right? ")
    print("You got out of the Lost Forest!")
    ```
    
    {{< quiz_multiple_choice questionId="Q4_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}&nbsp;You're in the Lost Forest. Go left or right?&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;You got out of the Lost Forest!&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution >}}{{< resource e909e336-e407-93af-bc54-0dcf0b03ac3e >}}{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}
  
9.  ### For Loops
    
      
    
    What is printed when the below code is run?
    
    ```
    mysum = 0
    for i in range(5, 11, 2):
     mysum += i
     if mysum == 5:
      break
      mysum += 1
    print(mysum)
    ```
    
    {{< quiz_multiple_choice questionId="Q5_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="true" >}}&nbsp;5&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;6&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;21&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;24&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution >}}{{< resource 179b5f41-d5d9-0fdb-dfd6-b8c28021b263 >}}{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}