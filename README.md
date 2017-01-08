Description
===================
yaml2json 

This clone uses a pinned version of go-yaml library to support non-standard `>>:` yaml construct.

Feature
====================
* zero config.
* zero install.
* support windows,linux,Mac os,freebsd,netbsd,openbsd,plan9 platform

Usage
====================
### build
```
go get github.com/sklevenz/yaml2json # get sources and install binary to GOPATH
glide install                        # install vendor directory
go build                             # build executable
```

### shell
* find the build of you platform
* run `echo "a: 1" | yaml2json` to see result

### read from file save to file
```
cat 1.yml | yaml2json > 2.json
```

Notice
=====================
* if you do not know your mashine is 386 or amd64,you can use 386...
* master branch may rewrite history to save space.
* source branch save the history of source code.

Reference
====================
https://github.com/peter-edge/go-yaml2json
