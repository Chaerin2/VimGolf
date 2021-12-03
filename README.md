# VimGolf
1. Add quotes to ansible playbook
---

2. Simple replacements
---
3. Satisfy the go linter
---
4. Plotting some variables in python
---
5. Python dataclasses

start file
```python
  1 from dataclasses import dataclass
  2
  3 @dataclass
  4 class Student:
  5     student_id: str
  6     name: str
  7     age: int
  8     score: float
  9
 10 fields = ""
 ```
 
 Endfile
 ```python
  1 from dataclasses import dataclass
  2
  3 @dataclass
  4 class Student:
  5     student_id: str
  6     name: str
  7     age: int
  8     score: float
  9
 10 fields = "student_id,name,age,score"
 ```     
 
