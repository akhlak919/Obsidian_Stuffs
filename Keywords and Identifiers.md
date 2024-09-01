Keywords are **predefined** reserved words in C++ that have special meaning to the compiler.

>[!example]
```cpp
float pi;
```

here `float` is a keyword that indicates `pi` is a variable of type floating point number.

Here is a list of all C++ keywords. (as of C++17)

| `alignas`    | `decltype`     | `namespace`        | `struct`       |
| ------------ | -------------- | ------------------ | -------------- |
| `alignof`    | `default`      | `new`              | `switch`       |
| `and`        | `delete`       | `noexcept`         | `template`     |
| `and_eq`     | `do`           | `not`              | `this`         |
| `asm`        | `double`       | `not_eq`           | `thread_local` |
| `auto`       | `dynamic_cast` | `nullptr`          | `throw`        |
| `bitand`     | `else`         | `operator`         | `true`         |
| `bitor`      | `enum`         | `or`               | `try`          |
| `bool`       | `explicit`     | `or_eq`            | `typedef`      |
| `break`      | `export`       | `private`          | `typeid`       |
| `case`       | `extern`       | `protected`        | `typename`     |
| `catch`      | `false`        | `public`           | `union`        |
| `char`       | `float`        | `register`         | `unsigned`     |
| `char16_t`   | `for`          | `reinterpret_cast` | `using`        |
| `char32_t`   | `friend`       | `return`           | `virtual`      |
| `class`      | `goto`         | `short`            | `void`         |
| `compl`      | `if`           | `signed`           | `volatile`     |
| `const`      | `inline`       | `sizeof`           | `wchar_t`      |
| `constexpr`  | `int`          | `static`           | `while`        |
| `const_cast` | `long`         | `static_assert`    | `xor`          |
| `continue`   | `mutable`      | `static_cast`      | `xor_eq`       |
#### C++ Identifiers
Identifiers are the unique names given to variables, classes, functions, or other entities by the programmer.

>[!example]
```cpp
int money;
double salary;
```

here `money` and `salary` are identifiers.

---
##### Rules for naming Identifiers

- Identifiers can be composed of letters, digits, and the underscore character.
- It has no limit on name length.
- It must begin with either a letter or an underscore.
- It is case-sensitive.
- We cannot use keywords as identifiers.

We can choose any name as an identifier if we follow the above rules. However, we should give meaningful names to the identifier that makes sense.



