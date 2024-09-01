In C++, data types specify the type of data that a variable can hold. They define the size and layout of the variable's memory, the range of values that can be stored within that memory, and the set of operations that can be applied to the variable.

### 1. Primary Data Types

| Data type | Size              | Description                                                                                                                               | Range                                 | Example                 |
| --------- | ----------------- | :---------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------- | ----------------------- |
| `int`     | Typically 4 bytes | Standard integer type                                                                                                                     | -2,147,483,648 to 2,147,483,647       | `int age = 25;`         |
| `float`   | Typically 4 bytes | Represents single-precision floating-point numbers                                                                                        | 3.4e-38 to 3.4e+38                    | `float pi = 3.14f;`     |
| `char`    | 1 bytes           | Represents a single character                                                                                                             | -128 to 127 (or 0 to 255 if unsigned) | `char letter = 'A';`    |
| `bool`    | 1 bytes           | Represents a boolean value(either `true (1)` or `false (0)`                                                                               | -                                     | `bool isActive = true;` |
| `void`    | -                 | Represents the absence of type(Used primarily in functions that do not return a value or to indicate a function that takes no parameters) | -                                     | `void printMessage();`  |

```python
from manim import *

class Manimation(Scene):
	def construct(self):
		text = Text("String value takes up")
		self.add(text)
```



   

