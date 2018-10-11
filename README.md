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
# 安装V2RAY
```javascript
bash <(curl -s -L https://raw.githubusercontent.com/ArtechChu/VPS-INSTALL-V2RAY/master/lib/install.sh)
```

传输协议：无特殊要求的话，默认TCP即可
端口：无特殊要求的话，默认即可
