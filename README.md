# 今天520 传点儿之前做的??

# 注意 
bigcake.py 为程序源代码（在 media\花絮 内有这些）
其中主要使用使用了turtle库
还使用了pygame库 用来播放音乐

# 演示效果在这儿
[B站演示视频](https://www.bilibili.com/video/av53114885)

# 然后我把包括源代码在内的python打包成了win下可以运行的程序
使用的打包程序是pyinstaller ，代码好像是py2的版本，大家有兴趣可以随便拿去玩。哈哈??  
就是 请插上耳机后点开哦~for mylove.exe  这个文件，放心无毒。


## 关于pyinstaller 打包的操作
py3可以使用，
```python
## 安装好pyinstaller后
pyinstaller -F file.py  # 打包成一个单一exe文件
pyinstaller -F -w file.py  # 打包成一个单一的exe文件，并且不输出cmd命令框
pyinstaller -F -w -i hello.ico file.py  # 打包成一个单一的exe文件，并且不输出cmd命令框，并且把hello.ico设为exe的图标
```

> 你可以忘记一切，但是千万不要忘记爱自己❤  2020.03.03
