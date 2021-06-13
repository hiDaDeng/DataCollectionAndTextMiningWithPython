# 常见函数

### 重点函数

- sorted(lst， ascending)
- range(start, end, step)
- enumerate(lst)
- eval(expression)
- zip(lst1, lst2..)
- map(func, lst)
- print(x)
- open(file, encoding)

### 数学相关

| 函数                        | 功能                                                         | 例子              | 运行结果    |
| --------------------------- | ------------------------------------------------------------ | ----------------- | ----------- |
| abs(a)                      | 对a取绝对值                                                  | abs(-1)           | 1           |
| max(lst)、min(lst)          | 寻找lst中的最大、最小值                                      | max([3, 2, 9])    | 9           |
| sum(lst)                    | 对lst内所有数字求和                                          | sum([3, 2, 9])    | 14          |
| ==sorted(lst， ascending)== | 对lst排序； 参数ascending为布尔值控制升降序                  | sorted([3, 2, 9]) | [2, 3, 9]   |
| ==range(start, end, step)== | 以步长step，生成从start到end的数列,默认step=1，结果取不到end | list(range(1,5))  | [1, 2, 3,4] |

### 类型转换

| 函数               | 功能                                                       | 例子                             | 运行结果                      |
| ------------------ | ---------------------------------------------------------- | -------------------------------- | ----------------------------- |
| int(string)        | 将字符串数改为整数型                                       | int('9')                         | 9                             |
| float(int/str)     | 将int或str改为浮点型                                       | float(9)、float('9')             | 9.0                           |
| list(iterable)     | 将可迭代对象为列表。这里的iterable可以为字符串，可以是列表 | list('abc')                      | ['a', 'b', 'c']               |
| ==enumerate(lst)== | 返回带有索引值的序列seq.==需要list(seq)处理后才能看到seq== | list(enumerate(['a', 'b', 'c'])) | [(0,'a'), (1, 'b'), (2, 'c')] |
| tuple(lst)         | 将lst变为tuple                                             | tuple([1,2,3])                   | (1,2,3)                       |
| set(lst)           | 将lst变为集合                                              | set([1,4,4,4,3])                 | {1,3,4}                       |

### 功能函数

| 函数                      | 功能                                                        | 例子                           | 运行结果                 |
| ------------------------- | ----------------------------------------------------------- | ------------------------------ | ------------------------ |
| ==eval(expression)==      | 执行一个表达式                                              | eval('1+1')                    | 2                        |
| ==zip(lst1,lst2...)==     | 将lst1,lst2...合并,返回zip对象。==需要list处理一下zip对象== | list(zip([1,2,3],[4,5,6]))     | [(1, 4), (2, 5), (3, 6)] |
| ==type(x)==               | 查看X的类型                                                 | type('2')                      | <class 'str'>            |
| help(x)                   | 查看X的相关信息                                             | help([1, 2])                   | Help on list object..    |
| ==map(func, lst)==        | 对lst中的每一个个体都进行func操作                           | list(map(sum, [[1,1], [1,2]])) | [2, 3]                   |
| ==print(x)==              | 打印x                                                       | print('abc')                   | Abc                      |
| ==open(file， encoding)== | 打开file文件， encoding是file的文件编码                     |                                |                          |

