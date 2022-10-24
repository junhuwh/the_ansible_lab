# 安装 Ansible 以及 AWX 环境

### 系统环境准备

使用Windows系统，安装 virtualbox 虚拟机搭建实验平台

计划使用 centos stream 9 作为控制端

使用 vagrant 下载可用的操作系统镜像 或者使用 centos stream 9 安装包安装操作系统 

将该机器命名为 ansible-controller-01

在 centos 中安装 ansible 程序

复制这台虚拟机作为被控端 将其命名为 ansible-client-01

在 ansible-controller-01 中配置 Inventory 使其能连接到 ansible-client-01

测试 ansible 连接






