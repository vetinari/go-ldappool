ldappool - simple pooling for LDAP connections in go
====================================================

The ldappool package provides simple pooling in the style of https://gopkg.in/fatih/pool.v2, in fact
lots of code is taken from there and rewritten to match the `ldap.Client` interface in `gopkg.in/ldap.v2`

Notes
------

This is only suitable for connections which do not use `Bind()` after the initial connection setup.


