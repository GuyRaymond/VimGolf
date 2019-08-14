# VimGolf
Solve problems from https://vimgolf.com/ with gvim and emacs

# Start solving a problem

```
cd vimgolf

mkdir problem_name

cd problem_name

create file <input.txt> with the input from VimGolf

create file <output.txt> with the output from VimGolf
```

# Open gvim
```
:cd problem_name

:e outputvim.txt

:r input.txt

:1d
```


# Open emacs

```
C-x d problem_name

C-x C-f outputemacs.txt

C-x i input.txt
```
