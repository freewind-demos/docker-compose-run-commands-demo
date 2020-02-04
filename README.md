Docker Compose Run Commands Demo
================================

直接在`docker-compose.yml`中运行某个docker container中的command

注意在yaml中多行字符串的写法：换行符会被替换成空格，组成一行

更多写法：https://stackoverflow.com/a/49685727/342235

```
docker-compose up
```

会启动后执行`command`中的命令
