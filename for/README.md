haskell-examples
================

Examples of how to use/build haskell programs

https://lotz84.github.io/haskellbyexample/ex/for

Dependencies
============

* GHC : apt-get install ghc

Running
=======

As a script:

    runhaskell src/for.hs 

Compiling:

    ghc src/for.hs -o dist/build/for
    dist/build/for

NOTE: Doesn't currently work for me, fails with a cryptic "parse error on input ‘import’" error
