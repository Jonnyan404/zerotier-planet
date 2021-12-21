
# 一分钟自建zerotier-planet

私有部署zeroteir-planet服务
基于 [ztncui](https://github.com/key-networks/ztncui-aio) 整理成 docker-compose.yml 文件.


# 必要条件

- 具有公网ip的服务器(需要开放4000/tcp端口,亦可自定义端口）
- 安装 docker
- 安装 docker-compose

# 用法

纯小白建议直接执行这个:

`docker run --restart=on-failure:3 -d --name ztncui -e HTTP_PORT=4000 -e HTTP_ALL_INTERFACES=yes -e ZTNCUI_PASSWD=mrdoc.fun -p 4000:4000 keynetworks/ztncui`

有基础的,可二选一.

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

# 关联云服务器(带公网IP)

[【腾讯云】云产品限时秒杀，爆款2核4G云服务器，首年74元](https://curl.qcloud.com/S2Db7PLK)

## 后记

经实测,window/Android客户端可直接连接,无需修改任何文件.理论上其它客户端同理.

### 私有 zerotier-planet 的优势:
- 解除官方 50 的设备连接数限制
- 提升手机客户端连接的稳定性

# Reference Link

- <https://www.mrdoc.fun/doc/443/>
- <https://github.com/key-networks/ztncui-aio>
