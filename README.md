# docker-compose

要遵照yml文件格式

不能用tab

services:下面要縮排

- 後面不能有：
    environment:
     		MYSQL_ROOT_PASSWORD: qq303904446
        
被link的container要寫在前面

cd到 docker-compose.yml 再啟動

$ docker-compose up -d
