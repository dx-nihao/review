# loadrunner的使用

## 一.Generate的使用

### 1.添加快照功能

<img src="C:\Users\hasee\AppData\Roaming\Typora\typora-user-images\image-20220706202944298.png" alt="image-20220706202944298" style="zoom:50%;" />

<img src="C:\Users\hasee\AppData\Roaming\Typora\typora-user-images\image-20220706203355001.png" alt="image-20220706203355001" style="zoom: 67%;" />



### 2.添加关联（例如登录设置变量）

<img src="C:\Users\hasee\AppData\Roaming\Typora\typora-user-images\image-20220706202730237.png" alt="image-20220706202730237" style="zoom: 50%;" />

<img src="C:\Users\hasee\AppData\Roaming\Typora\typora-user-images\image-20220706203554138.png" alt="image-20220706203554138" style="zoom:80%;" />

![image-20220706204019030](C:\Users\hasee\AppData\Roaming\Typora\typora-user-images\image-20220706204019030.png)



![image-20220706204221064](C:\Users\hasee\AppData\Roaming\Typora\typora-user-images\image-20220706204221064.png)



![image-20220706205242206](C:\Users\hasee\AppData\Roaming\Typora\typora-user-images\image-20220706205242206.png)

![image-20220706205649866](C:\Users\hasee\AppData\Roaming\Typora\typora-user-images\image-20220706205649866.png)

![image-20220706205923801](C:\Users\hasee\AppData\Roaming\Typora\typora-user-images\image-20220706205923801.png)



![image-20220706211451366](C:\Users\hasee\AppData\Roaming\Typora\typora-user-images\image-20220706211451366.png)

![image-20220706210201305](C:\Users\hasee\AppData\Roaming\Typora\typora-user-images\image-20220706210201305.png)



### 3.添加检查点（断言）

<img src="C:\Users\hasee\AppData\Roaming\Typora\typora-user-images\image-20220706202840848.png" alt="image-20220706202840848" style="zoom:50%;" />



### 4.参数记录

(1)"SaveCount=**reservation_Count**",

![image-20220706203102649](C:\Users\hasee\AppData\Roaming\Typora\typora-user-images\image-20220706203102649.png)

(2)打印

lr_output_message("")

**lr_output_message**(lr_eval_string("{userName}"))

strcmp(str1, str2);	



### 5.设置运行场景

![image-20220706220225366](C:\Users\hasee\AppData\Roaming\Typora\typora-user-images\image-20220706220225366.png)

![image-20220706220719149](C:\Users\hasee\AppData\Roaming\Typora\typora-user-images\image-20220706220719149.png)



## 二.Controller的使用

![image-20220708231151098](C:\Users\hasee\AppData\Roaming\Typora\typora-user-images\image-20220708231151098.png)

点击run后，之后在view中点击show graps来显示运行图

之后运行结束后，通过在result中点击自动加载analysis会跳转到analysis页面，之后里面就会生成一个报告总结



## 三.Analysis的使用

![image-20220708234407581](C:\Users\hasee\AppData\Roaming\Typora\typora-user-images\image-20220708234407581.png)

![image-20220708233835575](C:\Users\hasee\AppData\Roaming\Typora\typora-user-images\image-20220708233835575.png)