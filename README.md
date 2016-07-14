Proxy package to install haskell tool executables with lts constraints:

- ghc-mod
- stylish-haskell
- hlint
- hspec-discover

Commands:

```
$ cabal sandbox init
$ cabal update
$ cabal install --only-dependencies
```

Add below in the bash initialization file:

```
export PATH="<path to tools folder>/.cabal-sandbox/bin:$PATH"
```
