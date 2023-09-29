---
content_type: page
description: This page contains in-class questions for Lecture 3.
learning_resource_types: []
ocw_type: CourseSection
parent_title: In-Class Questions and Video Solutions
parent_type: CourseSection
parent_uid: cc74bf5b-1a22-399e-2712-70abfff469d7
title: Lecture 3
uid: 6f345174-e0dc-c7e8-1d42-cb983600c3b0
---
1.  ### String Manipulations
    
    What does the code below print?
    
    ```
    s = "6.00 is 6.0001 and 6.0002"
    new_str = ""
    new_str += s[-1]
    new_str += s[0]
    new_str += s[4::30] 
    new_str += s[13:10:-1]
    print(new_str)
    ```
    
      
    {{< quiz_multiple_choice questionId="Q1_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}&nbsp;260000&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;26100&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;26 100&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;nothing, it will give an error&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;6.00 is 6.0001 and 6.0002&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution >}}{{< resource 7133484b-6c6c-d61d-3135-927babcf844f >}}{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}
  
3.  ### For Loops with Strings
    
    How many times will the code below print "common letter"?
    
    ```
    s1 = "mit u rock"
    s2 = "i rule mit"
    if len(s1) == len(s2):
     for char1 in s1:
     for char2 in s2:
     if char1 == char2:
     print("common letter")
     break
    ```
    
    {{< quiz_multiple_choice questionId="Q2_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}&nbsp;0&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;2&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;4&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;5&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;6&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;7&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;8&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;10&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution >}}{{< resource 1ee521e6-b140-0a30-12d0-f70c2a8334ce >}}{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}