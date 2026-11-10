# python3.10

Python 3.10.22 with pip (an older/other version beside python3): ssl, sqlite3, zlib, bz2, lzma, ctypes, readline, curses

A package for [tOS](https://github.com/Artfical/tOS), installed with `tpkg`:

```
sudo tpkg install python3.10
```

| | |
|---|---|
| Version | 3.10.22 |
| Licence | PSF-2.0 |
| Upstream | https://www.python.org |
| Needs | [`zlib`](https://github.com/Artfical/tpkg-zlib), [`openssl`](https://github.com/Artfical/tpkg-openssl), [`libffi`](https://github.com/Artfical/tpkg-libffi), [`bzip2`](https://github.com/Artfical/tpkg-bzip2), [`sqlite`](https://github.com/Artfical/tpkg-sqlite), [`readline`](https://github.com/Artfical/tpkg-readline), [`ncurses`](https://github.com/Artfical/tpkg-ncurses), [`ca-certificates`](https://github.com/Artfical/tpkg-ca-certificates) |
| Needs tOS build | 618 or newer |
| Size | 30600599 bytes (98399296 unpacked) |
| SHA-256 of the `.tpkg` | `70fbdeabf5844c305d4956dd224923d994fea274a5cf6fb0b980c82cf3995b92` |

## Commands it adds

| Command | Runs |
|---|---|
| `python3.10` | `bin/python3.10` |
| `pip3.10` | `bin/pip3.10` |
| `pydoc3.10` | `bin/pydoc3.10` |

## Download

The package file (`python3.10-3.10.22.tpkg`) and the sources it was built from are the assets of the
[v3.10.22 release](https://github.com/Artfical/tpkg-python3.10/releases/tag/v3.10.22).
Git holds only the text: `meta.json`, the licences and `NOTICE.txt` (how it was built and what was changed).

Sources in the release:
- `Python-3.10.22.tar.xz`

Check a download: `sha256sum python3.10-3.10.22.tpkg` must give the hash above.

## Signatures

Packages are signed by Artfical's package server (Ed25519) and tOS checks the signature before it installs one.
The signature is made when the server hands a package out, so it is not kept here, and the signing key is never published.
`tpkg install` is the supported way to install; a `.tpkg` taken from here has the hash above but not the server's signature.

## Licence

The package is made of other people's software, under their licences: PSF-2.0. The licence texts are in this
repository (`LICENSE*`, `UNLICENSE`), and `NOTICE.txt` says how it was built. The sources above are the
corresponding source. `meta.json` and this README are free to copy.

Package problems (build, files, versions): open an issue here. Problems in the software itself belong upstream.
Security reports: see [SECURITY.md](https://github.com/Artfical/tOS/blob/main/SECURITY.md).
