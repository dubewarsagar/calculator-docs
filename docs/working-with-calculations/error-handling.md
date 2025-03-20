# Handling Errors in the Calculator

> [!WARNING]
> Incorrect input or unsupported operations can result in errors. This section helps you understand and resolve them.

## Common Errors and Solutions

### ❌ Invalid Input
**Error Message:**  
```sh
Error: Invalid input. Please enter numbers only.
```
**Cause:**  
- Non-numeric input provided.

**Solution:**  
- Ensure you use numbers:
  ```sh
  calculator.exe add five 3  # ❌ Incorrect
  calculator.exe add 5 3      # ✅ Correct
  ```
---

### ❌ Division by Zero
**Error Message:**  
```sh
Error: Cannot divide by zero.
```
**Cause:**  
- Attempting to divide by zero.

**Solution:**  
- Ensure the denominator is not zero:
  ```sh
  calculator.exe divide 10 0  # ❌ Incorrect
  calculator.exe divide 10 2  # ✅ Correct
  ```
---

### ❌ Exponentiation with Negative Base and Fractional Power
**Error Message:**  
```sh
Error: Cannot compute negative base with a fractional exponent.
```
**Cause:**  
- Trying to calculate a negative base raised to a fractional exponent.

**Solution:**  
- Avoid fractional exponents for negative bases:
  ```sh
  calculator.exe pow -2 0.5  # ❌ Incorrect
  calculator.exe pow 2 0.5   # ✅ Correct
  ```
---

## Next Steps
For basic operations, see [Basic Calculator Operations](basic-operations.md).  
For advanced calculations, see [Advanced Functions](advanced-functions.md).