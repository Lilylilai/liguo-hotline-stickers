# liguo-hotline-stickers

莉国热线 v0.2 的独立公开贴纸资源仓库。

- `manifest.json` 是客户端读取的稳定清单。
- 历史消息只保存 `sticker_id` / `asset_id`，不保存图片 URL。
- 已投入使用的 ID 与文件不删除；停用时将 `enabled` 改为 `false`。
- 首批 6 张 SVG 是功能验收用测试贴纸，可在保持 ID 和路径稳定的前提下优化画面。

当前贴纸：挥手、抱抱、大笑、思考、睡觉、收到。
