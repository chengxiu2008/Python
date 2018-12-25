# Python
This is a reference for daily work with python
## Structure Data
- Dict
  - dict = {'key1':'valuel1', 'key2':'value2'}
  - **sorted**: 存储无序，可以用sorted函数输有序输出
  - **items**: 迭代字典键值对 for k,v in dict.items(): print(k, v)
  - 可修改. dict['k'] = new_value
  - keyerror: use **in** or **not in** to avoid keyerror.
  - **setdefault**: better way to avoid keyerror. dict.setdefault(key, default_value)
- Set
  - 没有重复，无序存储。vowels = set('aoeiu')， vowels = {'a', 'o', 'e', 'i', 'u'}
  - 并集union: word = 'hello', u = vowels.union(word). 每个集合的不同元素的集合，且不重复。
  - 差集difference: d = vowels.difference(word). 在vowels中不在word中。
  - 交集intersection: i = vowels.intersection(word). 即在vowels中也在word中。
  - 可修改。 u.add('p'), u.remove('p')
- Tuple
  - 不可修改的列表。vowels = ('a', 'o', 'e', 'i', 'u')
  - 只有一个对象的元组. t = ('python',) 逗号是必须的，否则会被看作一个字符串，而不是元组。
- 嵌套字典（也就是表）
  - 访问某个值：people['ford'] = {'Name':'Ford', 'Gender':'Male'}, people['ford']['Name']
  - 漂亮打印：pprint(pretty print): import pprint, pprint.pprint(people)
## Code reuse
- Function
  - def, return, docstring(三重引号包围的字符串）. help(functionname) will show the docstring.
  - PEP: Python Enahncement Protocol。 Python增强协议，python代码的最佳实践。https://www.python.org/dev/peps/
  - 安装pytest模块和pep8模块，然后检测代码是否符合PEP 8标准
  - 位置赋值和关键字赋值
- Module
  - 解释器会在3个主要位置搜索模块：
    - 你的当前工作目录
    - 你的解释器的site-packages位置
    - 标准库位置
- 复制还是引用
  - 按值参数传递：传递的是该变量的一个副本，无论在函数中怎么改变该参数，原变量都不会变。
  - 按引用参数传递： 传递的是该变量的一个别名，会维护该变量的一个链接，在函数中改变该别名，原变量也会改变
  - Python：函数参数语义即支持按值调用也支持按引用调用。可以看成是对象引用。
    - 如果变量指示一个可变的值，就按引用调用语义。
    - 如果变量指示一个不可变得类型，就按值调用语义。
## Web
- Flask: light web应用框架, python的第三方模块。 
- Django: python web 框架之母
- \_\_name__: dunder name。python解释器维护的值， 在程序中的任何地方使用这个值时，都会设置为当前活动模块的名字。
- @：decorator，函数修饰符。可以调整一个现有函数的行为，而无需修改这个函数的代码。



