issue-duplicate_symbol
======================

Fixed in Go 1.8
https://github.com/golang/go/issues/8756

Show an example with Duplicate Symbol issue.

### Error Message:

`##PATH##\Go\pkg\windows_386/github.com/mattn/go-sqlite3.a
(_all.o): duplicate symbol reference: __moddi3 in both github.com/d2g/unqlitego(
.text) and github.com/mattn/go-sqlite3(.text)`

### Enviroment:
go version go1.3.1 windows/386
