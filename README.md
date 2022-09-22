# Scheme Interpreter
Based on [Write Yourself a Scheme in 48 Hours](https://en.wikibooks.org/wiki/Write_Yourself_a_Scheme_in_48_Hours)

## Compilation
```
ghc -package parsec -o lisp src/Main.hs
```

## Execution
### from command line (activate REPL):
```
./lisp
```

### from REPL
```
Lisp>>> (+ 2 3)
5
```

### Load standard library:
```
Lisp>>> (load "stdlib.scm")
```
