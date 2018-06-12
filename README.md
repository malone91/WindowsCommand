# WindowsCommand
Windows命令 

查看所有端口占用情况
netstat -ano

查看某个端口被占用的PID
netstat -aon|findstr "8080"

查看哪个进程占用了端口
tasklist|findstr "pid"
