# datascience-R

Repo này ghi chép lại cách mà một Data Engineer / Data Science xử lý dữ liệu với R. Mình tự học, đang làm việc về ngành khoa học dữ liệu này. Mình bắt đầu với R, là một ngôn ngữ khá mạnh (bên cạnh Python) để xử lý dữ liệu.

Mỗi chương / phần lớn sẽ được đặt trong 1 thư mục cùng với Notebook cụ thể, cập nhật thường xuyên theo những gì mà mình học được. Một số bài viết hoàn chỉnh mà mình đúc kết được cũng có thể được đăng ở https://blog.duyetdev.com 


# 0. Getting started

1. Cài đặt [R](https://www.r-project.org/), [RStudio](https://www.rstudio.com/products/rstudio/download/).
2. [Cài đặt R trên Jupiter Notebook (Ubuntu 14.04 / 14.10 / 16.04)](http://blog.duyetdev.com/2016/11/r-tren-jupiter-notebook-ubuntu-1404.html).

## 1. [Import  data](1-import-data/import-data.ipynb)

1. `read.csv()` - Đọc data.frame từ csv
2. `stringsAsFactors = TRUE`
3. `read.delim() & read.table()` - Đọc data.frame từ bất kỳ dạng file tabular nào.
4. `summary()` - Thống kê miêu tả nhanh về data.frame
5. `file.path()` - Tạo đường dẫn đến data.
6. Lọc dữ liệu với `which.min` và `which.max`


# How to contribute

1. Fork the project on Github
2. Create a topic branch for your changes
3. Ensure that you provide documentation and test coverage for your changes (patches won’t be accepted without)
4. Create a pull request on Github (these are also a great place to start a conversation around a patch as early as possible)

# License

MIT License

Copyright (c) 2016 Van-Duyet Le

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
