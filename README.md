<p align="center"><img src="./assets/banner.svg" alt="XXD Panel 038 project banner" width="1200"></p>

<div align="center">

# 🦁 XXD Panel 038

### 把照片重新缝成一段温暖的人文拼布故事

[![Codex Skill](https://img.shields.io/badge/Codex-Skill-000000?style=flat-square)](./SKILL.md)
[![Modes](https://img.shields.io/badge/Modes-4-D96952?style=flat-square)](#)
[![Output](https://img.shields.io/badge/Output-PNG-5D8D83?style=flat-square)](#)

<strong>简体中文</strong> · <a href="README.en.md">English</a> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a>

</div>

<div>

> 源图布色 · 真实毛边 · 手缝针脚 · 主动留白 · 隐藏情绪

照片没有说出的关系被重构为当代拼布：格纹棉布、亚麻、水洗粗麻、毛边、补丁和可见手缝线。留白承担陪伴、距离、成长、停留、归属、偶遇或时间。

## 为什么需要这套 Skill

这套风格依赖每一张源图，不是可替换内容的装饰预设。它遵循这条重构链：

```text
读出未说出口的关系 → 保留三个辨识线索 → 删除字面场景 → 用源图色布片裁出必要形态 → 层叠、裁切、穿插并让局部越界 → 让针脚与毛边真实可见 → 用留白承载距离与时间 → 绣入一句未说完般的短语
```

如果换成无关照片后，辨识度、构造、位置、材质、颜色、留白与文案都不发生实质变化，结果就不属于这套 Panel。

## 视觉契约

- 保留至少三个源图线索，同时把人物、动物、器物、建筑或景观简化成有意义的布片形态。
- 真实呈现格纹棉布、亚麻、水洗粗麻、补丁布、毛边纤维、手缝针脚、交叉缝线与轻微不规则接合，并保持编辑设计的克制。
- 每张源图生成不同的温润、清爽、人文布艺色组；保留原图冷暖与一个鲜活焦点，不套米黄灰棕、莫兰迪或人为旧化。
- 以不对称、层叠、裁切、局部越界和大面积主动留白表达陪伴、距离、成长、停留、归属、偶遇或时间。
- 手工感来自纤维和缝制，不来自污渍、泛黄、脏旧或儿童手工课质感。

完整审美约束与拒绝项写在 Skill 和生产提示词中；它们保留原始提示词的审美动机，但不会把历史 3:4 画布变成隐藏默认值。 [SKILL.md](SKILL.md) · [production prompt](references/xxd-panel-038-prompt.en.md)

## 样张 · 来自 X

> [小小东（@xiaoxiaodong01）](https://x.com/xiaoxiaodong01/status/2090807474467291568) · 2026-08-21<br>
> GPT2 x 布艺 x 情绪 x 美学提示词 x VOL.038

<table>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2090807474467291568"><img src="./assets/examples/sample-01.jpg" alt="XXD Panel 038 样张 1"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2090807474467291568"><img src="./assets/examples/sample-02.jpg" alt="XXD Panel 038 样张 2"></a></td>
  </tr>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2090807474467291568"><img src="./assets/examples/sample-03.jpg" alt="XXD Panel 038 样张 3"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2090807474467291568"><img src="./assets/examples/sample-04.jpg" alt="XXD Panel 038 样张 4"></a></td>
  </tr>
</table>

<p align="center"><a href="https://x.com/xiaoxiaodong01/status/2090807474467291568">查看原推文与完整提示词 →</a></p>

这些样张用于展示 038 的美学动机，不会把样张中的主体、构图、配色、文案或旧画幅变成生成参考或当前默认值。

## 四种可组合输出模式

可用 `1`、`1+3`、`1、2、4` 或 `全部` 选择一个或多个模式；`全部` 每张源图输出 7 个独立 PNG。模式确定后，Skill 会在生图前继续询问整张最终成品的画幅：`3:4` 原提示词画幅、明确跟随原图、常用比例，或自定义比例／准确像素。不会再静默套用源图尺寸。

| 模式 | 画幅逻辑 | 成品 |
| --- | --- | --- |
| `top-bottom` | 用户确认的整张成品画幅 | 一次生成完整画布：高保真原图在上，038 设计在下，约 50/50 |
| `left-right` | 用户确认的整张成品画幅 | 一次生成完整画布：高保真原图在左，038 设计在右，约 50/50 |
| `design-only` | 用户确认的整张成品画幅 | 038 设计铺满画布，不显示原照片 |
| `wallpaper-pack` | 逐设备确认 | 手机、iPad、电脑、儿童手表四张独立 PNG |

双联默认把原图作为高保真垫图／编辑参考，用一套完整提示词直接生成一张整体成品，让摄影、设计、色彩、光线、文字与含义自然呼应。只有完整画布针对性重试仍失败、用户要求原片逐像素不变、当前通道无法实现目标画幅，或需要无创像素校准时，才启用确定性拼合兜底。

壁纸可选连贯或独立。连贯套装先批准一张 iPad 定调图，另外三张分别参考原图＋同一定调图重新构图；独立套装的四张都只参考原图。两者都不会裁切其他设备成品或串联衍生图。

## 文案与语言

正式生成前确认自动文案、准确自定义文案或无文字；语言跟随目标受众而不是命令语言，用户给出的准确文案逐字保留。

本项目的文案规则： 从源图隐藏的情绪、动作、关系或隐喻提炼一个短语，而不是只写物名或地点。用目标语言中自然的细线刺绣、手缝线迹或克制手写，让文字在缝线与负空间中延续、停顿或隐藏。

## 完整画布优先与位图边界

图像模型负责整张成品的审美重构，双联也默认一次直出完整画布。`scripts/compose_panel.py` 只保留为条件明确的兜底、无创尺寸校准和只读审计工具，不再预先规划每次任务，也不评价审美是否成功。

全部交付为 PNG 位图。每次调用都在 `~/Desktop/xxd/` 下创建新任务；已配置图像通道只返回脱敏状态，不公开供应商、端点、凭据、请求头、提示词、响应或账户信息。SVG、HTML、Canvas、图表和程序绘图不能替代最终作品。

## 开始使用

```bash
git clone https://github.com/nevertoday/xxd-panel-038.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/xxd-panel-038" ~/.codex/skills/xxd-panel-038
```

Claude Code 用户可把同一文件夹链接到 `~/.claude/skills/xxd-panel-038`. 安装后请重启 Agent 会话。

```text
$xxd-panel-038
Use this photograph, ask me for the modes and copy setting, then generate fresh raster outputs.
```

完整规格: [Skill 工作流](SKILL.md) · [原始风格档案](references/038-source.md) · [英文生产提示词](references/xxd-panel-038-prompt.en.md) · [中文生产提示词](references/xxd-panel-038-prompt.zh-CN.md)

## 关于 XXD

XXD 是小小东品牌名的缩写，本项目由小小东创建并维护： [@xiaoxiaodong01](https://x.com/xiaoxiaodong01).

## 支持与会员

### 深度咨询 · 299 元／小时

一对一深入咨询 Skills 的使用与工作流，通过微信联系小小东预约。 [WeChat](https://xiaoxiaodong.pages.dev/assets/wechat-qr.png)

### 小小东 Skills 用户交流群 · 99 元

一次付费加入 Skills 用户交流群，用于工作流分享和用户间讨论；不包含按小时计费的一对一咨询。

### 知识星球＋成员提示词库 · 699 元／年

知识星球和成员提示词库是一份会员费用：从任一入口开通后，通过微信联系小小东获取另一边的权益。

[Knowledge Planet](https://wx.zsxq.com/group/15554814142882) · [Member Prompt Library](https://vip.xiaoxiaodong.ai/)

<p align="center"><a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="XXD WeChat" width="280"></a></p>

<div align="center"><strong>布片留下形态，空白留下我们之间的距离。</strong></div>

---

<div align="center">

## ☕ 支持这个开源项目

算力赞助请使用小小东自己的微信或支付宝赞赏码；赞助完全自愿，不改变开源项目的访问权限。


<table><tr>
<td align="center"><a href="https://colors.xiaoxiaodong.ai/docs/images/wechat-reward-qr.png"><img src="https://colors.xiaoxiaodong.ai/docs/images/wechat-reward-qr.png" alt="XXD WeChat reward" width="180"></a><br><strong>WeChat</strong></td>
<td align="center"><a href="https://colors.xiaoxiaodong.ai/docs/images/alipay-reward-qr.png"><img src="https://colors.xiaoxiaodong.ai/docs/images/alipay-reward-qr.png" alt="XXD Alipay reward" width="180"></a><br><strong>Alipay</strong></td>
</tr></table>

</div>
</div>
