
# 一分钟自建zerotier-planet

私有部署zeroteir-planet服务
基于 [ztncui](https://github.com/key-networks/ztncui-aio) 整理成 docker-compose.yml 文件.

# 必要条件

- 具有公网ip的服务器(需要开放4000/tcp端口,亦可自定义端口）
- 安装 docker
- 安装 docker-compose

# 用法

```
git clone https://github.com/Jonnyan404/zerotier-planet
OR
git clone https://gitee.com/Jonnyan404/zerotier-planet

cd zerotier-planet
docker-compose up -d
```

然后访问 `http://ip:4000` 访问web界面.

- 用户名:admin
- 密码:mrdoc.fun


# Reference Link

- <https://www.mrdoc.fun/doc/443/>
- <https://github.com/key-networks/ztncui-aio>
