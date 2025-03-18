重头开始

1. 安装docker 配置镜像
2. 下载ubuntu镜像
3. 启动容器
4. apt update  安装init ，git，g++
5. 更换阿里源
6. 添加.ssh ida_rsa ，用docker复制文件过去就可以
7. 配置git
sudo 用户alias sudo=''
apt install ubuntu-standard
   apt install wget -y
   unzip
   sudo docker cp ~/UniMem/tool/apps/turi/Twitter-dataset.zip f865c7b47de8:/root/
   
   解决root下sudo无法运行的错误
   apt install -y bc
   pin工具权限不够，主机sudo su之后按照错误提示改
   