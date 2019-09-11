[to solve]:http://www.vimgolf.com/challenges/50f3c2d55c891f0002000002

[Word frequency alignment][to solve]

```
|------------------------------------------------------------+----------------|
| emacs                                                      | GVIM           |
|------------------------------------------------------------+----------------|
| M-m C-n C-<SPC> C-10 C-n C-e M-% <SPC><RET><RET> ! C-x C-s | C-V G$< :w<CR> |
|------------------------------------------------------------+----------------|
|                                                            | C-V ) < :w<CR> |
|------------------------------------------------------------+----------------|
|                                                            | C-V } < :w<CR> |
|------------------------------------------------------------+----------------|
```

# Word frequency alignment

You've got to align the second column, but the spacing is inconvenient and there are nasty TABs in the way. If you're a "real Vim ninja," this could be very quick indeed...

**Start file**

```
     align here
the        56271872
of        33950064
and        29944184
to        25956096
in        17420636
I        11764797
that        11073318
was        10078245
his        8799755
he        8397205
it        8058110
```

**End file**

```
     align here
the  56271872
of   33950064
and  29944184
to   25956096
in   17420636
I    11764797
that 11073318
was  10078245
his  8799755
he   8397205
it   8058110
```
