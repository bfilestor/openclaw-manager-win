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

## 注意事项

- windows下启动和停止openclaw耗时较长，需要耐心等待，如果启动失败，或停止失败，可多点击几次停止再重新启动
- 当出现“Gateway service missing.”时表示停止完成
- 当出现“If the gateway is supervised, stop it with: openclaw gateway stop” 则需要重新点击启动

## 截图
[!控制按钮页面](images/win-01.png)

[!配置修改页面](images/win-02.png)