[English](./README.EN.md) | 简体中文

[![HitCount](http://hits.dwyl.com/ActonMartin/ActonMartin/KITTI_dataset.svg)](http://hits.dwyl.com/ActonMartin/ActonMartin/KITTI_dataset)

# 原始数据集的地址
http://datasets.lids.mit.edu/sparse-to-dense/data/kitti.tar.gz

下载速度慢的话，开socks5代理。

# 国内数据集地址
百度网盘： 

链接:https://pan.baidu.com/s/1gAO7qRhnhUwpEt_3GKcXeg 提取码:qfwz 

由于是分割的文件，在下载各个部分之后需要合并。使用下列命令行进行数据合并。

 ```
 cat kiiti.tar.gz.part* > kitti_new_tar.gz
 ```