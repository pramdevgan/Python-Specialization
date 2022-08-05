# # **Formative Assessment 2**

---

## String Comparison

Select all of the true statements about `is` and `==` regarding string comparison.  **Hint** , there will be more than one correct answer.

- Both `is` and `==` do the exact same thing.
- **`is` compares object IDs.**
- **`==` compares values.**
- `is` is the preferred way to check equality.

The middle two statements are true;`is` compares object IDs while `==` compares values. Because of this, `is` and `==` do not do the same thing. It is possible that two strings with identical values can be stored in the same memory location. In this case, the `is` operator would work. However, it is also possible that two strings with the same value can have different memory addresses. The `is` operator would not work in this example.
