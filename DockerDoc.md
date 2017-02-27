# [Docker Documentation](https://docs.docker.com/)
Docker可以让你在不用考虑系统配置的情况下，帮你打包你的app机器依赖，从而使得你的app更加轻便。

## Basics Of Docker
[基础课程](c1/1-1.md)介绍了Docker的概念、工具、命令。比如告诉你如何build、push、pull Docker的Docker镜像，以及如何以容器的方式运行（这部分课程不会教你部署app）。

## [Define And Deploy Application](https://docs.docker.com/engine/getstarted-voting-app/)
定义和部署的课程会教你如何将容器相互关联，并将它们定义为（准备在大规模生产环境中部署的）应用的服务。Compose Version 3 new features and swarm mode。

## Componets
### [Docker For Mac](https://docs.docker.com/docker-for-mac/)
一款使用了MacOS沙箱安全模式的本机应用，它为你的 Mac 提供了所有Docker工具。

### [Docker For Windows](https://docs.docker.com/docker-for-windows/)
一款提供了所有Docker工具的本地windows应用。

### [Docker For Linux](https://docs.docker.com/engine/installation/linux/)
在已经安装了Linux发行版的电脑上安装Docker。

### [Docker Engine](https://docs.docker.com/engine/installation/)
可以用来创造Docker镜像以及运行Docker容器。
在1.12.0版本中，引擎包括 [swarm mode](https://docs.docker.com/engine/swarm/) 容器的功能

### [Docker Hub](https://docs.docker.com/docker-hub/)
管理和构建镜像的托管服务。

### [Docker Cloud](https://docs.docker.com/docker-cloud/)
提供build、testing、deploying Docker镜像的服务。

### [Docker Trusted Registry](https://docs.docker.com/datacenter/dtr/2.2/guides/)
存储/注册你的镜像。

### [Docker Universal Control Plane](https://docs.docker.com/datacenter/ucp/2.1/guides/)
像单台机器一样管理Docker集群的控制面板。

### [Docker Machine](https://docs.docker.com/machine/install-machine/)
在网络或者云中自动化容器配置。mac、window、Linux可用。

### [Docker Compose](https://docs.docker.com/compose/overview/)
定义使用多容器的构建的应用
