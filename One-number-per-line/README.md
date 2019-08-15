[One number per line](https://vimgolf.com/challenges/56fb2e75ccffcc0009026473)

```
|----------------------------------+--------------------------------|
| emacs                            | GVIM                           |
|----------------------------------+--------------------------------|
| C-2 C-k C-e C-k C-e C-k          | 2dd 3gJ $x                     |
| C-e <Backspace> F3               | qq F,s <CR> <Esc> k$ q         |
| M-b <Backspace> <RET>            | 8@q :w<CR>                     |
| C-p C-e F4 C-8 F4 C-x C-s        |                                |
|----------------------------------+--------------------------------|
| C-2 C-k  M-% C-q C-j <RET> <RET> | 2dd 3gJ :%s/,/\r/g <CR> :w<CR> |
| ! <Backspace> C-a M-% , <RET>    |                                |
| C-q C-j <RET> ! C-x C-s          |                                |
|----------------------------------+--------------------------------|
```




# One number per line

Just give me the numbers.

**Start file**
```
- One number per line -
-----------------------
2,3,5,7,
11,13,17,
19,23,29,
```
**End file**

```
2
3
5
7
11
13
17
19
23
29
```
