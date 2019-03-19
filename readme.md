## Slice

- A slice contains the length, capacity and a pointer to the zeroth element of the array. Hence when a slice is passed to a function as parameter, changes made inside the function are visible outside the function too. 

- `func append(s []T, x...T)[]T` will double the length of a slice `s`.  

  ```go
  If len(s) <len(x...){
  	len(s)+=2
  }
  ```

  

