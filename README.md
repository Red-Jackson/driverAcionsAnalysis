# driverAcionsAnalysis
交通运输行为特征分析数据处理部分代码

⚠️ 本项目为大数据概论课程实践项目，代码仅供参考

## 文件说明

- deal_data.py——数据预处理
- deal_index.py——对各项指标进行处理和修正，调用places.json与天气信息整合为一个文件输出
- china_places.json——中国地理位置坐标信息
- run_map.py——对修正后的轨迹生成html文件绘制轨迹图
- separate.py——将整合后的数据集进行二七分成训练集合和测试集文件
- bpnn_forescore.py——BP神经网络计算综合评分

### k_means

- heatmap_gen.py——生成热力图绘制文件
- kmeans.py——驾驶员行为特征聚类分析
- simhei.ttf——中文字体文件，防止生成图像中文乱码

### csv_data

- All_in_one.csv——所有信息整合后的数据
- trainset.csv——生成的训练集文件
- testset.csv——生成的测试集文件
- validationset.xlsx——最终三项评分验证表，绘制对比图用

### webpage_track

- img——附件图像
- html——两辆行为特征明显不规范的车辆轨迹绘制文件

### results

用来存放一些生成的图表

## ⚠️

由于数据处理部分文件过多，可以直接使用`csv_data`内的文件从神经网络分割数据集部分开始做起。