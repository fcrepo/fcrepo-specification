# Fedora API Specification

The goal of this specification is to define the behaviors of [Fedora](http://fedorarepository.org/) server
implementations to facilitate interoperability with client applications. At this point version 1.0 has
been released and is available as:

* [Latest Recommendation](https://fedora.info/spec/)

## Status

This specification is a final recommendation as version 1.0.

## How To Participate

We welcome questions, comments, and pull requests.  Feel free to open an issue or post to the mailing list:

* Github Issues: https://github.com/fcrepo/fcrepo-specification/issues
* Fedora-Tech Google Group: https://groups.google.com/d/forum/fedora-tech


## Background

* The [Fedora Specification wiki](https://wiki.duraspace.org/display/FEDORAAPI/Fedora+Specification) has more
  information on the purpose and rationale of the Fedora API Specification.
* For more information on the Fedora community and the current implementation, see the [Fedora Repository
  wiki](https://wiki.duraspace.org/display/FF/Fedora+Repository+Home).


## Editorial Guidelines

* Sections for HTTP verbs should kept in this order: GET, HEAD, OPTIONS, POST, PUT, PATCH, DELETE
* HTTP verbs should be in `<code>` blocks
* Section IDs/anchors should be formatted as hyphen-separated-lower-case
