## Slice

`func append(s []T, x...T)[]T` will double the length of a slice `s`. 

If `len(s)` <`len(x...)`, `len(s)+=2`.

