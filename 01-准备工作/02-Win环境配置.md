# Win环境配置

## 一、Python安装

官网  https://www.python.org/



### 安装注意事项

- 建议不要下载最新的，建议选择一下3.7.5
- ==选择**Install Now**默认安装方式==
- 勾选**Add Python 3.x to PATH**，这样命令行可以调用python



Disable







## 二、pip配置

pip是python的命令行安装工具，可以帮我们安装第三方库。



### 2.1 更改pip镜像

为了保证安装的速度和成功率，命令行执行

```
pip config set global.index-url https://mirrors.aliyun.com/pypi/simple/ 
```



### 2.2 使用方法

```
pip install packagename
```









## 三、Jupyter notebook

### 3.1 安装

命令行执行

```
pip install jupyter
```





###  3.2 调用

命令行执行

```
jupyter notebook
```





### 3.3 常用快捷键

| jupyter内快捷键 | 功能                             |
| --------------- | -------------------------------- |
| ESC+A（ESC+B）  | 当前单元格上(下)新建一个新的Cell |
| D+D             | 删除当前单元格                   |
| Shift+Enter     | 执行单元格内的Python代码         |
| ESC+M           | 单元格由代码模式转为标记模式     |



> Markdown语法特别好用，强烈建议学习，顺便安装一个Typora软件





## 四、Tips

如果环境配置对你太难，不妨在==淘宝==搜**python环境配置**，寻找一对一远程协助