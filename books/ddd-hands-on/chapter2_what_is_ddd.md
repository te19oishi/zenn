---
title: 'ドメイン駆動設計 (DDD) とは'
---

# ドメインとは

「**ドメイン**」という言葉は、さまざまな分野で使われています。たとえば、ドメインという言葉は、インターネット上のウェブサイトを識別するために使用されるものです。また、数学の分野で使われることもあります。ドメイン駆動設計 (DDD) においても、この「ドメイン」という言葉が重要な役割を果たします。ドメイン駆動設計における「ドメイン」とは、**ソフトウェアが解決しようとしている特定の問題領域**を指します。

**問題領域**とは、業務内の具体的な問題やニーズを指します。これは、ソフトウェアが扱う業務の本質的な側面であり、ユーザーの要求、課題、または業務上の問題を含みます。問題領域を理解することは、効果的なソフトウェアを設計する上で不可欠です。

ここで、ドメインとその問題領域の具体例をいくつかあげます。

| ドメイン                   | 問題領域                                                                                         |
| -------------------------- | ------------------------------------------------------------------------------------------------ |
| **オンライン書店**         | 在庫量とオンライン表示が一致しない問題を、自動更新機能を持つ在庫管理システムで解決したい         |
|                            | 顧客の購入パターンが把握しにくい問題を、顧客行動分析ツールを用いて解決したい                     |
|                            | クレジットカード詐欺や不正利用のリスクを、強化されたセキュリティを備えた決済システムで減らしたい |
| **病院の患者管理システム** | 緊急時の患者情報へのアクセスが遅い問題を、迅速アクセス機能のある電子カルテシステムで改善したい   |
|                            | 患者の長い待ち時間と非効率なスケジュール問題を、改良されたオンライン予約システムで解決したい     |
| **銀行の口座管理システム** | 口座取引のセキュリティが不十分な問題を、高度なセキュリティ機能と取引監視システムで強化したい     |

これらの例からもわかるように、**ドメイン**はそれぞれの業界や組織に固有のものであり、その中にはさまざまな問題領域が存在します。ソフトウェア開発において、このドメインを正確に理解し、それを反映したモデルを構築することが、非常に重要になります。

# ドメイン駆動設計の必要性

今日、数多くのソフトウェアが開発されていますが、その中で本当にビジネス価値を提供するものはどれだけあるでしょうか？ソフトウェア開発は単にコードを書くだけの作業ではありません。例に挙げたような実際の業務要件や問題点を的確に捉え、それを効果的に解決するためのシステムを構築する必要があります。この業務要件の核心を深く理解し、それをシステムに反映するためのアプローチが、ドメイン駆動設計（DDD）です。

## 伝統的な開発との違い

伝統的なソフトウェア開発では、先に技術を選定しそれに基づいて要件を構築したり、ドメインに詳しくないソフトウェア開発者がドメインを理解することなく開発を進めたりします。この結果、ソフトウェアはビジネスの要件を満たさず、本当に価値のあるものとはなりません。また、ドメインに詳しくない開発者が開発を進めると、ドメインの知識が不足しているため、ドメインモデルを正確に構築することができません。

ドメイン駆動設計では、この問題を解決するために、ビジネスの要件やドメインの知識を最前線に置き、それを基盤とした設計・開発を行います。ソフトウェア開発者は、業務知識を深め、その知識をもとにしたドメインモデルを構築することで、ビジネス要件を直接的にソフトウェアに反映させることができます。これにより、ソフトウェアがビジネスの真のニーズを満たし本当に価値があるものとなるのです。

# まとめ

- 「ドメイン」とはソフトウェアが解決しようとしている特定の問題領域を意味する
- ドメイン駆動設計 (DDD) はドメインを中心にしたソフトウェア開発アプローチ
- 「ユビキタス言語」は開発者・ビジネスステークホルダー間の共通言語

本章ではドメイン駆動設計においてドメインが非常に重要ということを学びました。
次章からドメイン駆動設計のアプローチを詳しく見ていきます。まず初めに第 1 部では、戦略的設計であるドメインモデリングやコンテキストマップの基本的な概念と原則を学びます。次に第 2 部では、戦術的設計であるドメインモデルを実際にコードに反映させる方法を学びます。
