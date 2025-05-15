## Redis - 6.2.6

## 1. 安装依赖

* sudo apt-get update
* sudo apt-get install build-essential tcl

## 2. 编译Redis

* make

## 3. 安装Redis（可选）

* sudo make install

## 4. 运行Redis服务器

* src/redis-server

## 5. 连接到Redis服务器进行测试

* src/redis-cli

## 6. 调试Redis（可选）

* make DEBUG=1

然后，使用gdb启动Redis服务器：

* gdb --args src/redis-server

## 7. 清理编译环境（可选）

* make distclean  # 清理所有构建文件和目标文件，但不删除源代码目录结构。
* make clean      # 清理构建文件和目标文件，但保留源代码目录结构。