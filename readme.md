## Slice

- A slice contains the length, capacity and a pointer to the zeroth element of the array. Hence when a slice is passed to a function as parameter, changes made inside the function are visible outside the function too. 

-There is a syntactic sugar which can be used to pass a slice to a variadic function. You have to suffix the slice with ... If that is done, the slice is directly passed to the function without a new slice being created.

- `func append(s []T, x...T)[]T` will double the length of a slice `s`.  

  ```go
  If len(s) <len(x...){
  	len(s)+=2
  }
  ```

  

