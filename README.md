

prototypeACS is the most complete TR-069 ACS available for free under the MIT License. You can download and install it, or contribute to the project! 

## Prerequisites

prototypeACS requires Java and MySQL. It has been tested to work on Java 8 and latest version of MySQL (the latter with some minor quirk in the install script).

## Social

* [Freeforums] (deprecated)

## Build it

prototypeACS is built with SBT on unix/linux systems:

```bash
$ ./mvnw test
```

Packaged to deployable zips with:

```bash
$ ./mvnw package
```

See the distribution modules target folder or the individual module target folders for deployable zip files.



## Versioning

We use SemVer for versioning.

## License

This project is licensed under the The MIT License.
