# Wiki Docker 安装

先确定你要在**本地**还是**服务器端**安装，然后修改 `docker-compose.yml` 文件中的 volumes `:` 之前的路径，更改为自己正确的路径：

```
  wiki:
    volumes:
      - /home/wiki/assets/favicons:/wiki/assets/favicons

```

然后在该文件夹下执行 `docker-compose up -d` 即可。