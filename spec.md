# 冬凪書房 — design-seasidebookshop-fuyunagi Spec

**Status:** Approved  
**Author:** torifo  
**Created:** 2026-05-24  
**Updated:** 2026-05-24

## 1. Overview

### Problem Statement
日本海側の冬の海辺にある書店を、一般的な爽やかな海辺表現で作ると土地の気配が消える。荒天の日に長く読む体験が伝わらない。

### Goal
「冬凪書房」という架空書店を、冬の海、古い漁具倉庫、郷土の本を軸に実装する。短時間で回遊するサイトではなく、重く深く読むサイトにする。

### Non-Goals
- 明るいリゾート表現
- 軽いZINE中心の棚
- カート・決済機能

## 2. User Stories

| ID | Persona | Want to | So that |
|---|---|---|---|
| US-01 | 地元の読書家 | 郷土史や民俗の棚を見たい | 土地の本を探せる |
| US-02 | 冬の滞在者 | 長く読める本を知りたい | 荒天の日の過ごし方を決められる |
| US-03 | 来店予定者 | 読書席や営業時間を知りたい | 滞在できるか判断できる |

## 3. Functional Requirements

| ID | Requirement | Priority |
|---|---|---|
| FR-01 | 暗色ヒーローと冬の海写真 | P0 |
| FR-02 | 棚3分類 | P0 |
| FR-03 | 長読みリスト | P0 |
| FR-04 | 囲炉裏まわり情報 | P1 |
| FR-05 | 840px以下で1カラム化 | P0 |

## 4. Architecture

```text
index.html
├── header.mast
├── section.hero
├── section.stacks
├── section.longread
├── section.irori
└── footer
```

## 5. Design System

```css
--ink:  #17202a;
--snow: #e8e5dd;
--ash:  #a9b0ae;
--wood: #4d3429;
--red:  #9e342b;
```

## 6. Testing Strategy

| Layer | Scenarios |
|---|---|
| Desktop | 暗色コントラスト、棚3列、長読みリスト |
| Mobile | 長読みリストの縦積み、画像高さ |
| Contrast | 暗背景の本文可読性 |
