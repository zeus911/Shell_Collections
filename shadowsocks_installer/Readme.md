# Shadowsock automatic installer

## ShadowsockR_installer
OS: CentOS, Debian, Ubuntu

RAM >= 128 MB

### Default Settings

> Port: 8989
> 
> Password: doufu.ru
> 
> Method: chacha20
> 
> Protoco: origin
> 
> Protocol param: 
> 
> Obfs: http_simple_compatible
> 
> Obfs param: bing.com,microsoft.com,live.com,outlook.com

### Usage
#### Install
```
bash -c "$(wget --no-check-certificate https://github.com/Char1sma/Shell_Collections/raw/master/shadowsocks_installer/shadowsocksR_installer.sh -O -)" -c "-i"
```
#### Uninstall
```
bash -c "$(wget --no-check-certificate https://github.com/Char1sma/Shell_Collections/raw/master/shadowsocks_installer/shadowsocksR_installer.sh -O -)" -c "-u"
```