# undertone

[![Build Status][gh-actions-badge]][gh-actions]
[![LFE Versions][lfe-badge]][lfe]
[![Erlang Versions][erlang-badge]][versions]
[![Tag][github-tag-badge]][github-tag]

[![Project Logo][logo]][logo-large]

*SuperCollider and OSC support in LFE*

##### Table of Contents

* [About](#about-)
* [Build](#build-)
* [Start the Project REPL](#start-the-repl-)
* [Tests](#tests-)
* [Usage](#usage-)
* [License](#license-)

## About [&#x219F;](#table-of-contents)

TBD

## Build [&#x219F;](#table-of-contents)

```shell
$ rebar3 lfe compile
```

## Start the Project REPL [&#x219F;](#table-of-contents)

```shell
$ rebar3 lfe repl
```

## Tests [&#x219F;](#table-of-contents)

```shell
$ rebar3 lfe test
```

## Usage [&#x219F;](#table-of-contents)

Start the REPL, per the above:

``` lisp
lfe> (application:start 'undertone)
ok
lfe> (undertone.server:echo "this is a test")
"this is a test"
```

## License [&#x219F;](#table-of-contents)

Apache License, Version 2.0

Copyright © 2020, Duncan McGreggor <oubiwann@gmail.com>.


[//]: ---Named-Links---

[logo]: priv/images/logo-v1.png
[logo-large]: priv/images/logo-v1-large.png
[github]: https://github.com/lfex/undertone
[gh-actions-badge]: https://github.com/lfex/undertone/workflows/ci%2Fcd/badge.svg
[gh-actions]: https://github.com/lfex/undertone/actions
[lfe]: https://github.com/rvirding/lfe
[lfe-badge]: https://img.shields.io/badge/lfe-2.0-blue.svg
[erlang-badge]: https://img.shields.io/badge/erlang-19%20to%2023-blue.svg
[versions]: https://github.com/lfex/undertone/blob/master/.github/workflows/cicd.yml
[github-tag]: https://github.com/lfex/undertone/tags
[github-tag-badge]: https://img.shields.io/github/tag/lfex/undertone.svg
[github-downloads]: https://img.shields.io/github/downloads/lfex/undertone/total.svg

