Simple bzip2 utility to pack/unpack bzip2 archives written on Limbo. Intended to run on [Inferno64NG](https://github.com/sphynkx/inferno64ng) fork, but would be work on orig. and other forks also. Compatible with GNU bzip2. "API" is same as gzip/gunzip.


## Install
Place `appl/cmd/*.b`, `appl/lib/*.b` and `man/1/bzip2` in system, modify `appl/cmd/mkfile` (as noted in repo's `appl/cmd/mkfile` `appl/lib/mkfile`)

Rebuild:
```bash
cd appl/cmd
mk install
```
