# Fizz Buzz

## Imperative Style

Lets write a fizzbuzz functions that takes one argument n and returns
FizzBuzz if n is divisible by 15, Fizz if n is divisable by 3,
and Buzz if n is divisable by 5.

```wl
fizzbuzz[n_] := Which[
    Mod[n,15] == 0, "FizzBuzz",
    Mod[n,5] == 0, "Buzz",
    Mod[n,3] == 0, "Fizz",
    True, n
]

fizzbuzz[15]
```


## Functional Style

Fizzbuzz can also be implemented using pattern matching for the divisibility check.
The `/;` operator can be used to set and extra condition on a pattern. 


By adding the `Listable` attribute to fizzbuzz, the function
also accepts and returns a list of number as argument or result.

```wl
SetAttributes[fizzbuzz,Listable]
fizzbuzz[n_ /; Mod[n, 15] == 0] := "FizzBuzz";
fizzbuzz[n_ /; Mod[n, 3] == 0] := "Fizz";
fizzbuzz[n_ /; Mod[n, 5] == 0] := "Buzz";
fizzbuzz[n_] := n

fizzbuzz[Range[100]]
```