工具octive<br/>
小车时间(xi)和位移关系(yi)关系<br/>
x = [0 1 2 3 4 5 6  7  8  9]<br/>
y = [0 2 4 7 8 9 12 14 15 18]<br/>
代码<br/>
x = [0 1 2 3 4 5 6  7  8  9]<br/>
y = [0 2 4 7 8 9 12 14 15 18]<br/>
plot(x,y,'o');grid;polyfit(x,y,1) ###到这里显示的结果是 ans =1.93333   0.20000 即 y = 1.9333\*x + 0.20000 <br/>
hold on;x=[0,10];y= [1.93333\*0 + 0.20000,1.93333*10 + 0.20000];plot(x,y)<br/>
![image](https://github.com/advx9600/blog/blob/master/%E6%9C%80%E5%B0%8F%E4%BA%8C%E4%B9%98%E6%B3%95/main.png)
