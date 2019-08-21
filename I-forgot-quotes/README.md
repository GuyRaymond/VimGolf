[to solve]:https://www.vimgolf.com/challenges/5462e3f41198b80002512673

[I forgot quotes][to solve]

```
|---------------------------------------+--------------------------|
| emacs                                 | GVIM                     |
|---------------------------------------+--------------------------|
| C-M-% a.*$ <RET> "\&" <RET> ! C-x C-s | :%s/a.*$/"&"<RET>:w<RET> |
|---------------------------------------+--------------------------|
```

# I forgot quotes

Oops.

**Start file**

```
foo = a
      ab
      abc
```

**End file**

```
foo = "a"
      "ab"
      "abc"
```
