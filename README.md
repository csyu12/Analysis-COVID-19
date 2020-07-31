# Analysis-COVID-19

+ 介绍

  本项目对全球以及各个国家进行确诊，死亡，痊愈等案例进行了数据分析，通过各个国家确诊人数的对比，使用 SVR、多项式回归、贝叶斯岭回归三个算法，对未来的确诊病例进行了预测

+ 部署

  ```python
  pip install jupyter
  
  # 启动
  jupyter notebook
  
  # 模块安装
  pip install numpy
  pip install pandas
  pip install seaborn
  pip install matplotlib
  ```

+ 技术总结

  本项目主要使用了pandas、numpy、matplotlib、sklearn等模块。

  - 对csv文件进行了读取，使用了 pandas中的read_csv的方法，对csv格式的数据集进行读取。
  - 使用loc对数据进行了切片、对全球，国家的数据进行了划分
  - 使用 mat 对所有的数据进行图形化展示
  - 使用 SVR 、多项式回归、贝叶斯岭回归等算法对未来确诊数据进行了预测
  - 使用了MAE和MSE对模型训练后的误差进行了分析

+ 参考链接

  + `coef_`和 `intercept _`：http://www.voidcn.com/article/p-bucfaeno-qq.html

  + MSE和MAE ：https://www.jianshu.com/p/1ff7ae7ea9ef

  + MSE与MAE对比：https://blog.csdn.net/PKU_Jade/article/details/80745404

  + SVR：https://www.jianshu.com/p/399ddcac2178

  + SVR：https://blog.csdn.net/zwqjoy/article/details/80251707

  + 多项式回归：https://blog.csdn.net/qq_25560849/article/details/80543180

  + 多项式回归：https://www.cnblogs.com/zhangkanghui/p/11333572.html

  + 贝叶斯的岭回归：https://blog.csdn.net/u010016927/article/details/75000152

  + 贝叶斯的岭回归：https://blog.csdn.net/qq_37353105/article/details/80612561?utm_source=blogxgwz9
