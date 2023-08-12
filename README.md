# YoloPedestrian
yolov8 行人检测模型

------------------------------------
## 说明
使用 CityPersons, CrowdHuman, MOT17, MOT20, ETHZ, CUHK 等数据集汇总训练完成


## 模型训练记录
可以在 doc 目录下查看

### 其中:
- yolov8s 使用默认参数，cfg 用的是[fusion.yaml](configs%2Ffusion.yaml), 
- yolov8n 修改了loss权重，cfg使用了[default.yaml](configs%2Fdefault.yaml)
- yolov8s-vis-body 修改上述数据集中的Crowdhuman, 将full-body 改成vis-body, 并重新整合了数据


## 模型文件说明
未来会增加rknn, tensorrt, 以及ncnn 的部署模型
