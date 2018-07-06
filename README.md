# mac-node-note
* 显示隐藏文件
> 点击左侧隐藏文件所在目录—> shift + command + .

* 配置host
>  sudo vim /etc/hosts
> i 插入
> 插入完后按下esc wq: 回车退出

* node服务启动出现Error: listen EADDRINUSE :::8080
> 原因：端口占用
> 查看端口占用 lsof -i :8080
> node      26930 liuxuanqing  489u  IPv4 0x95796359500204d
> 杀死进程 kill 26930

* sh 读取并执行文件的命令
> sh upload-daily.sh
> 文件内容  git add . && git commit -a -m 'update daily' && git push 

* charles手机代理
> 手机上ip填电脑ip
> 端口写charles设置的端口8888
