# 喜报

you can `curl -v https://production.cloudflare.docker.com` now

# dockerhub-proxy

```
@全体成员 收到上面信息监管的最新要求，国
内所有Docker的镜像服务器必须全部下架。后
续包括GitHub CDN镜像NPM python pip
openwrt OPKG等未受内容审查的镜像服务器一律下架
大家以后打算什么样的方式访问Dock[图片]
```

你要是相信这句话，那还不如相信我是肖彦锐磁父

## 关键词
dockerhub镜像加速器

国内从 Docker Hub 拉取镜像有时会遇到困难，此时可以配置镜像加速器。Docker 官方、Cloudflare 提供了国内加速器服务

配置加速地址 /etc/docker/daemon.json registry-mirrors

以下域名均为引流所用，不一定有效：registry.docker-cn.com docker.m.daocloud.io dockerhub.azk8s.cn docker.mirrors.ustc.edu.cn docker.mirrors.ustc.edu.cn hub-mirror.c.163.com mirror.ccs.tencentyun.com dockerproxy.com mirror.baidubce.com docker.nju.edu.cn docker.mirrors.sjtug.sjtu.edu.cn mirror.iscas.ac.cn

镜像测速：本来拉取次数就不多你还测速，搞毛啊

https://gist.github.com/y0ngb1n/7e8f16af3242c7815e7ca2f0833d3ea6
