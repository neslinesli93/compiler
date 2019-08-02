# The Elm Compiler

Learn about the Elm programming language at [elm-lang.org](http://elm-lang.org/).

## Build the compiler

1) Create a container with GHC:

```bash
$ docker run -v $FULL_PATH_TO_COMPILER:/elm -it haskell:8.4.4 bash
```

2) Enter the `elm/` folder and run:

```
# cabal update
# cabal new-build
```

## Install

Follow [these instructions][installer]!

 [installer]: https://guide.elm-lang.org/install.html

## Help

If you are stuck, ask around on [the Elm slack channel][slack]. Folks are friendly and happy to help with questions!

[slack]: http://elmlang.herokuapp.com/
