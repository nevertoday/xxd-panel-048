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

## 作例 · X より

> [小小東（@xiaoxiaodong01）](https://x.com/xiaoxiaodong01/status/2091374796517130282) · 2026年8月23日<br>
> GPT2 × ブループリント × 構造分解 × 美学プロンプト × VOL.048

<table>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091374796517130282"><img src="./assets/examples/sample-01.jpg" alt="XXD Panel 048 作例 1"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091374796517130282"><img src="./assets/examples/sample-02.jpg" alt="XXD Panel 048 作例 2"></a></td>
  </tr>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091374796517130282"><img src="./assets/examples/sample-03.jpg" alt="XXD Panel 048 作例 3"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091374796517130282"><img src="./assets/examples/sample-04.jpg" alt="XXD Panel 048 作例 4"></a></td>
  </tr>
</table>

<p align="center"><a href="https://x.com/xiaoxiaodong01/status/2091374796517130282">元の投稿と完全なプロンプトを見る →</a></p>

これらの作例は 048 の美的意図を示すものであり、作例の被写体、構図、配色、コピー、旧キャンバス比率が生成時の参照や現在の既定値になることはありません。

## 組み合わせ可能な4つの出力

`1`、`1+3`、`1,2,4`、`全部` で一つまたは複数を選べます。`全部` は元画像ごとに7点の独立PNGを出力します。モード選択後、生成前に完成画像全体の画角を必ず確認します：元プロンプトの `3:4`、明示的な元画像比率、一般的な比率、またはカスタム比率／正確なピクセルです。元画像寸法を暗黙には適用しません。

| モード | 画角ルール | 成果物 |
| --- | --- | --- |
| `top-bottom` | ユーザー確認済みの完成画角 | 完成キャンバスを一度に生成：上に高忠実度の元画像、下に 048 デザイン、約50/50 |
| `left-right` | ユーザー確認済みの完成画角 | 完成キャンバスを一度に生成：左に高忠実度の元画像、右に 048 デザイン、約50/50 |
| `design-only` | ユーザー確認済みの完成画角 | 048 デザインが全画面を満たし、元画像は表示しない |
| `wallpaper-pack` | 端末ごとに確認 | スマートフォン、iPad、デスクトップ、子ども用ウォッチの個別PNG |

二連モードは元画像を高忠実度の編集／参照入力として使い、完全なスタイルプロンプト一式で完成画面を直接生成します。写真、デザイン、色、光、文字、意味を一体化するためです。決定論的な合成は、完成画面の再試行後も失敗した場合、原画像のピクセル完全保持を明示された場合、生成経路が指定画角に対応しない場合、または無劣化の最終ピクセル調整が必要な場合だけ使います。

壁紙は連動または独立を選べます。連動はiPad基準作を一つ承認し、他の端末を元画像＋同じ基準作から個別に再構成します。独立は各端末が元画像だけを参照します。どちらも他端末の成果を切り抜かず、派生を連鎖しません。

## 画像モデルの優先順位

GPT Image 2 を既定の第一候補とします。高忠実度の参照画像、生成前の完成キャンバス確認、二連モードの完成画面一括生成、条件を満たした場合だけのスクリプト合成という既存の流れは変わりません。

現在のツールまたは設定済み経路から実際に利用でき、元画像の忠実度、完成画角、対象言語の文字、連動壁紙の複数参照を満たせる場合は、Seedance 5.0 Pro、Nano Banana Pro（Gemini Image Pro）、Nano Banana 2（Gemini Image Flash）、その他の互換ビットマップモデルも利用できます。代替モデルが変更できるのは生成経路だけで、モード、画角、文案、言語、壁紙関係、完成キャンバス優先の方針は変更できません。

適切な経路がない場合は、画像生成ツールを有効にするか API Key を提供するようユーザーに案内します。ユーザーが提供した認証情報は現在のタスクで利用できますが、返信やログに再表示・記録・開示しません。明示的な依頼がない限り、長期保存やプロバイダー、アカウント、課金、グローバル経路の設定変更も行いません。

## インストールと作者

```bash
git clone https://github.com/nevertoday/xxd-panel-048.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/xxd-panel-048" ~/.codex/skills/xxd-panel-048
```

XXD は Xiaoxiaodong のブランド名の略称です。作者：[@xiaoxiaodong01](https://x.com/xiaoxiaodong01)。個別相談は CNY 299／時間、Skills ユーザー交流グループは一回払い CNY 99 です。Knowledge Planet＋会員プロンプトライブラリは年額 CNY 699 の一回の支払いで両方を利用できます。[Knowledge Planet](https://wx.zsxq.com/group/15554814142882) から加入した場合は、WeChat で Xiaoxiaodong に連絡して[会員プロンプトライブラリ](https://vip.xiaoxiaodong.ai/)の引換コードを受け取ってください。プロンプトライブラリで自動開通した場合は、WeChat で連絡して Knowledge Planet への招待を受けてください。[WeChat](https://xiaoxiaodong.pages.dev/assets/wechat-qr.png)

<p align="center"><a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="XXD WeChat" width="280"></a></p>

<p align="center"><a href="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true"><img src="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true" alt="Buy Me a Coffee" width="180"></a></p>
