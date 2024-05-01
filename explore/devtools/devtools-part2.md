# Part 2

## Basic DevTools

---

### Debugging
---
1. **Issue**: The document treated `num1` and `num2` as strings, leading to concatenation instead of addition. For e.g, `num1 = 1` and `num2 = 2` resulted in '12'.
2. **Solution**: After some research, I found that JavaScript can convert strings to numbers using the unary plus operator `+`. This operator tries to parse a string as a number. If successful it convert the string; otherwise, it results in NaN (Not a Number). To fix this, I add a unary plus to both `num1` and `num2` in the `calculateSum` function. You can see the fix.. screenshot at /expand/screenshots/fix.png.

---
