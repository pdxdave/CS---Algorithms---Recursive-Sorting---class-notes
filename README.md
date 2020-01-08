# CS---Algorithms---Recursive-Sorting---class-notes
CS---Algorithms---Recursive-Sorting---class-notes


#### A basic recursive function
```
  0(n) // OK
  
  def n_demo(n):
    print(n)
    
    // base case
    if n == 0:
      return
    n_demo(n-1)
```

How to analyze a recursive function?     
Q: How many times do we recurse?

```
0(2^n) // Terrible

def two_n_demo(n):
  print(n)
  if n == 0:
    return
  two_n_demo(n-1)
  two_n_demo(n-1)
```

Another example...

```
divide_n_demo(n):
  print(n)
  if n <= 1
    return
  divide_n_demo(n/2)
```
