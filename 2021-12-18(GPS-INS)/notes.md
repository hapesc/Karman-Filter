# NOTES

##### 在12-18 实验中，明显可以发现数据进行滤波的结果精度与激励过程噪声模型有着较强的关系

不同噪声模型对应的结果如下：

Q=1e-5



![Cmp_la_Q1](C:\Users\Administrator\Desktop\BaiduNetdiskWorkspace\Code\KF\2021-12-18(GPS-INS)\数据图\Cmp_La_Q1.png)

![Cmp_lo_Q1](C:\Users\Administrator\Desktop\BaiduNetdiskWorkspace\Code\KF\2021-12-18(GPS-INS)\数据图/Cmp_Lo_Q1.png)



Q=1e-3



![Cmp_la_Q3](C:\Users\Administrator\Desktop\BaiduNetdiskWorkspace\Code\KF\2021-12-18(GPS-INS)\数据图/Cmp_la_Q3.png)

![Cmp_lo_Q3](C:\Users\Administrator\Desktop\BaiduNetdiskWorkspace\Code\KF\2021-12-18(GPS-INS)\数据图/Cmp_lo_Q3.png)



Q=1e-2



![Cmp_la_Q2](C:\Users\Administrator\Desktop\BaiduNetdiskWorkspace\Code\KF\2021-12-18(GPS-INS)\数据图/Cmp_la_Q2.png)

![Cmp_lo_Q2](C:\Users\Administrator\Desktop\BaiduNetdiskWorkspace\Code\KF\2021-12-18(GPS-INS)\数据图/Cmp_lo_Q2.png)



Q=1e-1



![Cmp_la_Q4](C:\Users\Administrator\Desktop\BaiduNetdiskWorkspace\Code\KF\2021-12-18(GPS-INS)\数据图/Cmp_la_Q4.png)

![Cmp_lo_Q4](C:\Users\Administrator\Desktop\BaiduNetdiskWorkspace\Code\KF\2021-12-18(GPS-INS)\数据图/Cmp_lo_Q4.png)



从以上数据可以发现，Q=0.1时结果的精度最高，基本与原始数据重合