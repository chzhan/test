# test
github test
## 字体
**这是加粗的文字**
*这是倾斜的文字*`
***这是斜体加粗的文字***
~~这是加删除线的文字~~
## 引用
>这是引用的内容
>>这是引用的内容
>>>>>>>>>>这是引用的内容
## 分割线
---
----
***
*****
## 超链接
[简书](http://jianshu.com)
[百度](http://baidu.com)
## 图片
![blockchain](https://ss0.bdstatic.com/70cFvHSh_Q1YnxGkpoWK1HF6hhy/it/u=702257389,1274025419&fm=27&gp=0.jpg "区块链")
## 列表
### 无序列表
- 列表内容
+ 列表内容
* 列表内容
### 有序列表
1. 列表内容
2. 列表内容
3. 列表内容
### 列表嵌套
- 一级无序列表内容
   - 二级无序列表内容
   - 二级无序列表内容
- 一级无序列表内容
   1. 二级有序列表内容
   2. 二级有序列表内容
1. 一级有序列表内容
   - 二级无序列表内容
   - 级无序列表内容
2. 一级有序列表内容
   1. 序列表内容
   2. 序列表内容
## 表格
姓名|技能|排行
--|:--:|--:
刘备|哭|大哥
关羽|打|二哥
张飞|骂|三弟
## 代码
### 单句
`import numpy`
### 代码块
```python
import torch
torch.version
```
## 流程图
```flow st=>start: Start|past:>http://www.google.com[blank] e=>end: End:>http://www.google.com op1=>operation: get_hotel_ids|past op2=>operation: get_proxy|current sub1=>subroutine: get_proxy|current op3=>operation: save_comment|current op4=>operation: set_sentiment|current op5=>operation: set_record|current cond1=>condition: ids_remain空? cond2=>condition: proxy_list空? cond3=>condition: ids_got空? cond4=>condition: 爬取成功?? cond5=>condition: ids_remain空? io1=>inputoutput: ids-remain io2=>inputoutput: proxy_list io3=>inputoutput: ids-got st->op1(right)->io1->cond1 cond1(yes)->sub1->io2->cond2 cond2(no)->op3 cond2(yes)->sub1 cond1(no)->op3->cond4 cond4(yes)->io3->cond3 cond4(no)->io1 cond3(no)->op4 cond3(yes, right)->cond5 cond5(yes)->op5 cond5(no)->cond3 op5->e
```
















