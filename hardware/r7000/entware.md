# 前言
因为`GFW`的缘故，entware的源已经无法直接访问，因此需要提前下载好ipk安装包并本地安装的方式。所有安装包都能在目录中的`packages`下找到。

# 步骤
## 安装opkg
	sh entware-setup.sh
注：该脚本来源于[asuswrt-merlin](https://github.com/RMerl/asuswrt-merlin/blob/master/release/src/router/others/entware-setup.sh, '脚本来源')。经过部分修改，如支持`hfs`系统，使用本地安装包等。

## 安装entware-opt
	/opt/bin/opkg install entware-opt
注：会有一串前置依赖程序需要安装，都在`packages`目录里，通过下述命令安装：

	opkg install XXXX.ipk


