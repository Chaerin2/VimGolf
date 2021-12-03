# VimGolf
1. Add quotes to ansible playbook
---
##### 가장 마지막 줄에 있는 state:에 따옴표를 추가해주는 문제이다.
![문제1](https://user-images.githubusercontent.com/94672670/144594249-edd44471-dbef-4d1d-a62b-4e78b826a363.GIF)
위 문제를 해결하는 과정이다. (11점)
- G W i " esc A " esc :x

![문제1 과정](https://user-images.githubusercontent.com/94672670/144652809-d973360c-8134-41b4-89b2-d48fa95f51e5.gif)


2. Simple replacements
---
##### sublime과 emacs를 찾아 vim으로 교체해주는 문제이다.
![문제2](https://user-images.githubusercontent.com/94672670/144621521-95d60b39-9562-4bcf-9b79-e34bd4fb7b45.GIF)
위 문제를 해결하는 과정이다. (28점)
- :%s/sumlime\|emacs/vim/g :x

![문제 2 과정](https://user-images.githubusercontent.com/94672670/144653531-b8a5a508-9f78-41e5-9783-835901dd8a66.gif)

3. Satisfy the go linter
---
##### 4,6라인에 각각 문장을 입력해주는 문제이다.
![문제3](https://user-images.githubusercontent.com/94672670/144621537-47dc25fd-cd3d-4e5a-89da-fe6715b809ec.GIF)

4. Plotting some variables in python
---
##### 각각 abs(yn),문자교체,숫자증가를 수행하는 문제이다.
![문제4](https://user-images.githubusercontent.com/94672670/144622087-b5440491-18f3-4ea0-8c2c-27bff01e9d7a.GIF)

5. Python dataclasses
---
##### 마지막 따옴표에 문장을 추가하는 문제이다.
![문제5](https://user-images.githubusercontent.com/94672670/144622156-500c37f1-1456-4a54-887c-778828567ea2.GIF)
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
 
