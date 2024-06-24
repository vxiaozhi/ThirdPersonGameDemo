# ThirdPersonGameDemo

基于 UE4 第三人称模板开发

## 功能规划

- 支持客户端联网
- 自定义连接服务器
- 显示玩家姓名（由服务器根据玩家的端类型、名称等信息分配）、血条
- 当有新玩家进入时，广播给其它玩家。



## 启动

```
# start Client
H:\UGit\UnrealEngine\Engine\Binaries\Win64\UE4Editor.exe "H:\UGit\ThirdPersonGameDemo\ThirdPersonGame.uproject" -game 

# start server
H:\UGit\UnrealEngine\Engine\Binaries\Win64\UE4Editor.exe "H:\UGit\ThirdPersonGameDemo\ThirdPersonGame.uproject" -game -server -log

```


## 参考

- [第三人称模板](https://docs.unrealengine.com/4.27/zh-CN/Resources/Templates/ThirdPerson/)