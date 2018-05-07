# JData_2018---如期而至-用户购买时间预测
## 大家注意这是一份娱乐版baseline。。。仅供参考
### 线上分数 S = 0.3158 | S1 = 0.4726 | S2 = 0.2133
### 感谢  [Herbert95 的 baseline代码](https://github.com/Herbert95/JDATA_)

##### 此代码里面冗余部分较多，其实只用user_order表即可

##### 文件路径
- 初始数据放入 ./data 文件夹中
- 生成的 user_order_table.csv 请新建 ./processed_data 文件夹
- 输出结果 test.csv 请新建 ./output 文件夹

##### 思路：
1. 先按照用户年购买量排序，截取前50000名用户
2. 再从2017-05-01 ～～～～ 2017-05-15 中随机出50000天
3. 拼接在一起提交即可
