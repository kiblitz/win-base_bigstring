Original lib is not compatible with some Windows linkers due to missing `memmem` function

---

To use this fix, pin `base_bigstring` to a clone of this repo.
```
$ opam pin add base_bigstring .
```
