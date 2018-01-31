# OpencvQtRelease
使用Qt5.6.3 mingw4.9.2编译的库
编译方式参照https://wiki.qt.io/How_to_setup_Qt_and_openCV_on_Windows
使用的Qt版本：5.6.3
MingW：4.9.2

使用方法
1.解压后， 将 安装位置 \opencv\release\install\x86\mingw\bin 添加到环境变量。重启电脑。
2.Qt工程文件 添加 头文件 \opencv\release\install\include
  添加库 \opencv\release\install\x86\mingw\bin
  发布程序时 缺什么动态链接库，直接到该路径下找

