本项目是对项目https://github.com/MaiMeng1204/Predict-house-rent-with-neutral-network 中爬虫部分的更新，适应了最新的前端页面变换，以便自己使用。

# 简介

参见https://github.com/MaiMeng1204/Predict-house-rent-with-neutral-network

本项目利用`Python`的`scrapy`框架爬取[链家网](https://sh.lianjia.com/zufang/)的上海市租房信息，利用`pandas`、`numpy`、`matplotlib`、`seaborn`、`folium` 、`wordcloud` 等库进行数据分析和可视化，通过`one-hot`编码和文本特征提取出120个训练特征，搭建3层神经网络对上海市租房价格进行预测。
