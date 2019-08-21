[to solve]:http://www.vimgolf.com/challenges/540629666a1e4000020d9e5a

[Put hyphens everywhere.][to solve]

```
|-------------------------------------+--------------------------------|
| emacs                               | GVIM                           |
|-------------------------------------+--------------------------------|
| C-M-% . <RET> -\& <RET> ! - C-x C-s | :s/./-&/g<CR> A - <ESC> :w<CR> |
|-------------------------------------+--------------------------------|
```

# Put hyphens everywhere.

Put hyphens everywhere.

**Start file**
```
abcdefghijklm
```

**End file**
```
-a-b-c-d-e-f-g-h-i-j-k-l-m-
```
