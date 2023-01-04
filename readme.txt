https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.html
Pandas.DataFrame用法

https://zhuanlan.zhihu.com/p/111691682
csv和pickle区别

https://support.i-search.com.cn/article/1544801257653
pandas全面用法

https://pandas.pydata.org/pandas-docs/stable/user_guide/options.html
https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.add.html、
pandas用法

https://kknews.cc/digital/m9vjxvg.html
pandas Option设置

https://zhuanlan.zhihu.com/p/83410946
方差，标准差，均方差的区别

https://www.cnblogs.com/fuyudata/p/13616386.html
数据基础学习

https://www.cjavapy.com/article/385/
pandas学习

https://www.cbedai.net/u011630575/
人工智能教程

https://careerfoundry.com/en/blog/data-analytics/what-is-a-pivot-table/
数据挖掘

axis = 0 代表对横轴操作，也就是第0轴；
axis = 1 代表对纵轴操作，也就是第1轴；
https://blog.csdn.net/yaoqi_isee/article/details/77714570
axis的含义

https://blog.csdn.net/qianwenhong/article/details/41414809
arange()函数的用法

https://cloud.tencent.com/developer/article/1768311
https://www.cnblogs.com/massquantity/p/8908859.html
pandas和numpy中where的应用

https://blog.csdn.net/weixin_44241793/article/details/126280437?spm=1001.2101.3001.6661.1&utm_medium=distribute.pc_relevant_t0.none-task-blog-2%7Edefault%7EYuanLiJiHua%7EPosition-1-126280437-blog-81411257.pc_relevant_3mothn_strategy_and_data_recovery&depth_1-utm_source=distribute.pc_relevant_t0.none-task-blog-2%7Edefault%7EYuanLiJiHua%7EPosition-1-126280437-blog-81411257.pc_relevant_3mothn_strategy_and_data_recovery&utm_relevant_index=1
python 数据分析函数汇总

https://blog.csdn.net/W_weiying/article/details/81411257
loc和iloc用法

https://blog.csdn.net/W_weiying/article/details/84626260
drop函数用法

https://zhuanlan.zhihu.com/p/116884554
drop_duplicates去重用法

https://blog.csdn.net/qq_20141867/article/details/103683758
https://www.delftstack.com/zh/howto/numpy/python-numpy-mode/
numpy求众数

https://blog.csdn.net/qq_42665335/article/details/81177699
pandas.value_counts用法

https://blog.csdn.net/weixin_38605247/article/details/78736417
pandas interrows()用法

https://zhuanlan.zhihu.com/p/69224745
pandas.concat()用法

https://zhuanlan.zhihu.com/p/113150848
list和numpy一维数组区别

https://zhuanlan.zhihu.com/p/366934271
https://www.cnblogs.com/alivinfer/p/13339552.html
type(),dtype,astype()用法的区别


https://blog.csdn.net/lvbu89757/article/details/97891822?spm=1001.2101.3001.6661.1&utm_medium=distribute.pc_relevant_t0.none-task-blog-2%7Edefault%7ECTRLIST%7ERate-1-97891822-blog-103157725.pc_relevant_3mothn_strategy_recovery&depth_1-utm_source=distribute.pc_relevant_t0.none-task-blog-2%7Edefault%7ECTRLIST%7ERate-1-97891822-blog-103157725.pc_relevant_3mothn_strategy_recovery&utm_relevant_index=1
numpy数组的增加，删除，插入，合并concatenate

https://www.cnblogs.com/wodexk/p/10316793.html
pandas数据的更改和插入列
concat和loc/iloc可以对pandas进行增加，拼接列

https://www.runoob.com/numpy/numpy-indexing-and-slicing.html
numpy切片

pd.merge可以jointure两个列表
df3 = pd.merge(df1, df2, left_on= "employee", right_on= "emp_name")
两个表名字不同
pd.merge(df6, df2, how="left")
df6表中不存在一列如何保存
两个表中列的名称不同，用left_on和right_on名称来指定
两个表以行来合并，用left_index和right_index为true来执行
https://zhuanlan.zhihu.com/p/132579724
numpy.merge()用法
https://geek-docs.com/pandas/pandas-data-process/pandas-merger-merge.html
pandas.merge()用法/pandas教程

https://zhuanlan.zhihu.com/p/33270402
https://blog.csdn.net/weixin_41558411/article/details/115582012
matplotlib画图

https://zhuanlan.zhihu.com/p/133130001
聚合方法size()和count()
size跟count的区别： size计数时包含NaN值，而count不包含NaN值

https://blog.csdn.net/MsSpark/article/details/83154128
sort_values()用法：默认ascending=True


pandas 中 inplace 参数在很多函数中都会有，它的作用是：是否在原对象基础上进行修改。
​ inplace = True：不创建新的对象，直接对原始对象进行修改；

​ inplace = False：对数据进行修改，创建并返回新的对象承载其修改结果。



Markdown 备忘单 (Watson Studio)
上次更新时间: 2021-04-14

本文说明如何在 Jupyter Notebook 中编排 Markdown 单元格的格式。

标题：使用 # 后跟空格来表示 Notebook 标题和小节标题：

# 标题
## 主标题
### 副标题
#### 第 4 级副标题

强调：请使用以下代码：粗体：__string__ 或 **string**；斜体：_string_ 或 *string*；删除线：~~string~~

数学符号：请使用以下代码：$ mathematical symbols $

等宽字体：将文本括在反单引号 (`) 内。等宽字体用于表示文件路径和文件名，以及表示用户输入的文本或用户看到的消息文本。

换行符：有时，Markdown 无法在需要换行的位置换行。请在行尾放置两个空格，或者使用以下代码进行手动换行：<br>

缩进引用：请使用大于号 (> )，后跟空格，然后输入文本。该文本会缩进，其左侧有一条灰色的水平线，直至下一个回车符为止。

项目符号：请使用短划线后跟空格 (- )，或者使用空格、短划线和空格 ( - )，以创建圆形项目符号。要创建子项目符号，请使用跳格后跟短划线和空格。此外，还可以使用星号代替短划线，其作用相同。

编号列表：以 1. 开头，后跟空格，再后跟文本。按 Enter 键，编号会自动进行。以某数字和句点作为每一行的开头，后跟空格。按 Tab 键可缩进，从而生成子编号。

Notebook 中的图形：将图像拖放到 Markdown 单元格即可将其附加到 Notebook 中。要将图像添加到其他单元格类型，请通过以下代码使用 Web 上的图形（将 url/name 替换为图像的完整 URL 和名称）：<img src="url/filename.gif" alt="备用文本" title="标题文本" />

几何形状：请将以下代码与 UTF-8 几何形状所列的十进制或十六进制引用号配合使用：&#reference_number;

水平线：请使用三个星号：***

nos_pokemon.shape
