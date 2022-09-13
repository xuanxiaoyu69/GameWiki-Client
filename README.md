<p align="center">
    GameWiki-Client
</p>

## 关于 

游戏百科客户端

## 环境要求

php8.1+

mysql8

## 安装

1.复制.env配置文件
```
cp .env.example .env
```

2.修改.env配置文件中的数据库配置
```
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=gamewikiclient
DB_USERNAME=homestead
DB_PASSWORD=secret
```

3.执行安装命令
```
// 执行composer安装
composer install

// 发布laravel资源
php artisan vendor:publish --tag=laravel-assets --ansi --force

// 生成laravel key
php artisan key:generate --ansi

// 安装dcat-admin
php artisan admin:publish

php artisan admin:install
```

4.后台地址：域名/admin，使用用户名admin和密码admin登陆

## 鸣谢

+ [Laravel](https://laravel.com/)
+ [Dcat Admin](http://www.dcatadmin.com/)


## 开源协议

[MIT license](https://opensource.org/licenses/MIT).
