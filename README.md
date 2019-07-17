docker linux 安装流程
第一步：
yum install -y yum-utils device-mapper-persistent-data lvm2
第二步：
yum-config-manager --add-repo https://download.docker.com/linux/centos/docker-ce.repo
第三步：
yum list docker-ce --showduplicates | sort -r

安装Docker，命令：yum install docker-ce-版本号，我选的是18.09.5，如下
第四步：
yum install docker-ce-18.09.5

systemctl start docker

systemctl enable docker
