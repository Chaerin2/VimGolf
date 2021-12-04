# VimGolf
1. Add quotes to ansible playbook
---

##### 가장 마지막 줄에 있는 state:에 따옴표를 추가해주는 문제이다.
![문제1](https://user-images.githubusercontent.com/94672670/144594249-edd44471-dbef-4d1d-a62b-4e78b826a363.GIF)

## keystrokes (11점)
- LWi"<Esc>A"<Esc>:x<CR>

![문제1 과정](https://user-images.githubusercontent.com/94672670/144652809-d973360c-8134-41b4-89b2-d48fa95f51e5.gif)

2. Simple replacements
---
  
##### sublime과 emacs를 찾아 vim으로 교체해주는 문제이다.
![문제2](https://user-images.githubusercontent.com/94672670/144621521-95d60b39-9562-4bcf-9b79-e34bd4fb7b45.GIF)

keystrokes (28점)

- :%s/sublime\|emacs/vim/g<CR>:x<CR>

![문제 2 과정](https://user-images.githubusercontent.com/94672670/144653531-b8a5a508-9f78-41e5-9783-835901dd8a66.gif)

3. Satisfy the go linter
---
  
##### 4,6라인에 각각 문장을 입력해주는 문제이다.
![문제3](https://user-images.githubusercontent.com/94672670/144621537-47dc25fd-cd3d-4e5a-89da-fe6715b809ec.GIF)

keystrokes (35점)
- 4GywO// <Esc>paTODO<Esc>6GywO// <Esc>paTODO<Esc>:x<CR>

![문제 3번 과정](https://user-images.githubusercontent.com/94672670/144716876-528fa767-a0f5-40d7-ad67-8fb4a23f3f54.gif)


4. Plotting some variables in python
---
  
각각 abs(yn),문자교체,숫자증가를 수행하는 문제이다.
![문제4](https://user-images.githubusercontent.com/94672670/144622087-b5440491-18f3-4ea0-8c2c-27bff01e9d7a.GIF)

keystrokes (80점)
- :%s/y1/abs(y1)/g<CR>:3s/1/2/g<CR>:3s/k/b/g<CR>:4s/1/3/g<CR>:4s/k/r/g<CR>:5s/1/4/g<CR>:5s/k/g/g<CR>:x<CR>

![문제 4번 과정](https://user-images.githubusercontent.com/94672670/144716883-242992dc-4755-4a2e-a7ea-18431177fb64.gif)


5. Python dataclasses
---
  
##### 마지막 따옴표에 문장을 추가하는 문제이다.
![문제5](https://user-images.githubusercontent.com/94672670/144622156-500c37f1-1456-4a54-887c-778828567ea2.GIF)

keystrokes (32점)
- L<BS>istudent_id,name,age,score<Esc>:x<CR>
  
![문제 5번 과정](https://user-images.githubusercontent.com/94672670/144716884-ec8de1d4-e3b5-48b3-8113-19541ce319ba.gif)
