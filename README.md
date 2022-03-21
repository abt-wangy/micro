# micro
go-micro微服务
## 安装的插件
protoc-gen-go
protoc-gen-micro
protoc
etcd 端口号:2379
##编译proto文件
protoc -I=./proto --go_out=. --micro_out=. ./proto/hello.proto