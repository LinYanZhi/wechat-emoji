# wechat-emoji-public — 项目指令

## 这是什么

**微信表情包公开仓库**：微信官方默认表情素材 111 个 PNG（128×128 透明底），按面板顺序重排，附短代码 / 中文释义 / Unicode 映射。纯静态资源（无构建步骤）。

- ⚠️ **目录名 ≠ 仓库名**：本地目录 `wechat-emoji-public`，remote 是 `github.com/LinYanZhi/wechat-emoji`（main）。别误以为两个仓库。
- 本地还有非 git 的 `wechat-emoji\`（加工区：assets 原图 / ps1 处理脚本 / HANDOFF.md），是**发布前的加工目录**，别和发布仓库混淆。

## 结构

```
assets/           111 个表情 PNG（NNN_短代码.png）
manifest.json     机器可读清单（order/file/name/meaning/type/unicode/source）
manifest.csv      人读清单（Excel 可开）
demo.html         仿微信聊天示例页（内嵌清单，离线可用）
preview-grid.png  全部表情拼图预览
```

## 纪律

- 表情图是**腾讯版权资产，禁止商用**；改发布内容只动整理成果（manifest / README / demo），图片素材来自 `wechat-emoji\` 加工区。
- 目录结构 / 命名规则（`NNN_短代码.png`）保持稳定，改动需同步 manifest。
