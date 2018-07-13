# 镜像类资源集

## 前端CDN

- [360网站卫士](http://libs.useso.com/), 包括常用库，Google公共库及Google字体库镜像
- [又拍云](http://jscdn.upai.com/)
- [七牛云存储](http://www.staticfile.org/)
- [bootcdn](http://www.bootcdn.cn/)
- [百度](http://developer.baidu.com/wiki/index.php?title=docs/cplat/libs)
- [SAE](http://lib.sinaapp.com/)

## PHP

- [SAE](http://cn2.php.net/)

## PHP: Composer

- [pkg.phpcomposer.com](http://pkg.phpcomposer.com/)

## Node: Npm

- [淘宝NPM镜像](https://npm.taobao.org/)

使用方法：

```
npm config set registry https://registry.npm.taobao.org
```

## Python: PyPi

- [豆瓣](http://pypi.douban.com/)
- [V2EX](http://pypi.v2ex.com/simple/)

使用方法:

```
pip install web.py -i https://pypi.douban.com/simple
easy_install web.py -i https://pypi.douban.com/simple
```

## Ruby: RubyGems

- [淘宝](http://ruby.taobao.org/)

## Golang

- [Golang TC](http://www.golangtc.com/)

## Docker

### 加速器

- [daocloud](https://www.daocloud.io/mirror#accelerator-doc)
- [阿里云](http://aliyun.com/)
- [灵雀云](http://alauda.cn/)

如何配置加速器：TBD


### 镜像仓库
- [灵雀云 - 镜像仓库、加速器](https://hub.alauda.cn/)
- [阿里云] (https://dev.aliyun.com/search.html)

### 相关下载加速

- [docker - daocloud](https://download.daocloud.io/Docker_Mirror/Docker)
- [docker-compose - daocloud](https://download.daocloud.io/Docker_Mirror/Docker_Compose)
- [Docker for Mac/Windows](https://download.daocloud.io/Docker_Mirror/Docker_for_Windows_Mac)


## Linux/Ubuntu

- [阿里云](http://mirrors.aliyun.com/)
- [网易开源镜像站](http://mirrors.163.com/)
- [搜狐开源镜像站](http://mirrors.sohu.com/)

Ubuntu修改源例：

```
sed -i s/archive.ubuntu.com/mirrors.aliyun.com/g /etc/apt/sources.list && sed -i s/security.ubuntu.com/mirrors.aliyun.com/g /etc/apt/sources.list
apt-get update
```

## 许可证

[![知识共享许可协议](http://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)

本作品采用[知识共享署名 4.0 国际许可协议](http://creativecommons.org/licenses/by/4.0/)进行许可。
