# mysql
需要预先执行的脚本放到/config/mysql/initdb.d下。mysql创建时会自动执行。
# crontab
定时任务启动容器执行php脚本或者其他脚本，可以使用supervisor或者crontab配置。
配置文件参考/crontab/demo.sh
# 快速使用
```shell
cd docker-php-env
sudo docker-compose up -d
```