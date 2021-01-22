# cdlin的博客

##  1 Windows命令(DOS)

#### 1.1 打开CMD
```
Windows+r
```
#### 1.2 切换盘符
```
c: d:
```
#### 1.3 查看相关指示/帮助
```
xxx/?
```
#### 1.4 显示当前路径下的文件和文件夹 dir

|    参数    | 含义                                                  |
| :--------: | :---------------------------------------------------- |
|   **/?**   | **查看相关指示**                                      |
|   **/s**   | **显示指定目录和所有子目录中的文件。ctrl+c 退出显示** |
|   **/p**   | **在每个信息屏幕后暂停**                              |
|  **/p/s**  | **一页一页的看，ctrl+c 退出显示**                     |
|   **/w**   | **用宽列表格式显示**                                  |
|   **/o**   | **用分类顺序列出文件，默认文件夹在前，文件在后**      |
| **>a.txt** | **把查找出的文件信息写入到a.txt中。**                 |

#### 1.5 cd

```
cd进入到，后面加文件夹或文件名；
cd .当前路径；
cd ..返回上一级；cd/返回盘符
```

#### 1.6 **创建文件夹** md

```
创建三个文件夹 md a b c;
创建多层文件夹 md d:\a\a\a
```

#### 1.7 **复制文件**

```
copy a.txt e\a
```

#### 1.8 **创建新文件**

```
copy nul a.txt
```

#### 1.9 **创建新文件并写入信息并保存**

```
copy con b.txt
shutdown -s -t 600
ctrl+z
```

#### 1.10 **更改名称**

```
rename oldFullName newFullName 
ren oldFullName newFullName
```

#### 1.11 **删除文件**

```
del a.txt
```

#### 1.12 **删除文件夹**

```
rd e\a 只删除了a文件夹
```

#### 1.13 **修改名字**

```
ren 旧文件 新文件
```

#### 1.14 **关机**

```
shutdown - s 关闭本地计算机
shutdown -s -t 600 十分钟关机（不写时间不好用）
shutdown –a 取消关机
```

#### 1.15 **查看本机 ip **

```
ipconfig
```

#### 1.16 **判断是否可以连接某一个网址**

```
ping xxx(ip地址或网站)
```
