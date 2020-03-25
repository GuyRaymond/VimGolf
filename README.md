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
:cd problem_name<CR>

:e outputvim.txt<CR>

:0r input.txt<CR>
```


# Open emacs

```
M-x cd<RET> problem_name<RET>

C-x C-f outputemacs.txt<RET>

C-x i input.txt<RET>
```

