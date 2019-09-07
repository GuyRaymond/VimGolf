[to solve]:https://www.vimgolf.com/challenges/55b18bbea9c2c30d04000001

[Simple, Practical, and Common][to solve]

```
|---------------------------------+----------------------|
| emacs                           | GVIM                 |
|---------------------------------+----------------------|
| C-5 C-n C-<SPC> C-n M-w C-y C-b | :t6f1c$7<SPC>11<ESC> |
| <DEL><DEL><DEL>                 | GONew<SPC>text.<ESC> |
| 7 <SPC> 11 M-g M-g 10 <RET> C-j | <CR> :w<CR>          |
| New<SPC>Text. C-o C-x C-s       |                      |
|---------------------------------+----------------------|

```

# Simple, Practical, and Common

Simple things we do all the time should be able to be done with very few keystrokes, but sometimes I find something I need to do makes me go, "There MUST be a better way." This challenge is just a simple movement and entering text at a certain place.

**Start file**

```
*temp var1 0
*temp var2 "hi"
*temp var3 -1
*temp var4 42
*temp var5 "asdf"
*temp var6 0

Simple things we do all the time should be able to be done with very few keystrokes, but sometimes I find something I need to do makes me go, "There MUST be a better way."

This challenge is just a simple movement and entering text at a certain place.
```

**End file**

```
*temp var1 0
*temp var2 "hi"
*temp var3 -1
*temp var4 42
*temp var5 "asdf"
*temp var6 0
*temp var7 11

Simple things we do all the time should be able to be done with very few keystrokes, but sometimes I find something I need to do makes me go, "There MUST be a better way."

New text.

This challenge is just a simple movement and entering text at a certain place.
```
