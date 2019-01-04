# Python Basics:

## Comments in python:
```python
#can be used for single line comment
"""can be used for multiline comments""""
```

## Datatypes in python:

1. Numerical:
    * Integer(Int):
        <mark>**Effectively there is no limit to the size of an integer but there is a limit to your resources.**</mark>

        > Also there are different bases too but let's skip them for now because what we are going to do doesn't concern them and also they are not frequently used but don't skip them try yourself when you are home.

    * Float(Float):
        **Float is the double precision decimal point number in python. It's a cool type to work with.
        <mark>According to IEEE 754 Floating point Standards: </mark>**
        
        > the maximum value a floating-point number can have is approximately 1.8 ⨉ 10<sup>308</sup>. Python will indicate **a number greater than that by the string inf**

        > The closest a nonzero number can be to zero is approximately 5.0 ⨉ 10<sup>-324</sup>. **Anything closer to zero than that is effectively zero**

    * Complex(z):
       **This is one of the reason which makes python easy for dealing with mathematical problems. They just added ground support for conventional yet unconventional things.**

       Syntax for declaring complex variables: **'real_part'+'imaginary_part'j**

       ```python
        z = 3+2j
       ```   

2. Strings : <mark>**Again it's length doesn't depend upon the python it depends on the resources you have.**</mark>

3. Boolean : **<mark> Boolean is 0 or 1. Also False and True**

    ```python
    present = True
    present = true #Wrong form of assignment.
    ```


## Variables in python:

* It's easy and direct just assign whatever you want to assign to the name of the variable python don't need explicit mention of ***data type***.

## Indexes and Indentations:


## Operators in Pythons:
1. Arithmetic Operators:
   * Exponent( ** )
   * Floor Division( // )

2. Comparison Operators:
   * == (difference between = and ==)
   * '!='

3. Logical Operators:
   * and
   * or
   * not


4. Assignment Operataros:
    * += 
    * -= 
    * //= 
    * **=

5. Membership Operators:
   * in
   * not in

6. Identity Operators:
   * is : <mark>**Evaluates to true if the variables on either side of the operator point to the same object and false otherwise**</mark>
   * is not : **viceversa**

## Conditional Operators:
* If
* Else
* Elif

## Sequences:
* Lists
* Tuples
* Dictionary

## Iterations, Range Based Loop and While Loop