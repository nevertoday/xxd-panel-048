<p align="center"><img src="./assets/banner.svg" alt="XXD Panel 048 项目横幅" width="1200"></p>

<div align="center">

# 🦁 XXD Panel 048

### 让主体的结构逻辑，在透明蓝图中清晰显影

**简体中文** · [English](README.en.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [العربية](README.ar.md)

</div>

> 透明结构 · 科学图解 · 清透单色 · 精确注释 · 编辑留白

XXD Panel 048 把照片中的可识别主体重构为介于工程图纸、X-ray 透视、科学图解与未来档案之间的结构蓝图。它不机械堆砌零件，而是根据对象本身解释内部：器物看组件，建筑看空间，交通工具看动力，植物看生长，人物与动物看姿态、动作或服装层次。

## 审美动机

```text
锁定身份、轮廓、姿态与关系 → 保留三个线索 → 决定“内部”对该主体意味着什么 → 选择性剖切与透明显影 → 用轴线、尺度、节点和引线建立阅读路径 → 从源图提炼清透单色 → 保持大量留白 → 让文案精确绑定结构
```

- 外轮廓始终一眼可辨，内部结构必须有对象依据。
- 半透明、剖面、爆炸分解与局部放大只解释真正重要的信息。
- 浅色背景＋一个源图衍生主线色＋少量明暗层级；不默认蓝色。
- 拒绝普通线稿、血肉解剖、任意机械化、满版 HUD、霓虹赛博与伪技术文字。

完整规则：[Skill 工作流](SKILL.md) · [原始提示词](references/048-source.md) · [中文生产提示词](references/xxd-panel-048-prompt.zh-CN.md) · [英文生产提示词](references/xxd-panel-048-prompt.en.md)

## 样张 · 来自 X

> [小小东（@xiaoxiaodong01）](https://x.com/xiaoxiaodong01/status/2091374796517130282) · 2026 年 8 月 23 日<br>
> GPT2 × 蓝图 × 拆解 × 美学提示词 × VOL.048

<table>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091374796517130282"><img src="./assets/examples/sample-01.jpg" alt="XXD Panel 048 样张 1"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091374796517130282"><img src="./assets/examples/sample-02.jpg" alt="XXD Panel 048 样张 2"></a></td>
  </tr>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091374796517130282"><img src="./assets/examples/sample-03.jpg" alt="XXD Panel 048 样张 3"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091374796517130282"><img src="./assets/examples/sample-04.jpg" alt="XXD Panel 048 样张 4"></a></td>
  </tr>
</table>

<p align="center"><a href="https://x.com/xiaoxiaodong01/status/2091374796517130282">查看原推文与完整提示词 →</a></p>

这些样张用于展示 048 的美学动机，不会把样张中的主体、构图、配色、文案或旧画幅变成生成参考或当前默认值。

## 四种可组合模式

| 模式 | 未指定尺寸 | 成果物 |
| --- | --- | --- |
| `top-bottom` | 源图自适应 `W×2H` | 完整原图在上＋同尺寸设计图在下，严格 50/50 |
| `left-right` | 源图自适应 `2W×H` | 完整原图在左＋同尺寸设计图在右，严格 50/50 |
| `design-only` | 源图自适应 `W×H` | 只显示变化设计 |
| `wallpaper-pack` | 设备分别指定 | 手机、iPad、电脑、儿童手表四张 PNG |

可选择一个或多个模式；选择全部时每张源图输出 7 张 PNG。壁纸可选“连贯”或“独立”：连贯套装共同参考原图与同一批准定调图，绝不裁切或串联衍生图。

## 文案、语言与输出

生成前确认自动文案、准确自定义文案或无文字，并单独确认目标语言／地区。自动文案是与身份、功能、动作或象征意义绑定的短标题和必要技术注释；用户准确文案逐字保留。普通模式按源图自适应，全部结果为 PNG，并写入新的 `~/Desktop/xxd/xxd-panel-048/<fresh-task>/` 任务目录。

## 安装

```bash
git clone https://github.com/nevertoday/xxd-panel-048.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/xxd-panel-048" ~/.codex/skills/xxd-panel-048
```

Claude Code 用户可链接到 `~/.claude/skills/xxd-panel-048`。安装后重启 Agent 会话，并使用 `$xxd-panel-048`。

## 关于 XXD 与支持

XXD 是小小东品牌名的缩写。创建与维护者：[@xiaoxiaodong01](https://x.com/xiaoxiaodong01)。深度咨询 299 元／小时；Skills 用户交流群 99 元，一次付费入群；知识星球＋成员提示词库 699 元／年，一次年费同时开通两项权益。若从[知识星球](https://wx.zsxq.com/group/15554814142882)开通，请微信联系小小东领取[成员提示词库](https://vip.xiaoxiaodong.ai/)兑换码；若在成员提示词库自助开通，请微信联系小小东邀请进入知识星球。[微信](https://xiaoxiaodong.pages.dev/assets/wechat-qr.png)

<p align="center"><a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="XXD WeChat" width="280"></a></p>

<div align="center">

## ☕ 支持这个开源项目

算力赞助完全自愿，不改变开源项目的访问权限。

<table><tr><td align="center"><a href="https://colors.xiaoxiaodong.ai/docs/images/wechat-reward-qr.png"><img src="https://colors.xiaoxiaodong.ai/docs/images/wechat-reward-qr.png" alt="XXD 微信赞赏" width="180"></a><br><strong>WeChat</strong></td><td align="center"><a href="https://colors.xiaoxiaodong.ai/docs/images/alipay-reward-qr.png"><img src="https://colors.xiaoxiaodong.ai/docs/images/alipay-reward-qr.png" alt="XXD 支付宝赞赏" width="180"></a><br><strong>Alipay</strong></td></tr></table>

</div>
