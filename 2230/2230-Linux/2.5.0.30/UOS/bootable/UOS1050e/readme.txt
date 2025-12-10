#功能：该目录提供脚本install.sh，在安装卡下系统时可以将ps3stor.ko集成到ramfs中
#使用方法
（1）安装卡下系统在选择安装介质前，按住ctrl+alt+F2进行后台shell
（2）将与系统匹配的ps3stor.ko和install.sh脚本放在一个目录下
（3）为了保证ps3stor.ko是匹配的，可以先insmod ps3stor.ko；若不手动执行，install.sh脚本中也会执行ps3stor.ko的安装
（4）执行sh install.sh脚本，确保没有报错，说明后台程序已经执行
（5）按住ctrl+alt+F6，回到系统安装界面，刷新后选择卡下系统盘进行安装