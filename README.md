This C++ Program is designed to hold fractions. For example 1 / 10 would be stored as two values, 1 and 10, not 0.1. The fractions are stored as a fraction in a normalized state. For example, instead of storing 5 / 15, you would store 1 / 3.

Constructors only take int values. One constructor takes a single int and the second takes two ints, the first for the numerator, the second for the denominator. The default constructor creates a "zero" fraction which would look like 0/1.

The unary operators being overloaded:
- (negation)
++ (post-increment)
++ (pre-increment)

The binary operators being overloaded:
+ (addition)
- (subtraction)
* (multiplication)
/ (division)
+= (addition and assignment)
The comparison operators: < <= == != >= >
<< (used with cout)
