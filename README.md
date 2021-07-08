<img src="https://cdn.rawgit.com/oh-my-fish/oh-my-fish/e4f1c2e0219a17e2c748b824004c8d0b38055c16/docs/logo.svg" align="left" width="144px" height="144px"/>

#### ossl.fish

> A plugin for the [fish-shell](https://fishshell.com).

[![MIT License](https://img.shields.io/badge/license-MIT-007EC7.svg?style=flat-square)](/LICENSE)
[![Fish Shell Version](https://img.shields.io/badge/fish-v3.3.1-blue.svg?style=flat-square)](https://fishshell.com)

<br/>

This plugin installs fish function wrappers around `openssl` to ease day to day operations on TLS certificates.

## Install

With [fisher]

```fish
$ fisher install iouns/ossl.fish
```

## Usage

Print a TLS certificate:

```fish
$ ossl-print-crt mycertificatefile.pem
```

## Available commands

| Functions         |               Goal               |
| ----------------- | :------------------------------: |
| ossl-print-key    |      Print rsa private key       |
| ossl-print-csr    |  Print certificate csr centered  |
| ossl-print-cr     |      Print x509 certificate      |
| ossl-print-pkcs12 |           Print pkcs12           |
| ossl-modulus-crt  |    Print certificate modulus     |
| ossl-modulus-key  |        Print key modulus         |
| ossl-modulus-csr  |        Print csr modulus         |
| ossl-sclient      | Try to s_client connect a server |

# License

[MIT][mit] © [Iouns](https://github.com/iouns)

[mit]: https://opensource.org/licenses/MIT
[omf-link]: https://www.github.com/oh-my-fish/oh-my-fish
[fisher]: https://github.com/jorgebucaran/fisher
[license-badge]: https://img.shields.io/badge/license-MIT-007EC7.svg?style=flat-square
