# awesome cli
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)


An awesome list for modern drop-in replacements for common tools with sane defaults.

Commands such as `netstat -tulpen`, `ps aux` or `ls -lah` are in your muscle memory, because you always forget what the individual parameters stand for? You get confused with inconsistencies between`du . -h --max-depth 1` and `find -name "CMake*" -maxdepth 2 -type f -exec grep -i "Debug" {} \;`. Are you tired of searching how to do simple things with your tool on [StackExchange](https://unix.stackexchange.com/a/12904) in general? This list is for you.
Also ❤ for speed.

## grep

typical usage `grep -r PATTERN *`. This will print results in `.git` or search for files in `.gitignore` which is cumbersome in git repositories.

`grep PATTERN` will read/wait standard-input for standard input.

### ripgrep
[ripgrep](https://github.com/BurntSushi/ripgrep) (Rust, MIT)

```bash
$ rg awesome
README.md
1:# awesome cli
2:[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
5:An awesome list for modern drop-in replacements for common tools with sane defaults.
```

### ag
[ag](https://github.com/ggreer/the_silver_searcher) the silver searcher (C, Apache 2.0)
```bash
$ ag awesome
README.md
1:# awesome cli
2:[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
5:An awesome list for modern drop-in replacements for common tools with sane defaults.
```

### others
* [ack](https://beyondgrep.com) (Perl 5, Artistic 2.0)


## cat
### bat
[bat](https://github.com/sharkdp/bat)

cat/less with line number, colors and syntax highlighting.

```bash
──────┬────────────────────────────────────────────────────────────────────────
       │ File: README.md
───────┼────────────────────────────────────────────────────────────────────────
   1   │ # awesome cli
   2   │ [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
   3   │ 
   4   │ 
```

## ls

### [exa](https://the.exa.website/) (Rust, MIT)

```bash
$ exa -lT
drwxr-xr-x    - root  2 Jul 11:45 .
.rw-r--r-- 6,8k root 12 Jun 18:09 ├── bounds.s
lrwxrwxrwx   40 root 12 Jun 18:09 ├── bpf -> ../../linux-headers-4.15.0-24/kernel/bpf
lrwxrwxrwx   43 root 12 Jun 18:09 ├── cgroup -> ../../linux-headers-4.15.0-24/kernel/cgroup
lrwxrwxrwx   42 root 12 Jun 18:09 ├── debug -> ../../linux-headers-4.15.0-24/kernel/debug
```

## find 

* [fd](https://github.com/sharkdp/fd) (Rust, MIT/Apache 2.0)

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
