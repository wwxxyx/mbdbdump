mbdbdump
========

This tool is used to dump contents of an MBDB backup.

## Building

Just type `make` :)

Or, for an out-of-tree build:
```
mkdir build
cd build
make -f ../Makefile
```

You will need GNU make for this, and this tool depends on OpenSSL.

## Installing

`make install` will install everything to `/usr/local`. You can specify the
prefix with `make PREFIX=/usr install`.

## Usage

Take a look at the man page [here](doc/mbdbdump.1.md).
