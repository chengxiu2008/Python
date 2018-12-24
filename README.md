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
  - 没有重复，无序存储。vowels = set('aoeiu')
  - 并集union: word = 'hello', u = vowels.union(word). 每个集合的不同元素的集合，且不重复。
  - 差集difference: d = vowels.difference(word). 在vowels中不在word中。
  - 交集intersection: i = vowels.intersection(word). 即在vowels中也在word中。
  - 可修改。 u.add('p'), u.remove('p')
- Tuple
  - 不可修改的列表。vowels = ('a', 'o', 'e', 'i', 'u')
  - 只有一个对象的元组. t = ('python',) 逗号是必须的，否则会被看作一个字符串，而不是元组。
  

