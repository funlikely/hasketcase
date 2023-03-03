# hasketcase

## Steps to run

One can use GHCI to :load an app/ .hs file like:
```
hasketcase\app> ghci
ghci> :load Main.hs
[1 of 1] Compiling Main             ( Main.hs, interpreted )
Ok, one module loaded.
ghci> main
Hello World
ghci>
```

Or you can debug using [Haskell GHCi Debug Adapter Phoityne]

And the "haskell(stack)" run configuration, which will use the

stack.yaml file, that specifies a ghci version of 9.2.5.


## Venting:

Seriously, reddit and stackoverflow are full of people talking about how difficult even getting haskell to run is. And apparently its harder on Windows. And even though it should not be difficult to get VS Code, the extensions, the ghc, the haskell-language-server, the stack, the ghcup, the haskell-debug-adapter, the cabal, the everything installed,

it sometimes seems to be,

for some people.

This is just an attempt to get it running on Windows, and be able to write some code and debug with breakpoints.

Eventually this may turn into a serious language learning endeavor.


