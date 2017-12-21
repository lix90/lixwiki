# Python

## 编码

字节与字符：

字节：一串二进制数据，用于存储和传输

字符：人类可阅读，用于显示

编码：字符 -&gt; 字节

解码：字节 -&gt; 字符

### Py2

Python2使用ASCII为默认编码方式

Python2有两种字符串类型：unicode和str

str：二进制字节序列

UnicodeEncodeError：unicode -&gt; str出错

UnicodeDecodeError：str -&gt; unicode出错

### Py3

Python3使用ASCII为默认编码方式

\* str

\* bytes

编码：str -&gt; bytes

解码：bytes -&gt; str

---

## Python与Hadoop交互

通过subprocess模块调用HDFS命令

https://community.hortonworks.com/articles/92321/interacting-with-hadoop-hdfs-using-python-codes.html

hdfs模块

pydoop模块

pyhdfs模块





