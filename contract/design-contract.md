# Design Contract — 苏俊旭个人主页

## Style Tier & Aesthetic Direction
style: minimal-light (brand-themed)
aesthetic: cozy web / digital garden — 温暖、亲密、手作感、留白呼吸
tone keywords: calm / intimate / contemplative / curated / nostalgic

## Tech Stack + Delivery Type
stack: vanilla HTML + CSS + JS
delivery: pure-static (零外部依赖，双击可离线打开)

## Design Tokens
color.primary:     #7A9B76  (moss green)
color.primary-soft: #C8D8C4
color.primary-deep: #5A7A56
color.accent:      #B07A52  (terracotta)
color.gold:        #BFA058
color.bg:           #F5F0E8  (warm cream)
color.surface:      #FAF6EE
color.bg-soft:      #EFE9DE
color.border:       #D5CDBE
color.border-soft:  #E2DACE
color.text:         #2C2823  (warm charcoal)
color.text-sub:    #5E5750
color.text-faint:  #8A8275
color.text-ghost:  #B0A898

font.display: Georgia, 'Songti SC', 'Noto Serif SC', 'STSong', serif
font.body: -apple-system, BlinkMacSystemFont, 'Segoe UI', 'PingFang SC', 'Microsoft YaHei', sans-serif
font.scale: 12 / 14 / 16 / 20 / 24 / 32 / 40 (px)
radius: sm6 / md10 / lg16
shadow: card 0 2px 16px -6px rgba(43,40,35,0.12)
spacing.unit: 4px base (4/8/12/16/24/32/48/64/80)
layout: max-width 680px (main), 880px (header)
icon: inline SVG (Lucide style, stroke 1.5~2, currentColor)
motion: staggered reveal on scroll (opacity+translateY, 0.6s ease), hover micro-transitions (0.2~0.3s)
bg-texture: subtle radial gradients in moss-soft/gold-soft tones, no flat solid

## Component Spec
- button: pill border, 1.5px solid, hover fills ink
- card: 10px radius, 1px border-soft, hover lift 2px + soft shadow
- tag: pill, bg-soft, text-faint, 0.625rem
- list-item: border-bottom divider, hover padding-left +6px, dot indicator scales
- nav: text links, active gets underline (moss, 1.5px)

## Page List
- index.html | 单页个人主页 | hero + about + research + teaching + works + achievements + philosophy + contact

## Mock Schema
所有内容数据内联在 HTML 中（个人主页无需动态数据源）
