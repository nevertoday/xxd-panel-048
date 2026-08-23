<p align="center"><img src="./assets/banner.svg" alt="XXD Panel 048 프로젝트 배너" width="1200"></p>

<div align="center">

# 🦁 XXD Panel 048

### 대상의 구조 논리를 투명한 설계도 안에서 선명하게 드러내기

[简体中文](README.md) · [English](README.en.md) · [日本語](README.ja.md) · **한국어** · [العربية](README.ar.md)

</div>

> 투명 구조 · 과학 도해 · 맑은 단색 · 정밀 주석 · 편집 여백

XXD Panel 048은 알아볼 수 있는 대상을 공학 도면, X-ray 투시도, 과학 도해, 미래 아카이브 사이의 구조 설계도로 재구성합니다. 내부는 대상 자체에 맞게 해석하며 보편적인 기계 부품을 임의로 덧붙이지 않습니다.

## 미학적 동기

윤곽, 자세, 관계를 고정하고 원본 고유 단서를 세 개 이상 보존합니다. 의미 있는 내부만 투명층과 절개로 드러내고 축선, 치수, 노드, 지시선으로 하나의 읽기 경로를 만듭니다. 밝은 바탕과 원본에서 얻은 주 선색, 넉넉한 여백을 사용하며 파란색을 기본값으로 삼지 않습니다. 일반 선화, 살점 해부, 임의의 기계화, 과밀 HUD, 가짜 기술 문자를 거부합니다.

전체 사양: [Skill](SKILL.md) · [원문](references/048-source.md) · [영문 생성 프롬프트](references/xxd-panel-048-prompt.en.md) · [중문 생성 프롬프트](references/xxd-panel-048-prompt.zh-CN.md)

## 예시

예시는 제작 중입니다. 다른 Panel 이미지나 가짜 플레이스홀더를 빌리지 않습니다. 향후 예시도 고정 주제, 색, 구성, 문구, 화면 비율이 되지 않습니다. [정책](assets/examples/README.md)

## 조합 가능한 네 가지 모드

- `top-bottom`: 원본 적응형 `W×2H`, 정확한 상하 50/50.
- `left-right`: 원본 적응형 `2W×H`, 정확한 좌우 50/50.
- `design-only`: 원본 적응형 `W×H`, 변환 디자인만 출력.
- `wallpaper-pack`: 휴대전화, iPad, PC, 어린이용 시계 PNG 개별 출력.

하나 이상 선택할 수 있고 배경화면은 연결형 또는 독립형입니다. 생성 전에 자동 문구, 정확한 사용자 문구, 무문자 중 하나와 대상 언어／지역을 확인합니다. 모든 결과는 새 `~/Desktop/xxd/xxd-panel-048/<fresh-task>/`에 PNG로 저장됩니다.

## 설치와 제작자

```bash
git clone https://github.com/nevertoday/xxd-panel-048.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/xxd-panel-048" ~/.codex/skills/xxd-panel-048
```

XXD는 Xiaoxiaodong 브랜드 이름의 약자입니다. 제작: [@xiaoxiaodong01](https://x.com/xiaoxiaodong01). 심층 상담은 CNY 299/시간이며 Skills 사용자 교류 그룹은 CNY 99 일회 결제입니다. Knowledge Planet＋회원 프롬프트 라이브러리는 연 CNY 699 한 번의 결제로 두 혜택을 모두 엽니다. [Knowledge Planet](https://wx.zsxq.com/group/15554814142882)에서 가입한 뒤 WeChat으로 Xiaoxiaodong에게 연락해 [회원 프롬프트 라이브러리](https://vip.xiaoxiaodong.ai/) 교환 코드를 받으세요. 프롬프트 라이브러리에서 셀프서비스로 개통한 뒤에는 WeChat으로 연락해 Knowledge Planet 초대를 받으세요. [WeChat](https://xiaoxiaodong.pages.dev/assets/wechat-qr.png)

<p align="center"><a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="XXD WeChat" width="280"></a></p>

<p align="center"><a href="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true"><img src="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true" alt="Buy Me a Coffee" width="180"></a></p>
