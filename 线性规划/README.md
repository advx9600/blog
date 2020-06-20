### 线性规划 Octave
max z= 2\*x1 + 3\*x2 -5\*x3<br/>
s.t.<br/>
  x1 + x2 + x3 =7<br/>
  2\*x1 -5\*x2 + x3 >=10<br/>
  x1,x2,x3 >=0<br/>
### 代码
c=[2 3 -5];a=[1 1 1;2 -5 1];b=[7 10];lb=[0 0 0];ub=[inf inf inf];<br/>
ctype=['S' 'L'];vtype=['C' 'C' 'C'];<br/>
glpk(c,a,b,lb,ub,ctype,vtype,-1)
