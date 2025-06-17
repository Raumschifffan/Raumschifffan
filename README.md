```py
def greet(name):
    print(f"Greetings, my name is {name}")


def interests(*args):
    print("I'm interested in...")
    for arg in args:
        print('\t', arg)

def learning(*args):
    print("Currently learning...")
    for arg in args:
        print('\t', arg)

def run():
    greet("Raumschifffan")
    print()
    interests("Mathematics", "Japanese", "Korean", "Music", "Philosophy")
    print()
    learning("Advanced Python", "C++", "Rust", "Lunarvim", "Unicon", "Haskell")

>>>run()
Greetings, my name is Raumi

I'm interested in...
    Mathematics
    Japanese
    Korean
    Music
    Philosophy

Currently learning...
    Advanced Python
    C++
    Rust
    Lunarvim
    Unicon
    Haskell
```
