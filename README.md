# -1
记录电脑配置操作文件

<一>
2023/6/27
Anaconda环境无损从C盘移植到D盘最快捷的方式==>
将Anaconda环境文件移植到D盘，并将D盘的新文件夹创建快捷方式在旧目录下。
步骤：
①将虚拟环境 envs整个目录剪切到D盘，我是在D盘新建了个文件夹 D:\anaconda env。
②进入cmd环境，以管理员方式运行。
③输入命令

MKLINK /D "C:\用户目录\anaconda3\envs" "D:\AncondaEnv"
③该命令的含义是在C盘指定目录下创建快捷链接"envs"到"D:\AnacondaEnv"，注意原来的envs文件夹必须要删除，否则会提示路径已经存在，无法创建。
③命令执行成功后。在C盘目录下已经创建envs快捷方式.

<二>
