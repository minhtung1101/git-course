# Git

  ## 1. Giải thích các câu lệnh: 

- <code>git init</code>: Khởi tạo thư mục được quản lý bởi Git

- <code>git add <file_name></code>: đưa file *<file_name>* từ **Working Directory** sang **Staging**
- <code>git add .</code> : đưa tất cả file từ **Working Directory** sang **Staging**
- <code>git commit -m “message”</code>: **Tạo ra 1 phiên bản "message"** -  đưa tất cả file từ **Staging** sang **Repository**



## 2. Liệt kê các file theo từng vùng:
1. Tạo 3 file: file1, file2, file3

| WD               |    Staging     |Repository  |    
|:----------       | :----------    |:---------- |
|                  |                |            |
|                  |                |            |
|                  |                |            |
2.  <code>git init</code>: 

| WD               |    Staging     |Repository  |    
|:----------       | :----------    |:---------- |
| file1            |                |            |
| file2            |                |            |
| file3            |                |            |
3. <code> git commit -m”init project” </code>

| WD               |    Staging     |Repository  |    
|:----------       | :----------    |:---------- |
| file1            |                |            |
| file2            |                |            |
| file3            |                |            |
4. <code>git add file1</code>

| WD               |    Staging     |Repository  |    
|:----------       | :----------    |:---------- |
|                  | file1          |            |
| file2            |                |            |
| file3            |                |            |

5. <code>git commit -m”add file1”</code>

| WD               |    Staging     |Repository  |    
|:----------       | :----------    |:---------- |
|                  |                |  file1     |
| file2            |                |            |
| file3            |                |            |
6. Chạy lệnh: git add file

| WD               |    Staging     |Repository  |    
|:----------       | :----------    |:---------- |
|                  |                |  file1     |
| file2            |                |            |
| file3            |                |            |


 

