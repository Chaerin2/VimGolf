# VimGolf
1. Add quotes to ansible playbook
---
##### 가장 마지막 줄에 있는 state:에 따옴표를 추가해주는 문제이다.
![문제1](https://user-images.githubusercontent.com/94672670/144594249-edd44471-dbef-4d1d-a62b-4e78b826a363.GIF)
11타수로 해결할 수 있는 방법은 다음과 같다
- G W i " esc A " esc :x
다음 사진은 해결하는 과정이다.
2. Simple replacements
---
![문제2](https://user-images.githubusercontent.com/94672670/144621521-95d60b39-9562-4bcf-9b79-e34bd4fb7b45.GIF)
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
 
