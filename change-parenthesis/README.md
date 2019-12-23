[to solve]:https://www.vimgolf.com/challenges/5d2eb22d2fdc4f0009d79444

[change parenthesis][to solve]

```
|----------------------------------+---------------|
| emacs                            | GVIM          |
|----------------------------------+---------------|
| C-M-n <BS> ) C-M-p C-d ( C-x C-s | %r)F{r(:w<CR> |
|----------------------------------+---------------|
```

# change parenthesis

change the pair of braces into a pair of parentheses

**Start file**

```
this is some text {inside a pair of braces} and you need to change it into (brackets)
```

**End file**

```
this is some text (inside a pair of braces) and you need to change it into (brackets)
```
