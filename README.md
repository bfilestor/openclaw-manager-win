一个轻量的Windows版本OpenClaw桌面管理工具。

## 前提条件
- 按照openclaw官方文档，在C:\Users\<当前用户>\.openclaw 目录安装好openclaw

## 功能列表

- 快速进入openclaw Web控制面板
- 启动，停止，重启openclaw
- 编辑修改openclaw.json,并可回滚，对比变化

## 编译命令

```go
 go build -ldflags "-H windowsgui" -o OpenClawGatewayGUI.exe
```