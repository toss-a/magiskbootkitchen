# magiskbootkitchen
Support Windows and linux,only 64bit device can execute
更改:
修复修改ramdisk文件后打包cpio失效
针对sm8475的vendor_boot.img启用了lz4压缩导致解压错误修复
如果其他vab没有启用lz4压缩 请注释掉lz4压缩代码
测试系统ubuntu 22.04 需要安装 lz4 命令sudo apt install lz4