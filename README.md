Original lib is not compatible with some Windows linkers due to missing `memmem` function

---

To use this fix, pin `base_bigstring` to this repo
```
$ opam pin add base_bigstring git+https://github.com/kiblitz/win-base_bigstring#v0.17
```
Alternatively, pin it to a clone of this repo.
```
$ opam pin add base_bigstring .
```
