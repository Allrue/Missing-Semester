# Missing-Semester 
## Theme 1: The Shell
 * **1.使用echo $SHELL命令可以查看您的 shell 是否满足要求。如果打印结果为/bin/bash或/usr/bin/zsh则是可以的。**
* **2.在 /tmp 下新建一个名为 missing 的文件夹。**
* **3.用 man 查看程序 touch 的使用手册。**
* **4.用 touch 在 missing 文件夹中新建一个叫 semester 的文件。**
*  **5.将以下内容一行一行地写入 semester 文件：**
 ```
#!/bin/sh
curl --head --silent https://missing.csail.mit.edu
```
* **6. 尝试执行这个文件**
* **7. 查看 chmod 的手册**
* **8. 使用 chmod 命令改变权限**
* **9. 使用 | 和 > ，将 semester 文件输出的最后更改日期信息，写入主目录下的 last-modified.txt 的文件中**
* **10. 写一段命令来从 /sys 中获取笔记本的电量信息，或者台式机 CPU 的温度。**
