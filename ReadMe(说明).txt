������������This is an constructor of a music game named "Rhythm Master" (Tencent) ���������������� 

Contact:   ezgo_transfer@foxmail.com
	
	QQ: 2755703143

��������������������������������������������������������������������������������������������

��bases, parameters, extension1 ����һ���ļ��С�

����prefix.imd, drawing.mp3����һ���ļ��У���parameters.py��prefix_path�ĳ�

prefix.imd, drawing.mp3���ڵ��ļ��С�

ʹ�ã� D�㣬 H�ߣ� T���ߣ� Bģ�顣 draw(rm_obj)��IVM�ϻ���(��Ҫ��װIVM֧��draw()��������
���� 
from extension1 import *

a = D(300)
draw(a)

b = H(300, 1000)
draw(b)

c = T([300, 500,900], [-1, 1, 0])
draw(c)
draw(c.mr())

d = B([b,c], ['p', 2])
draw(d)
draw(d.mr())

e = retiming(d, 1000)
draw(e)

f = vibro('12dd1', 300, 3000)
draw(f)

g = gliss('10d1, 300, 2000)
draw(g)
