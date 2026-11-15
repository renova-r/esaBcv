# esaBcv 1.2.1.1.9001

Renova release, based on CRAN esaBcv 1.2.1.1 (archived on CRAN 2024-05-14).

- `R/ESA_BCV.R`: three `if()` conditions now test `class(x)[1L] == "try-error"` instead of `class(x) == "try-error"`.
- `man/esaBcv_package.Rd`: the invalid alias `esaBcv_package-package` is replaced by `esaBcv-package` (documentation only).
- `DESCRIPTION`: trailing whitespace removed from the end of `Description` (metadata only).
- `DESCRIPTION`: `Version` set to `1.2.1.1.9001`; "Compatibility updates by Renova." appended to `Description`.
- The stale `MD5` file was removed.
- `COPYING` (GNU GPL version 2 text) was added; the `License` field is unchanged.
- `README.md` was added and `.Rbuildignore` keeps `README.md` and `NEWS.md` out of the built package.
