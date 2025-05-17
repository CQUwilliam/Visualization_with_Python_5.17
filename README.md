# conda mac 已经不支持 python3.7
## 首先未避免文件位置报错，将SpeakingData.csv、Speaking_FixationReport_Raw.xlsx、Listening_FixationReport_Raw.xlsx移动到代码当前文件夹中；或使用文件相对位置、绝对位置
 ## 在终端中运行：
      conda create -n py38 python=3.8 之后按 y 同意安装
      conda activate py38
      pip install ipykernel
      pip install pandas numpy matplotlib seaborn scipy statsmodels pingouin jinja2 openpyxl
      python -m ipykernel --name py38 --user
      输入 jupyter notebook 启动
      (如果没有装过 jupyter notebook 在终端中运行 pip install jupyter)
      jupyter notebook 右上角选择python 环境
