# POI导出Excel，这里封装了几个方法，在监听器中调用即可
#<br />[CSDN](http://blog.csdn.net/beyood1983/article/details/53078862)
 <br />  1.saveFile方法主要是选保存路径，并判断文件是否已存在，list里是从数据库查询到的数据，这里就不写了
 <br />  2.writeexcel方法负责创建excel，前面4步即可，许多属性默认；并创建数据流处理数据
 <br /> 3.insertCell方法：插入数据到单元格，这里是按行插入数据；如果要按列插入数据，可以把行封装到List里，遍历数据做createRow，并把它添加到List里，在循环遍历插入数据。
 ![](http://img.blog.csdn.net/20161109103655364)
 <br />
 ![](http://img.blog.csdn.net/20161109103707431)
 
 

