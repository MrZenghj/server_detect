# server_detect
服务环境检测工具，并将java项目打包成.exe（windows系统版本）

目的
1. 通过sigar工具获取服务器的相关信息。
   获取的信息有：java环境、系统CPU、IO、内存总量、余存量以及使用率的使用情况、网关等相关信息。

2. 通过java调用CMD命令查看当前端口的占用情况。
  

3. ping服务网关的延迟和丢包率
	 ping 8.8.8.8的延迟和丢包率
	 ping www.baidu.com的延迟和丢包率
   
将获取到的信息保存到指定文件中，本项目保存到我的桌面中。新建一个ServerProperty.txt

4. 将java项目做成.exe文件 方便用户运行
