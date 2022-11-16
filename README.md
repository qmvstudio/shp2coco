# 关于shp2coco
shp2coco 是一个帮助从shp（矢量数据）和tif（影像数据）文件创建COCO格式数据集的工具 . <br>

功能主要包括:<br>
1:通过shape制作Tif的掩膜（mask）.<br>
2:切割mask与tif.<br>
3:将数据划分为 training, eval and test数据集.<br>
4:生成COCO数据集所需要的annotations （in uncompressed RLE ） 和 polygons 文件.<br>

## 第三方库
脚本基于： 
[geotool](https://github.com/Kindron/geotool) 
[pycococreator](https://github.com/waspinator/pycococreator)

## 使用方法:
如果想要生成annotations，请执行:<br>
`python shape_to_coco.py`<br>
如果想要可视化annotations, 则执行:<br>
`python visualize_coco.py`<br>
