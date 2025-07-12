本项目数据来源于https://www.kaggle.com/datasets/yijiajia/taobao-userbehavior
 由于数据据过于庞大，本项目只截取了前一百万行数据进行分析


操作流程
1.安装依赖库：在使用本项目之前，需要提前下载好必要的 Python 库。以下是各个库及其在项目中的作用：
jupyter：用于运行和展示项目中的 Jupyter Notebook 文件（电商用户行为分析.ipynb），方便进行交互式数据分析。
pandas：强大的数据处理和分析库，用于读取、清洗和处理淘宝用户行为数据。
seaborn：基于 Matplotlib 的统计数据可视化库，可用于创建美观的统计图表。
matplotlib：Python 中常用的绘图库，为项目中的数据可视化提供基础支持。
pyecharts：用于生成 ECharts 图表的 Python 库，项目中的漏斗图和柱状图就是使用该库生成的。
numpy：提供高效的多维数组对象和各种数学函数，在数据处理和分析过程中发挥重要作用。
你可以使用以下命令来安装这些库：
pip install jupyter pandas seaborn matplotlib pyecharts numpy

2.启动项目：
下载项目文件后，复制文件的下载地址。
在命令行中切换到项目所在路径。例如，如果你使用的是 Windows 系统的命令提示符，可以使用 cd 命令进行切换：
cd "C:\your\project\path"

输入 jupyter notebook 启动 Jupyter Notebook 服务器。
在浏览器中打开 Jupyter Notebook 的界面，找到并打开 电商用户行为分析.ipynb 文件，即可开始运行项目。
