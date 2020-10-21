# Linux 常用命令

### 文件管理
```bash

# cat   查看文件内容
$ cat file.txt
 
# chmod   赋权文件
$ chmod 777 file.txt
 
# find  查找文件
$ find . -name "*.txt"

# touch 新建文件
$ touch file.txt
 
# mv  移动文件
$ mv aaa bbb  #aaa改名为bbb
$ mv mv info/file.txt logs

# rm  删除文件
$ rm -rf info/flie.txt

# cp  复制文件
$ cp -r test/ newtest
```
### 磁盘管理
```bash
# df  显示磁盘使用情况
$ df -h

# du  显示文件大小
$ du -sh test

# mkdir 新建文件夹
$ mkdir -p test/test1

