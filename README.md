# ddcw
only for manage script at ./*shells
and packet shells

## conf
for ddcw config, ddcw.conf define variable for other script , default.conf is default configure doc, change by release.
conf/ddcw.conf 定义了一些常规变量,为了方便其他脚本执行, conf/default.conf是默认的配置,只和版本有关.

## install_shells
only install_script, such as ZK_PseudoCluster_install.sh to install Zookeeper,
install_shells目录下面的脚本都是安装类型的脚本,这里的脚本会按照conf/ddcw.conf里面定义的变量去执行
比如定义默认安装路径BASE_INSTALL_DIR="/usr/local"   开机自启ONBOOT=1

## man
some of shell command has Help documentation 
有些命令可以使用帮助文档,比如 man ddcw

## readme
mayby shell script has readme
保留的,感觉没得用处....

## shells
main shells will copy to /usr/bin and chmod +x shells/
这里的脚本会被拷贝到 /usr/bin下面去, 比如ddcw  scanportDDCW
