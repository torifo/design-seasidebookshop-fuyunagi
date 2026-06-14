---
name: design-seasidebookshop-fuyunagi
description: "seaside bookshop landing-page design study — 'fuyunagi' theme/persona (pure HTML/CSS/JS, no build). Use when designing a 'fuyunagi'-style seaside bookshop site aesthetic. 荒れる日は、長い本を. seaside bookshopの「fuyunagi」テーマLPのデザイン参照スキル。"
---

# design-seasidebookshop-fuyunagi

A landing-page **design study** for a fictional **fuyunagi**-theme seaside bookshop (pure HTML + CSS + vanilla JS, no build, GitHub-Pages ready). Use this as a **style / design-system reference** when building a similar aesthetic.

架空の「fuyunagi」テーマのseaside bookshop LP デザイン研究。同種の世界観を作るときの**スタイル／デザインシステム参照**として使う。

## When to use / 使いどころ
- **EN:** designing a 'fuyunagi'-style seaside bookshop site — match its palette, typography and layout discipline.
- **JP:** 「fuyunagi」系のseaside bookshopサイトを設計するとき。配色・タイポ・レイアウト規律を流用。

## Bundled assets / 同梱アセット
This skill folder is the reference implementation — start from these files:
- `index.html` — full page markup
- `style.css` — design tokens (CSS custom properties) + layout
- `script.js` — vanilla JS (if present)
- `README.md` — full bilingual doc, brand context and series links

## Design reference / デザイン参照
_Lifted from the repo README — see README.md for the complete, bilingual version._

### Overview
**seaside bookshop design research series** の「北陸・日本海側の冬」ペルソナ作品。

荒天の日に長く読める地元客・滞在者に向けて、郷土史、民俗、長編小説、冬の料理本を深く見せる。

### Brand
| | |
|--|--|
| **Brand** | 冬凪書房 |
| **Tagline** | 荒れる日は、長い本を。 |
| **Aesthetic** | 雪曇り × 古い倉庫 × 貸出台帳 |
| **Target Persona** | 荒天の日に長く読む地元客・滞在者 |
| **Books** | 郷土史、民俗、長編小説、冬の料理本 |
| **Color** | Ink `#17202a` + Snow `#e8e5dd` + Red `#9e342b` |
| **Display Font** | Noto Serif JP |
| **Body Font** | Zen Kaku Gothic New |

### Design Approach
- 暗い背景と重い明朝体で、冬の海と古い倉庫の密度を作る
- 棚は「土地」「夜」「台所」に絞り、深く読む体験を優先する
- 商品一覧は貸出台帳のようなリストで表示
- 滞在できる読書机や番茶の情報を、購買導線と同じくらい大切に扱う

## Tech / 技術
- Vanilla HTML / CSS — single file (`index.html`)
- Google Fonts: Noto Serif JP, BIZ UDMincho, Zen Kaku Gothic New
- ビルドツール不要

## How to apply / 適用方法
1. Reuse `style.css` custom properties (color / type / spacing tokens) as the design-system base.
2. Copy `index.html` layout as the starting structure, then swap brand name and content.
3. Keep the palette, font pairing and layout discipline described above.

---
> The brand is fictional (design study) — replace all brand/content. Full context: see **`README.md`**.
