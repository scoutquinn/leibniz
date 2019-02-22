## leibniz

# SYNTAX
```
f(x) := x^2
f' should return 2x
df/dx should also return 2x

f(x) := x^2
F should return x^3 /3 +c
F' should return x^2
dF/dx should also return x^2 (or dF?)
F[0,1] should return 1/3 
```
`f(x) = x^2` what do?
`f(x)` should return f(x) = x^2

`f(x) := expression` to define f(x)

valid function and variable names: a-z, greek alphabet (lowercase)

capitals refer to the integral of the corresponding lowercase function/variable

abcdefghijklmnopqrstuvwxyz: functions, variables, can be redefined

ABCDEFGHIJKLMNOPQRSTUVWXYZ: refer to the integral of the corresponding function

[a..z]' is the derivative

defining an integral or derivative evaluates until the function is calculated and stores that function

eg `f'(x) := 2x` produces `f(x) = x^2 +c`

`F(x) := x^2` produces `f(x) = 2x` and locks `F(x) = x^2 +c where c=0`

`+c where c=0` is hidden from output and calculation

variables only declared inside functions



`f' or f'(x) or df/dx`: first derivative of f
`f'', f'''`: second, third derivative etc
`f^(2)`: second derivaitve?

`F`: integral of f
`F'`: integrate then derive f, should return f
`f'(F)`: derive then integrate f, should return f

`f(g(x))`: evaluate f of g of x, evaluate g(x) then evaluate f(x) with g
`f o g(x)`: composition, same result as f(g(x))

---

# SETS

RESERVED SETS:

`{P}, {N}, {Z}, {Q}, {R}, {C}, {H}, {G}`
(primes, naturals, integers, rationals, reals, complex, quarterions, gaussians)

{} empty set

sets denoted by {set}

sets defined by {set} = {set definition}

eg: {X} = {1, 2, ..., 10}

`x, ..., y` = range of x to y inclusive

`{X} = (1, 3)` = {2}

`{X} = (1, 3]` = {2, 3}

etc

{X} = `{x^2, x E P, 1 < x <= 10}` = {4, 9, 25, 49, 81}

Y in a set fefers to {Y}?

or

{Y} in set definitions?

---

# ALGEBRA SHIT

x^3 / 3 = x cubed divided by 3

x^3/3 = x to the 3/3

x ^ 3 / 3 should yell at you

x ^3 = what to the 3?

x^ 3 = x to the what?

x ^ 3 = what to the what?

"x^3 -1/3 / 3"?

possibility: 

```
x^3 /
      3
```
```
x^3
---
3
```

x^3 /3 = what on 3?

x^3/ 3 = x cubed on what?

()[] are the same, evaluated from innermost

{} denotes a set unless () or {} are inside

unicode for greek

---

# COMMENTS
```
f # comment until end of line

###
multiline comment between start of line ### and next ###
###
```
