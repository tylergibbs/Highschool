Solve Diff Equations

uses racket's macros to define a language that can calculate any math equation that
uses addition, multiplication, exponentiation, natural logarithm, inverse, negative, sin, cos

numeric? determine if an expression is purely numeric

evaluate evaluates a numeric expression 

subs substitutes a value for a given variable

d/dx takes the derivative with regards to the given variable

fix simplifies a given expression removing any operations that are an identity 

tostr changes the expression to a string representation using standard math symbols

get-sym returns a list of all symbols in the expression

gradient compost the gradient with regard to all variables in the expression

get-func transforms the expression in to a lisp function taking in a variable for every symbol in the expression

plots plots the expression on a 3d surface
