# Changing Objects with Methods Formative Assessment 1

---

## Formative Assessment

Drag the code blocks into the box below so that the method `hello` will print a greeting using the `name` instance variable. **Note** , not all of the code blocks will be used.

Drag from here

* def hello(name):
* def hello():
* print(f"Hello, {name}.")

Construct your solution here

* def hello(self):
* print(f"Hello, {self.name}.")

The correct answer is:

```python
def hello(self):
  print(f"Hello, {self.name}.")
```

An instance method always takes `self` as the first argument. So `def hello(name):` and `def hello():` are not correct. When accessing an instance variable in a method, `self.` should always come before the variable name. So `print(f"Hello, {name}.")` is not correct.
