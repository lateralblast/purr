![alt tag](https://raw.githubusercontent.com/lateralblast/purr/master/purr.jpg)

PURR
----

Package/Utility Removal/Remediation

Version
-------

Current version 0.0.3

Introduction
------------

This is a script designed to gather some useful system functions together,
for example remove all the old kernel packages on Ubuntu to recover disk space.

Usage
-----

To get usage/help information:

```
./purr.sh --help

Usage: purr.sh --switch [value]

switches:
--------
 --action*)
   Action to perform
 --debug)
   Enable debug mode
 --force)
   Enable force mode
 --strict)
   Enable strict mode
 --verbose)
   Enable verbos e mode
 --version|-V)
   Print version information
 --option*)
   Option to enable
 --usage*)
   Action to perform
 --help|-h)
   Print help information
```

Get usage information about options:

```
./purr.sh --usage options

Usage: purr.sh --option(s) [value]

options:
-------
debug)
  Enable debug mode
force)
  Enable force mode
yes)
  Answer yes to questions
strict)
  Enable strict mode
verbose)
  Enable verbose mode
```

Get usage information about actions:

```
./purr.sh --usage actions

Usage: purr.sh --action(s) [value]

actions:
-------
 help)
   Print actions help
 version)
   Print version
 *oldkernels)
   Remove old kernels
```

Examples
--------

Remove old kernel modules:

```
./purr.sh --action removeoldkernels
```
