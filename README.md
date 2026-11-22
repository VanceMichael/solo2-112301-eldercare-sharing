# 家庭照护数据共享的趋势口径与授权变更

照护资料包含合成的步数、睡眠、提醒和亲属授权区间，支持关系字段核对。

项目中的记录和字段约定均为本地合成资料，不能代表真实个人、机构或交易。`fixtures/schema.json` 说明资料字段，`fixtures/records.json` 提供少量可复现的交接记录。

使用 Node.js 22.23.4。首次准备可执行 `npm ci --ignore-scripts --offline`，检查资料使用 `npm run check:materials`，运行构建检查使用 `npm run build`，运行测试使用 `npm test`。项目只依赖 Node.js 标准库。
