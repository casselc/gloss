# gloss [![Clojure CI](https://github.com/casselc/gloss/actions/workflows/test.yml/badge.svg)](https://github.com/casselc/gloss/actions/workflows/test.yml)

Gloss is a byte-format DSL.It can turn complicated byte formats into Clojure data structures, allowing
for easy use of custom network protocols and C libraries.  It can also turn Clojure data structures into
compact byte representations, allowing for efficient use of bandwidth and disk.

Read more about it in [the wiki](https://github.com/ztellman/gloss/wiki).

## note

This is a fork w/ minor type-hinting updates, updated dependencies, and conversion to deps.edn.

## usage

To add as a dependency to your `deps.edn`:

```clj
{:deps
 {io.github.casselc/gloss {:git/tag "0.0.0-SNAPSHOT" :git/sha "37a9f46"}}}
```

## documentation

The full API documentation can be found [here](http://aleph.io/codox/gloss/).

## license

Copyright © 2014 Zach Tellman

Distributed under the Eclipse Public License, which is also used by Clojure.
