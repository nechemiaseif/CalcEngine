# CalcEngine
Pluralsight tutorial demonstrating use of polymorphic references, abstract classes, and overloaded methods

CalculateBase is an abstract class with the contract method calculate(). 
Derived classes such as Adder, Divider, etc. override this method with their unique functions.

MathEquation offers an alternative suite of mathematical functions,
with a switch statement that allows client code to select a desired mathematical operation.
