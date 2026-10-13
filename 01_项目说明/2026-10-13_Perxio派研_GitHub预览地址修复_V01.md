# GitHub 预览地址修复 V01

日期：2026-10-13

## 文件整理结果

- 使用：`README.md`、Git 远端配置及公开网站和仓库地址。
- 历史记录：2026-09-27 的同步与上线记录保留原样，记录当时的用户名和地址。
- 归档：无需新增归档或删除文件。
- 最终输出：更新 `README.md` 的当前链接，并以本文件记录改址原因。

## 原因与处理

- GitHub 仓库的账号名由 `Jean0708` 改为 `Raddie-Jean`；仓库仍为 `perxio`。
- 旧预览地址 `https://jean0708.github.io/perxio/` 返回 HTTP 404。
- 新预览地址 `https://raddie-jean.github.io/perxio/` 返回 HTTP 200，并包含 Perxio 页面内容。
- 旧仓库地址会重定向到新仓库地址；本地 `origin` 已更新为 `https://github.com/Raddie-Jean/perxio.git`。
- 更新 README 中的仓库及预览链接。网页内容与 V05 历史原件未修改。

## 验证

- 在线页面内容与 `docs/index.html` 逐字节一致。
- 使用本机 Chrome 验证新地址返回 HTTP 200、页面标题与工作台显示正常、语言切换有效，控制台无错误。
- Git 推送和本地工作区状态检查通过。
