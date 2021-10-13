# module template

## What is this ??

This template provides you with a module template which makes it easy to make module.

## Directory Hierarchy

.  
├── main.py  
├── module_template  
│   ├── __init__.py  
│   └── test.py  
└── __init__.py  

## Calling the Module

In the current directory, you make main.py there and you write down like this in that file.

```main.py
import module_template

# If you want to use variable.
print(module_template.TEST_STRING)

# If you want to use method.
module_template.test_method()

# If you want to use class.
test = module_template.TestClass()
print(test.test)
```
