In R cells in the Atomic Learning platform, variables defined in one cell persist and can be accessed in subsequent cells. This allows for code to be split up into digestible chunks while maintaining the variables and the data they reference across the page.

For instance, we can create a variable in a cell:

```r-cell
x = 10
```

and this will be available for use in subsequent cells:

```r-cell
y = x + 5
print(x)
print(y)
```

Try running the cells above in the order they appear.

Variables and all data they reference will be reset if the page if reloaded. Try reloading the page and running the second cell again. You should see an error indicating that `x`{.r} is not defined.
