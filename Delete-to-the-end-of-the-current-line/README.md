[to solve]:http://www.vimgolf.com/challenges/5c393a580a5a300009888e2a

[Delete to the end of the current line][to solve]

```
|-------------------+-----------|
| emacs             | GVIM      |
|-------------------+-----------|
| C-s ; C-k C-x C-s | t/D:w<CR> |
|-------------------+-----------|
```

# Delete to the end of the current line

Delete to the end of the current line, but keep the character under the cursor.

**Start file**

```
just to remove all text after; // this is a comment
```

**End file**

```
just to remove all text after;
```
