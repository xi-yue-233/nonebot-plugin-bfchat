## 命令列表

| 命令 | 作用 | 备注 |
| --------------------------------------------------------- | ------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------- |
| `{p}bf help` | 返回帮助文档 | |
| `{p}bf init` | 初始化本群绑定功能，未初始化的群，群员不能使用绑定功能 | 仅SUPERUSER和群管理员有效 |
| `{p}bf1 [玩家id]`<br />`{p}bfv [玩家id]` <br />`{p}bf2042 [玩家id]`| 查询 `[玩家id]`的bf1/bfv/bf2042战绩信息 | 如果查询玩家是me，则会将数据保存至本地<br />且一小时内再次查询不会再发起请求 |
| `{p}bf1 [玩家id] weapons`<br />`{p}bfv [玩家id] weapons` <br />`{p}bf2042 [玩家id] weapons`| 查询 `[玩家id]`的bf1/bfv/bf2042武器信息 | |
| `{p}bf1 [玩家id] vehicles`<br />`{p}bfv [玩家id] vehicles` <br />`{p}bf2042 [玩家id] vehicles`| 查询 `[玩家id]`的bf1/bfv/bf2042载具信息 | |
| `{p}bf1 bind [玩家id]`<br />`{p}bfv bind [玩家id]` <br />`{p}bf2042 bind [玩家id]`| 将 对应游戏的 `[玩家id]`与命令发送人绑定，绑定后可使用 `me `代替 `{p}[玩家id]`<br />例如 `{p}bfv me` | bf1、bfv与bf2042绑定不互通 |
| `{p}bf1 list`<br />`{p}bfv list` | 列出该服务器所有已绑定的bf1/bfv玩家信息 | 使用本地数据，不会自动更新 |
| `{p}bf1 server [服务器名]`<br />`{p}bfv server [服务器名]` | 查询名字包含 `[服务器名]`的bf1/bfv服务器 | |