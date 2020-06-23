# play1-jooq-stager plugin

This plugin adds [jOOQ](http://www.jooq.org/) support to Play1 applications. It is a forked from Sismics' [play-jooq](https://github.com/sismics/play-jooq), customized to the requirements of Stager.

## Installing

Add the dependency to your `dependencies.yml` file:

```
require:
    - play1-jooq-stager -> play1-jooq-stager 1.0

repositories:
    - sismics:
        type:       https
        artifact:   "https://example.org/path/to/repo/[module]-[revision].zip"
        contains:
            - play1-jooq-stager -> *

```
Then run `play dependencies --sync`

# License

This software is released under the terms of the Apache License, Version 2.0. See `LICENSE` for more
information or see <https://opensource.org/licenses/Apache-2.0>.
