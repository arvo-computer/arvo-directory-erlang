SYNRC 🌐 LDAP
=============
[![Hex pm](http://img.shields.io/hexpm/v/ldap.svg?style=flat)](https://hex.pm/packages/ldap)

SYNRC LDAP is a high-performance IETF 2849 3296 3671-3673 3866 4510-4518 4522 4525 4526 4929 5480
compatible LDAP directory server with SQLITE, LMDB, MONGODB backends.

![ldap-shaders](https://github.com/synrc/ldap/assets/144776/19f35667-9a0e-4e43-8524-b6ccdf6c21b7)

Run
---

```
$ mix deps.get
$ iex -S mix
Erlang/OTP 24 [erts-12.2.1] [source] [64-bit]
              [smp:12:12] [ds:12:12:10] [async-threads:1] [jit]

Interactive Elixir (1.12.2) - press Ctrl+C to exit (type h() ENTER for help)
> :application.which_applications
[
  {:ldap, 'LDAP Directory and Identity Server', '8.6.0'},
  {:eldap, 'Ldap api', '1.2.9'},
  {:mix, 'mix', '1.12.2'},
  {:iex, 'iex', '1.12.2'},
  {:elixir, 'elixir', '1.12.2'},
  {:compiler, 'ERTS  CXC 138 10', '8.0.4'},
  {:stdlib, 'ERTS  CXC 138 10', '3.17'},
  {:kernel, 'ERTS  CXC 138 10', '8.2'}
]
```

Mentions
--------

* <a href="https://tonpa.guru/stream/2010/2010-10-18 LDAP.htm">2010-10-18 LDAP</a><br>
* <a href="https://tonpa.guru/stream/2023/2023-07-20 LDAP Compliance.htm">2023-07-20 LDAP Compliance</a><br>
* <a href="https://ldap.erp.uno">2023-07-25 SYNRC LDAP 2.0</a><br>

Credits
-------

* Maxim Sokhatsky
