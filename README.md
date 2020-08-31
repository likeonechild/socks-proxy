# socks-proxy
netty写的一个socks代理项目
#部署
使用 mvn assembly:assembly命令打包，打包后可直接nohup java -jar socks-proxy.jar &  启动代理，默认连接端口 18080,可在SocksServer.java中修改默认连接端口
