# USTCPhysExpData
USTC Physics Experiments Data

### 中科大大物实验数据

#### Comes with NO WARRENTY

#### For educational use only

本项目包含本人做过的大物实验的原始数据、数据处理脚本、数据处理结果和作图结果。可供参考。不保证内容的准确性、完整性。目前已知其中部分实验的结果并不理想，数据处理并不完全正确。

若提供数据或纠正错误，欢迎issue/pull request

### 内容说明

`Experiments`目录中含有所有内容，其中按照学期分为`Grade1Spring  Grade2Autumn  Grade2Spring`等。

学期目录内为该学期我做过的大物实验。

每个实验目录中，一般有：

`data.txt`记录原始数据，关于数据内容文件内有部分注释，但具体含义等可能需要参考该实验资料。关于格式，`#`开头是注释，`e`开头为指定数量级。

`plot.py`或`analyse.py`为分析脚本，读入`data.txt`，输出绘制的图片或者计算结果。

`*.png`为数据作图。

`gen.docx`或者其他类似文件为最终打印上交的内容，多数由脚本自动生成。

如果实验有具体要求，可能目录里有其他文件和资料，这都很好理解。

### 使用方法

建议：查看data.txt原始数据，查看图片参考作图，查看py脚本参考数据处理方法。

不建议：尝试直接运行脚本（原因如下）。

### 关于脚本？能否运行？

有时间再写-_-
