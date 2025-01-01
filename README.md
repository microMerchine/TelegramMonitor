### AD -- 机场推广

**机场 - 老百姓自己的机场**：[https://老百姓自己的机场.com](https://老百姓自己的机场.com)  
咱老百姓就得用自己的机场 **老百姓自己的机场** 做用的起的机场



# Telegram关键词监控 使用说明

## 系统与环境要求
- 最新发布版下载：https://github.com/Riniba/TelegramMonitor/releases/latest
- 发布包提供常见的系统版本已经包含运行时。  
- 如需其他可自行编译
- 请注意 使用时需具备**全局代理**或能**直连 Telegram**。  

## 账号与频道准备
- 准备一个 Telegram 账号，该账号需拥有一个或多个可发布消息的频道（Channel）。
- 该账号需对所选频道拥有发布消息的权限。
- 该账号需加入多个群组（Group），软件将监听这些群组中的消息。
- 当群组中出现匹配关键字的消息时，软件会将该消息内容转发至指定频道。

## 使用步骤
1. 确认已完成上述准备工作。
2. 双击运行 `TelegramMonitor.exe`。
3. 输入已经准备好的 Telegram 账号的手机号码，例如：`+8618888888888`。
4. 根据提示输入验证码或二级密码（首次登录时需要，成功登录后再次运行则无需）。
5. 成功登录后，程序会列出您拥有发布权限的频道名称和对应的频道 ID，并提示您选择频道。
6. 最新版的需要用键盘↑↓键选择你要发布消息的频道，然后按 Enter 键选择就行了。
7. 选择完成后，软件会提示已经开始工作，并在所选频道发布一条消息“开始工作”作为标记。
8. 此后请保持软件运行，关闭软件将无法继续监听群消息。
9. 如果需要停止软件请在那个黑框框里面输入stop 然后按Enter键就可以退出软件了 当然最简单的是直接右上角点X关闭

## 关键词设置
- 关键词文件为 `keyword.txt`，软件开始工作后会自动在同级目录创建该文件（也可手动提前创建）。

- 每次修改关键词文件无需重启软件即可生效。

- 每行一个关键词。

- 关键词匹配方式：
  - 全字匹配举例：“服务器”可匹配“有人要服务器吗？”  
  - 模糊匹配举例：“我?吃”可匹配“我今天吃了一顿大餐”或“我昨天吃了一顿小龙虾”。
  
  

> **重要提示：**  
> 只会监控群组的消息。请保持软件运行，以持续监听。

## 其他说明
- 本软件免费无毒，可在虚拟机中运行进行长期挂机。
- 有问题请联系 Telegram：[https://t.me/Riniba](https://t.me/Riniba)
- Telegram交流群组 [https://t.me/RinibaGroup](https://t.me/RinibaGroup)

  

---

