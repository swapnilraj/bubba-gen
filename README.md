# bubba-gen

Generates strings of the from bubbbbbbbbba, using a context-free grammar
so that [@bubba](https://github.com/bubba) doesn't need to think when ze wants
a new username.

## Prerequisites

* prolog interpreter

## How to run?

``` shell
  swipl -s bubba.pdb

  ?- s(L, []).
  L = [bu, ba] ;
  L = [bu, b, ba] ;
  L = [bu, b, b, ba] ;
  L = [bu, b, b, b, ba] ;
  L = [bu, b, b, b, b, ba] .
```

## Screenshot
