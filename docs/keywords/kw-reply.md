# reply

**Category:** KEYWORD | **Subcategory:** Control Flow

## Summary
Terminates the execution of the current procedure, method, or function, transmitting the resulting value back to the caller.

## Syntax
```verscript
reply <expression>
```

## Parameters / Arguments
- `expression` *(any)*: undefined

## Runnable Code Example
```verscript
def isPrime(n):
  if n < 2 then reply false
  loop i from 2 to sqrt(n):
    if n % i == 0 then reply false
  reply true
```
