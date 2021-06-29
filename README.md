CoGIS
========
本项目是中国地质大学（武汉）信息工程学院GIS工程实习题目，实现一个小型的原型系统，现将源代码开源。

关于数据
========
本项目分为两个版本，一个数据库版本，一个文件版本，这里暂时只提供文件版本。

Visual Studio 2019 打开
========
使用 vs2019 打开需要安装
1. MSVC v142 - VS 2019 C++ x64/x86 生成工具(最新)
2. Windows 10 SDK (10.0.19041.0)

工程文档说明
========

文档结构如下所示：

CoGIS
- 一些 git 文件
- CoGISSource
  - 其他工程目录
  - CoGIS 主工程目录
    - bin （可执行程序目录，编译后生成在此）
    - CoGIS （主工程目录）
    - Include （在 vs 中运行时调用）
    - workpath （点线面存放处）
    - bin.7z（可执行文件压缩包）
    - CoGIS.sln （解决方案文件）