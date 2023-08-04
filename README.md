streaming-commons
=================

Common lower-level functions needed by various streaming data libraries.
Intended to be shared by libraries like conduit and pipes.

[![Build status](https://github.com/fpco/streaming-commons/actions/workflows/tests.yml/badge.svg)](https://github.com/fpco/streaming-commons/actions/workflows/tests.yml)

Dependencies
------------

One of the requirements of this package is to restrict ourselves to "core"
dependencies. The definition of core is still to be decided, but here's a
working start:

* *No* dependency on system libraries, beyond that which is required by other
  dependencies.
* Anything which ships with GHC (including `text`, `transformers`).
* `network`
* `stm`

For debate:

* Other Haskell Platform packages, especially `vector` and `attoparsec`.
