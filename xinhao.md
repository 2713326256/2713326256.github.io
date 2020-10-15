# 2713326256.github.io
import matplotlib.pyplot as plt
import math
import numpy as np
import matplotlib
matplotlib.rcParams['font.family']='SimHei'
A=1;a=-0.6
t=np.arange(0.0,10.0,0.01)
x1=A*np.exp(a*t)
plt.plot(t,x1)
plt.axis([0,10,0,1])
plt.title("指数信号 ")
plt.xlabel('t')
plt.ylabel('x1(t)')
plt.show()
