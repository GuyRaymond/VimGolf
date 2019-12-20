[to solve]:http://www.vimgolf.com/challenges/4d1a8bf2b8cb3409320002c4

[Search and Replace 0][to solve]

```
|-----------------------------------+---------------------|
| emacs                             | GVIM                |
|-----------------------------------+---------------------|
| C-M-% aaa<RET> x&x<RET> ! C-x C-s | *:%s//x&x<CR>:w<CR> |
|-----------------------------------+---------------------|
|                                   |                     |
|-----------------------------------+---------------------|
```

# Search and Replace 0

Replace every instance of &#39;aaa&#39; with &#39;xaaax&#39;.

**Start file**

```
aaa
aab
abb
bbb
aaa
aab
abb
bbb
aaa
aab
abb
bbb
aaa
aab
abb
bbb
aaa
aab
abb
bbb
```

**End file**

```
xaaax
aab
abb
bbb
xaaax
aab
abb
bbb
xaaax
aab
abb
bbb
xaaax
aab
abb
bbb
xaaax
aab
abb
bbb
```
