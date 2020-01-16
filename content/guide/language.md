---
title: Language Guide
---

# Language Guide

### Symbolic Expressions

`f[a,b,...]` - the basic form of every exression

### Lists

[`{...}`](/builtin/List) —
[`[[...]]`](/builtin/Part) —
[`Table`](/builtin/Part) —
[`Length`](/builtin/Part) —
[`Take`](/builtin/Part) —
[`Select`](/builtin/Part)

### Associations
[`<|...|>`](/builtin/Part) —
[`Keys`](/builtin/Part) —
[`Values`](/builtin/Part) —
[`Lookup`](/builtin/Part) —
[`Merge`](/builtin/Part) 

### Functional Operators
[`&`](/builtin/Part) ·
[`/@`](/builtin/Part) ·
[`Nest`](/builtin/Part) ·
[`NestList`](/builtin/Part) ·
[`FoldList`](/builtin/Part) ·
[`Array`](/builtin/Part) ·
[`...`](/builtin/Part) 


### Pattern Matching
[`-`](/builtin/Part) ·
[`--`](/builtin/Part) ·
[`|`](/builtin/Part) ·
[`..`](/builtin/Part) ·
[`/;`](/builtin/Part) ·
[`Cases`](/builtin/Part) ·
[`Position`](/builtin/Part) ·
[`...`](/builtin/Part)


### Rules & Transformations
[`->`](/builtin/Part) ·
[`:>`](/builtin/Part) ·
[`/.`](/builtin/Part) ·
[`...`](/builtin/Part)


### Definitions & Associations
[`->`](/builtin/Part) ·
[`:>`](/builtin/Part) ·
[`/.`](/builtin/Part) ·
[`...`](/builtin/Part)


### Attributes

A function is defined using the lazy-set operator `:=`,
with on the left-hand side the name of the function,
and on the right-hand side the expression that evaluates the function.

```wl
f := a+1
``` 
