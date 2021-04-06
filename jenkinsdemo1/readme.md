1.部署需要有一个sterter-web的maven

1.使用命令
maven clean package

打包成jar包
命令行运行
java -jar xxx.jar  //在所在路径


jenkins使用
linux环境下  java ,maven ,git,docker 使用上

启动
nohup java -jar /xxx/xxx.war > /xxxx/xxx.out & 

把 jenkins.war包传到Linux  里面，再命令

有时出现输入重定向问题,要再点击回车

查看进程
ps -ef | grep jenkins

注意镜像要改成国内的

重启jenkins,安装插件

实例配置

配置新任务
manage jenkins
global tool configuration

记录各个的路径

项目要dockerfile

项目pom文件加打包类型和构件

先上传到git

再git导入

构件
execue shell

码云地址
https://gitee.com/xiaozhang-123/project2

jenkins执行
JENKINS_URL/job/project2/build?token=TOKEN_NAME