# Linux总结

## 一.Linux文件目录

根目录：/（计算机）

/bin 存放常用命令（即二进制可执行程序）

/etc 存放系统配置文件

/home 所有普通用户的家目录

/root 管理员用户的家目录

/user 存放系统应用程序及文档

/proc 虚拟文件目录，以进程为单位存储内存的映射

/dev 存放设备文件

/mnt 临时挂载点

/lib 存放库文件

/boot 系统内核及启动有关的文件

/tmp 存放各种临时文件，是所有用户均可访问的地点

/var 存放系统运行中常改变的文件，如系统日志

## 二.Linux常见相关命令

vim catalina.out//查看tomcat日志信息

linux进入mysql命令：mysql -uroot -p密码

cd 切换目录

mkdir 创建目录

mkdir -p 文件路径 递归创建

ll 列出当前目录的所有文件详细信息

pwd 显示当前目录

tree 显示目录的树结构

ctrl/shift+insert 复制/粘贴

touch 文件名 创建一个文件（如果存在就修改文件时间）

cat -n 查看文件所有内容 显示行号

less 查看一部分内容

rm -rf 文件路径名 不用提示全部删除

cp 源目录 目的目录 复制文件/目录  （目的路径/文件名  可以重新命名文件）

mv 源目录 目的目录 移动文件/目录	修改文件名 mv 原文件名  修改文件名

man + 命令名 显示帮助文档

head -n 显示文件前n行

tail -n 显示文件后n行

vim 创建/打开文件   i 插入模式 esc+:wq  保存并退出

grep 查找文件是否包含指定子符串，并显示当前的行

ps 查看系统当前运行的进程

ps aux|grep 进程名/进程id	查看当前运行的指定进程信息

netstat -anp | grep 进程名/进程id 查看系统的网络状态(可以查看端口是否被绑定)

chmod 777 文件名 修改文件权限 （4读 2写 1执行 0什么权限也没有） 3个代表root 组 其他用户

yum list | grep	软件包名 查看指定软件包名

yum install 包名

yum remove 包名

unzip 压缩包文件名 	解压缩文件
启动tomcat 	sh 文件路径下的startup.sh

下载文件     weget +文件地址
less 查看一个大的文件 按 q 进行退出

使用重定向文件中输入内容   echo + 内容 > 文件名

kill [参数] 进程号   就可以结束进程

一般为 kill -9 强制杀死进程

chmod +x *.sh  给当前目录下的以sh结尾的所有文件赋予可执行权限（tomcat使用）

whereis 文件名  查找文件所在位置

VIM文件操作快捷键

k/j  阅读模式向上/下进行翻找

ctrl+f  向下移动一页     Ctrl+b 向上移动一页

gg 移动到文件的第一行

G  移动到文件最后一行

/word  ?word 从光标位置下/上开始寻找一个名称为word的字符串 (n表示下一个，shift+n 表示上一个 匹配到的

内容)

n 光标向下移动n行

0 移动到当前行的首字符   $移动到当前行的尾字符位置

dd 删除当前行  ndd 表示删除光标下的n行

x/X 前/后删除一个字符   nx连续向后删除n个字符

yy 复制光标所在的行  nyy复制下面的n行

u   复原前一个动作

ctrl+r   重做上一个动作

.   重复前一个动作（可以用于重复删除或重复复制粘贴）

ln 为某一个文件在另一个位置建立一个同步的链接

vmstat 查看硬盘被占用了或剩余空间大小

du -sh */  查看内存使用情况

nohup 启动文件名 & 后台永久启动

启动数据库命令

service mysqld start 启动			service mysqld restart 重启