[to solve]:https://www.vimgolf.com/challenges/59384eb3652ee111a0000001

[From argument to object][to solve]

```
|-------------------------------------------------------------------------------+-------------------------|
| emacs                                                                         | GVIM                    |
|-------------------------------------------------------------------------------+-------------------------|
| <F3> C-a M-f <Left> M-z <SPC> C-a C-y <BS><BS> . <Down> <F4> C-3 <F4> C-x C-s | qqExhdaw0Pr.jq3@q:w<CR> |
|-------------------------------------------------------------------------------+-------------------------|
```

# From argument to object

This task typifies those programmers endure while coding. This C-family pseudocode needs a function argument to be repurposed as an object call. Simply search and replace? Repeat a pattern of edits?

**Start file**

```
organize(cupboard, 3, 2);
prioritize(bureau, 8, 7);
realize(bannister, 4, 4);
moralize(railing, 3,9);
```

**End file**

```
cupboard.organize(3, 2);
bureau.prioritize(8, 7);
bannister.realize(4, 4);
railing.moralize(3,9);
```
