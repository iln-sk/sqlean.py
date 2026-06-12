# conda-forge patches and files

This directory contains files derived from the conda-forge
`sqlean.py-feedstock` repository.

Source:
https://github.com/conda-forge/sqlean.py-feedstock

Included files:

- `patches/0001-remove-sqlean-ipaddr-c-from-win.patch`
- `test_windirent.h`

These files are included to reproduce the Windows build fixes used by
conda-forge for `sqlean.py`.

`patches/0002.1-fix-constants-in-time-c.patch` and `patches/0002.2-fix-constants-in-duration-c.patch` is derived from
conda-forge's `0002-fix-constans-in-sqlean-time-c.patch`.

These patch was adjusted by this fork's Makefile from sqlean 0.27.4 sources.

License:
BSD-3-Clause. See `LICENSE.txt` in this directory.
