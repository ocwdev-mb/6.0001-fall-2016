---
content_type: page
description: This page contains in-class questions for Lecture 7.
learning_resource_types: []
ocw_type: CourseSection
parent_title: In-Class Questions and Video Solutions
parent_type: CourseSection
parent_uid: cc74bf5b-1a22-399e-2712-70abfff469d7
title: Lecture 7
uid: f6173231-3f52-9164-402d-295ceb4706e8
---
1.  ### Black Box and Glass Box Testing
    
      
    
    With the below implementation, is the test set "n = 4 | n = -4 | n = 5" path complete?
    
    ```
    def is_even(n):
     """ 
     Returns True if a number is even
     and False if not 
     """
     if n > 0 and n % 2 == 0:
     return True
     elif n < 0 and n % 2 == 0:
     return True
     else: 
     return False
    
    ```
    
    {{< quiz_multiple_choice questionId="Q1_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="true" >}}&nbsp;Yes&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;No&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution >}}{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}
    
  

With the above implementation, which value for n is incorrectly labeled by is\_even?

{{< quiz_multiple_choice questionId="Q2_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}&nbsp;n is very large (and positive)&nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp; n is very small (and negative)&nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="true" >}}&nbsp;n is 0&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
{{< quiz_solution >}}{{< resource 2c04fb25-9121-79e0-e60b-f9336bd802d6 >}}{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}

  
  
6.  ### Errors
    
      
    
    Below is a piece of code and an error shown when running it. What is the problem?
    
    ```
    L = 3
    for i in range(len(L)):
     print(i)
    
    ERROR MESSAGE:
    
     File "C:/Users/Ana/.spyder2-py3/temp.py", line 2, in 
     for i in range(len(L)):
    
    TypeError: object of type 'int' has no len()
    
    ```
    
    {{< quiz_multiple_choice questionId="Q3_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}&nbsp;You are not allowed to name an integer with the variable name L&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;range is not allowed to have an expression inside its parentheses&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;You are not allowed to call len on an integer&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;You are not allowed to print the loop variable i&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution >}}{{< resource 383972c5-1db0-a96c-e222-1024b1e78b21 >}}{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}
  
8.  ### Exceptions
    
    If the user enters "twenty" in the code below what does the program do?
    
    ```
    try:
     n = int(input("How old are you? "))
     percent = round(n*100/80, 1)
     print("You've gone through", percent, "% of your life!")
    except ValueError:
     print("Oops, must enter a number.")
    except ZeroDivisionError:
     print("Division by zero.")
    except:
     print("Something went very wrong.")
    
    ```
    
    {{< quiz_multiple_choice questionId="Q4_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}&nbsp;prints "You've gone through 25.0 % of your life!"&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;prints "Oops, must enter a number."&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution >}}{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}
    

If the user enters "0" in the code above what does the program do?

{{< quiz_multiple_choice questionId="Q5_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="true" >}}&nbsp;prints "You've gone through 0.0 % of your life!"&nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp;prints "Division by zero."&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
{{< quiz_solution >}}{{< resource 3b1d84e0-2b94-31db-a47c-7a089b2f8d84 >}}{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}