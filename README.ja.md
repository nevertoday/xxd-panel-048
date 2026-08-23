<p align="center"><img src="./assets/banner.svg" alt="XXD Panel 048 プロジェクトバナー" width="1200"></p>

<div align="center">

# 🦁 XXD Panel 048

### 被写体の構造的な論理を、透明な設計図として明晰に可視化する

[简体中文](README.md) · [English](README.en.md) · **日本語** · [한국어](README.ko.md) · [العربية](README.ar.md)

</div>

> 透明構造 · 科学図解 · 明澄な単色 · 精密注釈 · 編集的余白

XXD Panel 048 は、認識可能な被写体を工学図面、X-ray 透視図、科学図解、未来のアーカイブの間にある構造設計図へ再構築します。内部は被写体に即して解釈し、一般的な機械部品を付け足しません。

## 美的動機

輪郭・姿勢・関係を固定し、元写真固有の手掛かりを三つ以上保持します。その上で意味のある内部だけを透明化・断面化し、軸線、寸法、ノード、引出線によって一つの読解経路を作ります。明るい背景と元写真由来の主線色、十分な余白を用い、青を固定値にしません。通常の線画、人体の生々しい解剖、恣意的な機械化、過密 HUD、偽の技術文字は拒否します。

完全な仕様：[Skill](SKILL.md) · [原文](references/048-source.md) · [英語生成プロンプト](references/xxd-panel-048-prompt.en.md) · [中国語生成プロンプト](references/xxd-panel-048-prompt.zh-CN.md)

## サンプル

サンプルは制作中です。他の Panel の画像や架空のプレースホルダーは使用しません。将来のサンプルも、固定の被写体、配色、構図、文案、画角にはなりません。[方針](assets/examples/README.md)

## 組み合わせ可能な四つのモード

- `top-bottom`: 元写真適応 `W×2H`、上下を厳密に 50/50。
- `left-right`: 元写真適応 `2W×H`、左右を厳密に 50/50。
- `design-only`: 元写真適応 `W×H`、変換デザインのみ。
- `wallpaper-pack`: スマートフォン、iPad、PC、子ども用腕時計の個別 PNG。

一つまたは複数を選択できます。壁紙は連動型または独立型です。生成前に自動文案、完全一致のカスタム文案、文字なしを決め、対象言語／地域も別途確認します。全出力は PNG で、新しい `~/Desktop/xxd/xxd-panel-048/<fresh-task>/` に保存されます。

## インストールと作者

```bash
git clone https://github.com/nevertoday/xxd-panel-048.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/xxd-panel-048" ~/.codex/skills/xxd-panel-048
```

XXD は Xiaoxiaodong のブランド名の略称です。作者：[@xiaoxiaodong01](https://x.com/xiaoxiaodong01)。個別相談は CNY 299／時間、Skills ユーザー交流グループは一回払い CNY 99 です。Knowledge Planet＋会員プロンプトライブラリは年額 CNY 699 の一回の支払いで両方を利用できます。[Knowledge Planet](https://wx.zsxq.com/group/15554814142882) から加入した場合は、WeChat で Xiaoxiaodong に連絡して[会員プロンプトライブラリ](https://vip.xiaoxiaodong.ai/)の引換コードを受け取ってください。プロンプトライブラリで自動開通した場合は、WeChat で連絡して Knowledge Planet への招待を受けてください。[WeChat](https://xiaoxiaodong.pages.dev/assets/wechat-qr.png)

<p align="center"><a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="XXD WeChat" width="280"></a></p>

<p align="center"><a href="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true"><img src="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true" alt="Buy Me a Coffee" width="180"></a></p>
