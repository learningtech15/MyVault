**OM**
      <img width="196" height="116" alt="image" src="https://github.com/user-attachments/assets/71aa88c1-8b59-4136-867b-e52004393206" />


* Unit 1
                    How to use Jupyter

-----------------------------------------------------------------------------------------------------------------------------
                    1st - Introduction to Python

-----------------------------------------------------------------------------------------------------------------------------
                    2nd -Variables & operators | Part 1

-----------------------------------------------------------------------------------------------------------------------------
                    3rd -Variables & operators | Part 2

______________________________________________________________________________________________________________________________
* Unit 2 Assignment Explanation Video  

                    4th - Built-in Functions | Part 1

2-Types of Python Functions:
A. Built-in Function: (68- Pre-defined)

1- Round : (its round off post decimal)
      a= 4.33
      round(a)
        ==> 4

      b= 4.66
      round(b)
        ==> 5

      print(round(4.123456789, 5)    """6th Digit is 6 so 5th Digit will become 7"""
      ==> 4.12357           

      Math= 75.82
      Phy= 82.91
      Chem= 67.23
      print(round(Maths+Phy+Chem))    """ total will be 225.96 """
        ==> 5226


2- Divmod:  (its related with Division, provide Quotient & Reminder)

  a= divmod(27,5)     """ 27/5 --> Q=5 & R=2 """
  print(a)
      ==> (5,2)    """ 'a' is a  TUPPLE (its Variable with MULTIPLE Values) i.e. (.., .., ..,.. ,.. ,...) """
  
  type(a)
      ==> tuple
  print(a[0])
      ==> 3
  print(a[1])
      ==> 4
  
  a= divmod(148.789, 12)
  b= divmod(148.789, 13)
  c= divmod(148.789, 14)
  d= divmod(148.789, 15)
  
  Q= a[0] + b[0] + c[0] +d[0]
  R= a[1] + b[1] + c[1] +d[1]
  print("sum of qnts are" Q)
  round(print("sum of reminders are" R))
      ==> 42.2
      ==> 33


3- IsInstance Function:  isinstance (object, type)  
  --> OBJECT always be Single unit agrument, but  
  --> TYPE can be TUPPLE(stores multiple item in () )
      """ It checks Outpult & always be True / False only """

  isinstance (5, int)
      ==> True
  
  isinstance (5.7, int)
      ==> False
  
  isinstance (5.7, (int, float, complex))
      ==> True         (because data type is float)
   
  print(isinstance("python is amazing", (int,float,str)))
      ==> True           (because data type is string)
  
  isinstance(2+3j, (int,float,complex))
      ==> True           (because data type is complex)
  
  isinstance(3.79, (int,complex))
      ==> False           (because FLOAT data type is missing)
  
  isinstance(3.71, (float,int,complex))
      ==> True           (because data type is float)

3- Pow Function:  pow(x,y)   OR   pow(x,y,z)
 
pow(3,4)
    ==> 81

pow(2,5,7)      """ 2*2*2*2*2/7 and reminder will return 4 """
    ==> 4

pow(3,4,6)     """ 81/6 = 78, reminder is 3
    ==> 3

pow(3.2, 4)    
    ==> 104.8576.......

pow(2+3j, 2)    """ pow will work for complex num as well """
    ==> -5+12j

a= pow(24,2,7)
b= pow(24,3,7)
c= pow(24,4,7)
d= pow(24,5,7)
print(a,b,c,d)
    ==> 2 6 4 5

print("reminder of a is" a=pow(24,2,7))
print("reminder of b is" a=pow(24,3,7))
print("reminder of c is" a=pow(24,4,7))
print("reminder of d is" a=pow(24,5,7))
    ==> 2 6 4 5


-----------------------------------------------------------------------------------------------------------------------------
                    5th - Built-in Functions | Part 2


______________________________________________________________________________________________________________________________
Unit 3 Assignment Explanation Video

-----------------------------------------------------------------------------------------------------------------------------
                    6th - Conditional Statements | Part 1

-----------------------------------------------------------------------------------------------------------------------------
                    7th - Conditional Statements | Part 2

______________________________________________________________________________________________________________________________
* Unit 4 Assignment Explanation Video

-----------------------------------------------------------------------------------------------------------------------------
                    8th - Concepts of Loops | Part 1

-----------------------------------------------------------------------------------------------------------------------------
                    9th - Concepts of Loops | Part 2

-----------------------------------------------------------------------------------------------------------------------------
                    10th - Concepts of Loops | Part 3

______________________________________________________________________________________________________________________________
                    Unit 5 Assignment Explanation Video

-----------------------------------------------------------------------------------------------------------------------------
* 11th - User Defined Functions | Part 1

-----------------------------------------------------------------------------------------------------------------------------
                    12th - User Defined Functions | Part 2

-----------------------------------------------------------------------------------------------------------------------------
                    13th - User Defined Functions | Part 3

______________________________________________________________________________________________________________________________
* Unit 6 Assignment Explanation Video


**This is bold text**

_This text is italicized_

~~This was mistaken text~~

***All this text is important***

This is a <sub>subscript</sub> text

This is a <sup>superscript</sup> text

This is an <ins>underlined</ins> text
