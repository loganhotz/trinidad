# trinidad beamer template

a `Beamer` template based almost entirely on the built-in Singapore theme

### installation
to make this (or any other custom beamer template) globally available on your machine, run
the following command in your terminal:
```shell
>>> tlmgr conf | grep "TEXMFHOME"
```
this will return `TEXMFHOME=path/to/somewhere/texmf`. in the `./somewhere/` directory,
create the `texmf` directory if need be. at `texmf/tex/latex/themes/beamer`, place the
custom beamer template files. of course, some or all of those directories may need to be
created as well.
