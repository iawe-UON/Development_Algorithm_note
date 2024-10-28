从镜像仓库拉取镜像：docker pull 

查看镜像列表：docker image

查看镜像，容器，数据卷占用空间：docker system df

显示虚悬镜像：docker image ls -f dangling=true（-f == --filter: 条件过滤）

删除虚悬镜像：docker image prune

只要镜像ID： docker image ls -q

重新组织：docker image ls --format “table {{.ID}}\t{{.Repository}}\t{{.Tag}}”

