
## Math operators



With Python you can add, subtract, multiply, divide numbers like this:

- addition = 72 + 23
- subtraction = 108 - 204
- multiplication = 108 * 0.5
- division = 108 / 9
- exponentiation = 2 ** 3
- modulo: Our final operator is modulo. Modulo returns the remainder from a division. So, if you type 3 % 2, it will return 1, because 2 goes into 3 evenly once, with 1 left over.

#####Operators Summary

|**Operator**|**Meaning**|
|------------|------------|
|+|addition|
|-|subtraction|
|*|multiplication|
|/|division|
|**|power|
|%|remainder of a division|



######Practice 1

We are going to do the following operations:
- Create a integer variable num equal to the sum of two numbers.
- Squar num variable.
- Multiply num from a new variables called num1 equal to the division of two numbers.

```python
>>> # create num variable
...
>>> num = 23 +90
>>> # Notice that a variable can be squared
...
>>> num ** 2
12769
>>> #Create the new variable num1
...
>>> num1= 56/71
>>> print num1
0
>>> #Notice that the division gives integers
... num1=float(56/71)
>>> print num1
0.0
>>> #Now num1 is a decimal (float variable)
...
>>> num*num1
0.0
>>>
```
---
######Practice 2
We are going to follow the steps bellow:
- Create two string variables.
- Sum them.

```python
>>>
>>> #Create two string variables
...
>>> var1 = 'Hello'
>>> var2=' World'
>>> #Sum string variables
...
>>> var1+var2
'Hello World'
>>>
```

---

##### Be careful!

- When you divide or multiply a integer by a float variable the result becomes float as well.


- When you divide an integer by another integer, the result is always an integer (rounded down, if needed).


- When you divide a float by an integer, the result is always a float.


- To divide two integers and end up with a float, you must first use float() to convert one of the integers to a float.


- When more than one operator appears in an expression, the order of evaluation
depends on the rules of precedence. For mathematical operators, Python follows mathematical convention.
You can use brackets `()`to reorder the operations.
