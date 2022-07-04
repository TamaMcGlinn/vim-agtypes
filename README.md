# AgTypes

A tiny plugin defining a list of Ag commands for each filetype, so that you can search
particular types of files easier. For example:

```
command! -bang -nargs=* Agpy execute "RgRaw -g \"**/*.py\" \"\""
```

Example mappings to put into your vimrc:

```
nmap <Leader>/p :Agpy<CR>
```

