# art-yaf

## php art 代码自动生成 for Yaf

## 是一个对Yaf框架自动化生成基础代码的工具。

# 功能特点
* 平台支持（支持Linux, Mac环境，Windows环境理论上也支持，不过未全面测试）
* 支持model数据模型自动生成
* 支持service数据服务自动生成
* 支持controller控制器自动生成

#  安装使用
## 依赖软件
##### 一般依赖
* yaf 1.0+
* git

### 0、下载源码
```linux
 [root@lidi home]# git clone https://github.com/autoed/art-yaf.git
  Cloning into 'art-yaf'...
  remote: Enumerating objects: 26, done.
  remote: Counting objects: 100% (26/26), done.
  remote: Compressing objects: 100% (21/21), done.
```
### 1、立刻即用
##### I::说明帮助➕
```php
> php art -h
@代码-优雅-生成器
@Art 使用说明
@example :  
1、php art m:你的微服:模型名
2、php art c:你的微服:控制器
3、php art s:你的微服 (默认你的模块下Service.php)
 -----------------------------------
｜一键创建：php art a:你的微服:起个名字｜
 -----------------------------------
 TODO-list-notice
 一、创建：audiouser请遵循小驼峰法:audioUser
 二、注意：不要忘记，配置路由（1.0版本不支持自动配置）
 .

```
##### II::检测版本⌚
```php
> php art -v
Welcome to this world
            _   
  __ _ _ __| |_ 
 / _` | '__| __|
| (_| | |  | |_ 
 \__,_|_|   \__|
 
@代码-优雅-生成器
@version ： 1.0
@author  ： fomo3d.wiki@gmail.com
.

```
##### III::注释修改㊗
```php
在 art 文件中
修改 变量 $authorName = '你的名字'
That is OK
```
## 协议

[![996.icu](https://img.shields.io/badge/link-996.icu-red.svg)](https://996.icu)
[![LICENSE](https://img.shields.io/badge/license-Anti%20996-blue.svg)](https://github.com/996icu/996.ICU/blob/master/LICENSE)

[MIT : license](https://github.com/autoed/art-yaf/blob/master/README.md)