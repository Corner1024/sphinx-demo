.. sphinx-demo documentation master file, created by
   sphinx-quickstart on Tue Jun 16 23:37:50 2015.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to sphinx-demo's documentation!
=======================================


=======
标题
=======
标题以“==”和“--”来定义，遵从下原则：
    * 双线比单线级别高
    * 上下线比单下线级别高

======
段落
======

    段落一
    
    段落二 
段落三

======
文字
======
*斜体*  

**粗体**

``import datetime #代码样式测试`` 

以下是一段代码块：
    <input></input> ::
    
======
列表
======
列表的字符：
``* + - • ‣ ⁃``

普通列表
    * 第一列
    * 第二列
        * 第 2.1 列
        * 第 2.2 列
    * 第三列
    
    
有序列表
使用“#”来生成序列
    1. 第一条
    
    #. 第二条
        a. 第2.1项
        #. 第2.2项
    #. 第三条

====
表格
====
    表格一：
    
    基本形式
    ========
     
    `下面这种是最简单的表格形式，当然你也可以去掉表头展示。`
     
    =====  =====  =======
      A      B    A and B
    =====  =====  =======
    False  False  False
    True   False  False
    False  True   False
    True   True   True
    =====  =====  =======
     
    表内嵌入
    ========
     
    `下面这种简单表内有列表`
     
    =====  =====
    col 1  col 2
    =====  =====
    1      Second column of row 1.
    2      Second column of row 2.
           Second line of paragraph.
    3      - Second column of row 3.
     
           - Second item in bullet
             list (row 3, column 2).
    \      Row 4; column 1 will be empty.
    =====  =====
     
    表头合并
    ========
     
    `表头进行分类合并`
     
    =====  =====  ======
       Inputs     Output
    ------------  ------
      A      B    A or B
    =====  =====  ======
    False  False  False A
    True   False  True
    False  True   True
    True   True   True
    =====  =====  ======
    
    表格二：
    
    +------------------------+------------+----------+----------+
    | Header row, column 1   | Header 2   | Header 3 | Header 4 |
    | (header rows optional) |            |          |          |
    +========================+============+==========+==========+
    | body row 1, column 1   | column 2   | column 3 | column 4 |
    +------------------------+------------+----------+----------+
    | body row 2             | ...        | ...      |          |
    +------------------------+------------+----------+----------+

=======
超链接
=======

-------
超链接
-------
    以下是一个超链接：
    
    我是 链接1_
    
    .. _链接1: http://www.baidu.com
    
    http://www.baidu.com

    我这里是一个 链接_.
     
    .. _链接: http://blog.useasp.net

    这里同样是一个 `链接文本 <http://example.com/>`_ ，不需要特别设置。


块
----

下面是我们的测试代码：
 
::
 
    for i in [1,2,3,4,5]:
        print i
    # 代码块测试
 
很简单的代码块测试。

行模块：
    | 这是一个行模块1
    | 这是一个行模块1




.. toctree::
   :maxdepth: 2



Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

