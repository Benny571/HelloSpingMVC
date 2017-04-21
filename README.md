# 运行前说明
1. 进入conf目录配置名称、IP、端口等
2. 第一次或重新统计请删除log目录下所有文件

# 关于环境及运行
## windows
1. cmd进入目录tcpdetect
2. 进入沙盒环境，运行 `<virtualenv_win\Scripts\activate.bat>`
3. 主程序，运行 `<python.exe main.py>`

## linux
1. cd进入目录tcpdetect
2. 安装环境，运行 `<pip install PyYAML==3.12>`
3. 主程序，运行 `<python.exe main.py>`

*备注说明，linux退出沙盒命令: deactivate*

# 关于目录
* conf
配置文件
* log
默认日志及扫描信息路径
* virtualenv_win
windows 运行环境
* virtualenv_linux
linux 运行环境(centos)

# 关于配置
*进入conf目录，详见注释*
