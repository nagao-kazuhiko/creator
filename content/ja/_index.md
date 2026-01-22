---
title: Kushiro Creator Project
description: クリエイターをクリエイトする
content_blocks:
  - _bookshop_name: hero
    heading:
      title: 釧路工業高等専門学校
      content: |-
        高専の実践力に基づいたクリエイティブ・イノベーター育成プログラム
      width: 10
    background:
      color: primary
      subtle: true
    illustration:
      image: /img/sunrise.jpg
      ratio: 16x9
      width: 6
    links:
      - title: さらに詳しく
        url: https://gethinode.com/docs
        icon: fas chevron-right
    orientation: horizontal
    justify: center


  - _bookshop_name: articles
    heading:
      title: News
      align: start
    input:
      section: blog
      reverse: true
      sort: date
      keywords: featured
    hide-empty: false
    header-style: none
    more:
      title: もっとみる
    padding: 0
    limit: 3
    class: border-0 card-zoom card-body-margin

  - _bookshop_name: articles
    heading:
      title: Projects
      align: start
    background:
      background: body-tertiary
    hide-empty: false
    input:
      section: projects
      reverse: false
      sort: date
    more:
      title: もっとみる
    cols: 1
    padding: 4
    limit: 2
    icon-style: fa-5x
    header-style: none
    footer-style: tags
    orientation: horizontal-sm
    class: border-1 card-emphasize
---


