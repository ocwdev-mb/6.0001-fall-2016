---
content_type: page
description: This page contains in-class questions for Lecture 4.
learning_resource_types: []
ocw_type: CourseSection
parent_title: In-Class Questions and Video Solutions
parent_type: CourseSection
parent_uid: cc74bf5b-1a22-399e-2712-70abfff469d7
title: Lecture 4
uid: 828237fd-efb5-0c69-43b8-3bf16ff40267
---
1.  ### Function Calls
    
      
    
    How many total lines of output will show up if you run the code below?
    
    ```
    def add(x, y):
     return x+y
    
    def mult(x, y):
     print(x*y)
    
    add(1,2)
    print(add(2,3))
    mult(3,4)
    print(mult(4,5))
    ```
    
      
    {{< quiz_multiple_choice questionId="Q1_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}&nbsp;0&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;2&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;4&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;5&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution >}}{{< resource aa5ba8ed-a730-fe61-e8d6-42e0aa2dd5c5 >}}{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}
  
3.  ### Functions as Arguments
    
      
    
    What does the code below print?
    
    ```
    def sq(func, x):
     y = x**2
     return func(y)
    
    def f(x):
     return x**2
    
    calc = sq(f, 2)
    print(calc)
    ```
    
    {{< quiz_multiple_choice questionId="Q2_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}&nbsp;4&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;8&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;16&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;nothing, it will show an error&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution >}}{{< resource 116b77d9-7285-6a45-a540-4ffe27132bd5 >}}{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}