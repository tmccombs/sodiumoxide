sodiumoxide
===========

> [NaCl](http://nacl.cr.yp.to) (pronounced "salt") is a new easy-to-use high-speed software library for network communication, encryption, decryption, signatures, etc. NaCl's goal is to provide all of the core operations needed to build higher-level cryptographic tools.
> Of course, other libraries already exist for these core operations. NaCl advances the state of the art by improving security, by improving usability, and by improving speed.

> [Sodium](https://github.com/jedisct1/libsodium) is a portable, cross-compilable, installable, packageable fork of NaCl (based on the latest released upstream version nacl-20110221), with a compatible API.

This package aims to provide a type-safe and efficient Rust binding that's just
as easy to use.

Dependencies
------------

[Sodium](https://github.com/jedisct1/libsodium)

Building
--------
    rust build src/lib.rs -O

Testing
-------
    rust test src/lib.rs

Documentation
-------------
    rust doc src/lib.rs

Documentation will be generated in doc/...

Most documentation is taken from NaCl, with minor modification where the API
differs between the C and Rust versions.

Examples
--------
TBD

Join in
=======
File bugs in the issue tracker

Master git repository
    git clone https://github.com/dnaq/sodiumoxide.git

License
-------
MIT