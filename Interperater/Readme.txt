{\rtf1\ansi\ansicpg1252\cocoartf1561\cocoasubrtf600
{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\margl1440\margr1440\vieww10800\viewh8400\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\fs24 \cf0 Solve Diff Equations\
\
uses racket's macros to define a language that can calculate any math equation that\
uses addition, multiplication, exponentiation, natural logarithm, inverse, negative, sin, cos\
\
numeric? determine if an expression is purely numeric\
\
evaluate evaluates a numeric expression \
\
subs substitutes a value for a given variable\
\
d/dx takes the derivative with regards to the given variable\
\
fix simplifies a given expression removing any operations that are an identity \
\
tostr changes the expression to a string representation using standard math symbols\
\
get-sym returns a list of all symbols in the expression\
\
gradient compost the gradient with regard to all variables in the expression\
\
get-func transforms the expression in to a lisp function taking in a variable for every symbol in the expression\
\
plots plots the expression on a 3d surface\
}