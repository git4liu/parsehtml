由于htmlcxx 只能解析出来一个DOM树，但是很多情况下我并不需要整个树，况且也太占用内存

在html文件夹下添加了
ParseHtmlExtract.cpp
ParseHtmlExtract.h
HtmlExtract.h

三个文件，其中 HtmlExtract.h 为模型
其余两个为操作类

按照HtmlExtrat.h 中描述的 字段提取网页的特征


本程序为 htmlcxx0.85 的定制