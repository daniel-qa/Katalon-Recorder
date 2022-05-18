```
storeEval  |  5  |  pages
storeEval  |  1  |  pageIndex
while | ${pageIndex}<${pages}
click  |  do something
storeEval | ${pageIndex} + 1 | pageIndex
endWhile
```
