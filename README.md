# dict

Get dictionary definition from the command line

## Install
Add to a bin directory found in the PATH envar e.g. ~/.local/bin

Make it executable
```bash
chmod +x /path/to/dict
```

Caches the definition for each request, so the cache dir must be created.
A cache filename is the MD5 checksum generated from the word argument.
```bash
mkdir -p ~/.local/share/dict
```

## Usage
```bash
$ dict <word>
$ dict python    
Python

        1. <language> A simple, high-level interpreted language by
        Guido van Rossum <guido@cwi.nl>, 1991.  Python combines ideas
        from ABC, C, Modula-3 and Icon.  It bridges the gap
        between C and shell programming, making it suitable for
        rapid prototyping or as an extension language for C
        applications.  It is object-oriented and supports packages,
        modules, classes, user-defined exceptions, a good C
        interface, dynamic loading of C modules and has no arbitrary
        restrictions.
        [REDACT]
```

