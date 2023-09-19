---
content_type: page
description: This page contains in-class questions for Lecture 5.
learning_resource_types: []
ocw_type: CourseSection
parent_title: In-Class Questions and Video Solutions
parent_type: CourseSection
parent_uid: cc74bf5b-1a22-399e-2712-70abfff469d7
title: Lecture 5
uid: 2d1ecaea-f49e-8ee7-cac3-ea3ce9cbe081
---
1.  ### Tuples
    
      
    
    Examine the code below. What does `always_sunny(('cloudy'), ('cold',))` evaluate to?
    
    ```
    def always_sunny(t1, t2):
     """ t1, t2 are non empty """
     sun = ("sunny","sun")
     first = t1[0] + t2[0]
     return (sun[0], first)
    
    ```
    
    {{< quiz_multiple_choice questionId="Q1_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}('sunny', 'cc'){{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}('sunny', 'ccold'){{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}('sunny', 'cloudycold'){{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution >}}{{< resource c9f180f7-568d-fdb9-55f6-4ae1ae784390 >}}{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}
  
3.  ### Simple Lists
    
      
    
    What is the value of L after you run the code below?
    
    ```
    L = ["life", "answer", 42, 0]
    for thing in L:
     if thing == 0:
      L[thing] = "universe"
     elif thing == 42:
      L[1] = "everything"
    
    ```
    
    {{< quiz_multiple_choice questionId="Q2_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}["life", "answer", 42, 0]{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}["universe", "answer", 42, 0]{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}["universe", "everything", 42, 0]{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}["life", "everything", 42, 0]{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution >}}{{< resource a656e4e2-eac1-6346-167e-90f6ff1be1b8 >}}{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}
  
5.  ### List Operations
    
      
    
    What is the value of L3 after you execute all the operations in the code below?
    
    ```
    L1 = ['re']
    L2 = ['mi']
    L3 = ['do']
    L4 = L1 + L2
    L3.extend(L4)
    L3.sort()
    del(L3[0])
    L3.append(['fa','la'])
    
    ```
    
    {{< quiz_multiple_choice questionId="Q3_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="true" >}}['mi', 're', ['fa', 'la']]{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}['mi', 're', 'fa', 'la']{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}['re', 'mi', ['fa', 'la']]{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}['do', 'mi', ['fa', 'la']]{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution >}}{{< resource 5b5ce068-2c40-8fcd-e630-aee685a1b530 >}}{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}
6.  ### List Aliasing/Mutation
    
      
    
    What is the value of brunch after you execute all the operations in the code below?
    
    ```
    L1 = ["bacon", "eggs"]
    L2 = ["toast", "jam"]
    brunch = L1
    L1.append("juice")
    brunch.extend(L2)
    
    ```
    
    {{< quiz_multiple_choice questionId="Q4_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}['bacon', 'eggs', 'toast', 'jam']{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}['bacon', 'eggs', 'juice', 'toast', 'jam']{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}['bacon', 'eggs', 'juice', ['toast', 'jam']]{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}['bacon', 'eggs', ['toast', 'jam']]{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution >}}{{< resource 22a6fadb-e4f1-343a-e332-e2313ecf66fe >}}{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}