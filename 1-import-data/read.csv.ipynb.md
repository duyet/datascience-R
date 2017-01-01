
`utils` package tự động load khi `R` session khởi động, bạn có thể import **CSV files** bằng hàm `read.csv()`.


# Goal 
1. Sử dụng `read.csv()` để import file `"swimming_pools.csv"` thành data frame `pools`.
2. In cấu trúc data frame bằng hàm `str()`.


```python
pools <- read.csv('swimming_pools.csv')
```


```python
str(pools)
```
