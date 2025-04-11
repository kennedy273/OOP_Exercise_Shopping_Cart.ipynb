

# 🛒 Shopping Cart Lab - Object Oriented Programming Practice

## Overview

This lab is designed to help you practice and strengthen your **Object-Oriented Programming (OOP)** skills using Python. You'll be working with the `shopping_cart.py` file, modifying and expanding it as you apply key OOP concepts like classes, attributes, methods, and object instantiation.

## Objectives

- Understand and apply OOP principles in Python
- Modify an existing class structure
- Experiment with class behaviors in a Jupyter Notebook
- Use `%autoreload` to streamline your development workflow

## Getting Started

To begin, make sure to enable `autoreload` in your notebook. This will allow your notebook to automatically pick up changes made to `shopping_cart.py`.  
> 💡 Remember: You'll need to reinitialize your class instance every time you make changes to the class definition.

```python
%load_ext autoreload
%autoreload 2
```

## Instructions

1. Open the `shopping_cart.py` file.
2. Modify and expand the class(es) within using proper OOP techniques.
3. Use the notebook to test your changes and experiment with your class instances.
4. Re-run your class initializations after making any updates to the file.

### Example

```python
from shopping_cart import ShoppingCart

cart = ShoppingCart()
cart.add_item("apple", 2)
cart.view_cart()
```

## Notes

- Focus on clean, readable, and reusable code.
- Be thoughtful about how you structure your classes and methods.
- Test frequently to make sure your code works as expected.

## Happy coding!

---

