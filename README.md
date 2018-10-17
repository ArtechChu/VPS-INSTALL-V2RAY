# VPS安装 V2RAY

> 关于BBR安装：https://github.com/ArtechChu/VPS-INSTALL-SS
>
> 参考自 223boy

## 安装 curl：
centos：
```javascript
yum update -y && yum install curl -y
```
ubuntu/debian
```javascript
apt-get update -y && apt-get install curl -y
```

## 安装 wget：
centos：
```javascript
yum -y install wget
```
ubuntu/debian
```javascript
apt-get -y install wget
```

## 安装V2RAY
- centOS
    ```javascript
    bash <(curl -s -L https://raw.githubusercontent.com/ArtechChu/VPS-INSTALL-V2RAY/master/lib/install.sh)
    ```
- debian
    ```javascript
    wget -N --no-check-certificate https://raw.githubusercontent.com/FunctionClub/V2ray.Fun/master/install.sh && bash install.sh
    ```

传输协议：无特殊要求的话，默认TCP即可

端口：无特殊要求的话，默认即可

## 管理命令
- v2ray info 查看 V2Ray 配置信息
- v2ray config 修改 V2Ray 配置
- v2ray link 生成 V2Ray 配置文件链接
- v2ray infolink 生成 V2Ray 配置信息链接
- v2ray qr 生成 V2Ray 配置二维码链接
- v2ray ss 修改 Shadowsocks 配置（可关闭）
- v2ray ssinfo 查看 Shadowsocks 配置信息
- v2ray ssqr 生成 Shadowsocks 配置二维码链接
- v2ray status 查看 V2Ray 运行状态
- v2ray start 启动 V2Ray
- v2ray stop 停止 V2Ray
- v2ray restart 重启 V2Ray
- v2ray log 查看 V2Ray 运行日志
- v2ray update 更新 V2Ray
- v2ray update.sh 更新 V2Ray 管理脚本
- v2ray uninstall 卸载 V2Ray
