
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

## 后记

经实测,window/Android客户端可直接连接,无需修改任何文件.理论上其它客户端同理.

### 私有 zerotier-planet 的优势:
- 解除官方 50 的设备连接数限制
- 提升手机客户端连接的稳定性

# Reference Link

- <https://www.mrdoc.fun/doc/443/>
- <https://github.com/key-networks/ztncui-aio>
