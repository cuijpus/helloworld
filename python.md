

## 碰到的坑
AttributeError: 'dict' object has no attribute 'iteritems'<br>
Python3.5中：iteritems变为items <br>

NameError:name ‘xrange’ is not defined<br>
若你想在python 3中运行程序，将xrange( )函数全部换为range( )即可<br>

python 3.x 错误 ‘generator’ object has no attribute ‘next’ <br>
原因是在python 3.x中 generator（有yield关键字的函数则会被识别为generator函数）中的next变为__next__了,next是python 3.x以前版本中的方法 <br>
