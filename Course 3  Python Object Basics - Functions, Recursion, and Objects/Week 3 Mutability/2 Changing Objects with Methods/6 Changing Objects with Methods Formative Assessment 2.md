# Changing Objects with Methods Formative Assessment 2

---

## Formative Assessment

Assume the following code:

```python
class Dog:
  def __init__(self, name, breed):
    self.name = name
    self.breed = breed

  def bark(self):
    print("Woof, woof!")

my_dog = Dog("Brutus", "Pomeranian")

```

What code would you add to print `Woof, woof!`?

- bark(my_dog)
- my_dog.bark(self)
- bark.my_dog()
- ***my_dog.bark()***

The correct answer is `my_dog.bark()`.

<details open=""><summary><strong>Statement</strong></summary>

Printing `Woof,woof!` comes from the `bark` method. To call this method, start with the variable that represents the `Dog` object, which is `my_dog`. Add a `.` and then add the name of the method, `bark`. Method calls use parenthesis, and any parameters go between these parenthesis. `self` is only a parameter when the method is declared, not when it is called.
</details>