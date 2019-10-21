# 递归
## 基本格式
![1](https://i.loli.net/2019/10/16/vMdOzbA9SsYZexQ.png)

## 处理死循环的三种方式
·展开　　·Big-O估算　　·主理论
![1](https://i.loli.net/2019/10/16/olCUEWmQrKakfBM.png)</br></br>
### 主理论 </br></br>
实际做题时，需将a,b,c,d,k替换成相应常数 </br></br>
![1](https://i.loli.net/2019/10/16/q5upS78Lk3TiBdU.png)
![1](https://i.loli.net/2019/10/16/j6AhMTtR3ivnXqp.png) </br></br>
#### Ps 
T(n) = aT(n-b) + c　　　当b ！= 1 时，需要进行推理，上述公式不可直接调用
