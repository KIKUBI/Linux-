# Linux-
1、docker 部署项目 
    使用压缩包安装tar -zxvf 
    配置下载源  vim /etc/docker/daemon.json.rpm
                vim /etc/docker/vim daemon.json.rpmsave
    添加：{
              "registry-mirrors": [
                    "https://docker.1ms.run",
                    "https://hub.rat.dev",
                    "https://docker.1panel.live"
                ]
          }
    修改文件 mv /etc/docker/daemon.json.rpm /etc/docker/daemon.json
    重启docker
