# awesome cli
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)


An awesome list for modern drop-in replacements for common tools with sane defaults.

## grep

typical usage `grep -r PATTERN *`

typical error `grep PATTERN` will read/wait standard-input for standard input

* [ag](https://github.com/ggreer/the_silver_searcher) the silver searcher (C, Apache 2.0)
* [ripgrep](https://github.com/BurntSushi/ripgrep) (Rust, MIT)
* [ack](https://beyondgrep.com) (Perl 5, Artistic 2.0)

## ls

* [exa](https://the.exa.website/)(Rust, MIT)

## find 

* [fd](https://github.com/sharkdp/fd), Rust, MIT/Apache 2.0

## http client (curl, wget..)

* [httpie](https://github.com/jakubroztocil/httpie) (Python..)

## http server

```
python -m SimpleHTTPServer
```

or 

```
python3 -m http.server
```

## parsing with sed, awk, grep

* [jq](https://stedolan.github.io/jq/) (C, MIT) json parser

## top

* htop

## ssh

* mosh

## screen

* tmux


## collections

* GNU coreutils rewritten in [Rust](https://github.com/uutils/coreutils), multi-platform
