# CS---Algorithms---Recursive-Sorting---class-notes
CS---Algorithms---Recursive-Sorting---class-notes


#### A basic recursive function
```
  0(n)
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
def two_n_demo(n):
  print(n)
  if n == 0:
    return
  n_demo(n-1)
  n_demo(n-1)
```
