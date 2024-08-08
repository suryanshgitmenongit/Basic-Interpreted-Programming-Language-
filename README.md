# Thoth-Interpreted-Programming-Language
Documentation:

```markdown


## Language Basics

### Variables

Variables are declared using the `let` keyword:

```
let x = 5
let y = 3.14
let name = "SenthilSivakumar"
```

### Data Types

 supports the following data types:
- Integers
- Floats
- Booleans (`true` and `false`)

### Operators

- Arithmetic: `+`, `-`, `*`, `/`
- Comparison: `<`, `>`, `<=`, `>=`, `==`
- Logical: `and`, `or`, `not`

## Control Structures

### If-Else Statements

```
if x > 5 do
    let y = 10
else
    let y = 5
```

### While Loops

```
while x < 10 do
    let x = x + 1
```

### For Loops 

```
for let i = 0; i < 5; let i = i + 1 do
    let x = x + i
```

## Error Handling

 provides basic error messages for common issues:
- Syntax errors
- Undefined variables
- Type mismatches
- Division by zero

Make sure to initialise variables you'll use before you use them 


###References:
Couldn't have made this without:
https://www.youtube.com/watch?v=1WpKsY9LBlY, https://github.com/VOYAGERX013/ShadowScript
and
Ruslan Spivak's blog post:
https://ruslanspivak.com/lsbasi-part1/

