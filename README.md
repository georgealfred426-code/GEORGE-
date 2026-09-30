WELCOME PYTHON
def welcome(name):
    return "Hello, " + name + "! Welcome to PLP."


print(welcome("Amina"))
print(welcome("Brian"))
print(welcome("Fatuma"))
def welcome(name):
    return "Hello, " + name + "! Welcome to PLP."


print(welcome("Amina"))
print(welcome("Brian"))
print(welcome("Fatuma"))Hello, Amina! Welcome to PLP.
Hello, Brian! Welcome to PLP.
Hello, Fatuma! Welcome to PLP.def double(number):
    return number * 2


def is_pass(score):
    return score >= 50


def greet(name, greeting="Hello"):
    return greeting + ", " + name + "!"


print(double(7))
print(double(10))
print(is_pass(80))
print(is_pass(20))
print(greet("Amina"))
print(greet("Brian", "Habari"))
14
20
True
False
Hello, Amina!
Habari, Brian!# PLP Python Week 4

This assignment is about writing simple Python functions.

* `welcome.py` - Contains a `welcome()` function that welcomes three people.
* `toolbox.py` - Contains three functions: `double()`, `is_pass()`, and `greet()`.

The hardest function for me was `greet()` because it uses an optional greeting. I needed to understand how to use the default value `"Hello"`.
plp-python-week4
│
├── welcome.py
├── toolbox.py
└── README.md
plp-python-week4

README.md
toolbox.py
welcome.py


