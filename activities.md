---
title: 活動記録
layout: page
header-title: Activities
tagline: 勉強会で使用した資料と、当サークルで作成した問題セットを掲載しています。
permalink: "/activities.html"
ref: activities
order: 3
---

<style>
table {
    line-height: 18px;
}
</style>

**勉強会資料および合宿の問題解説のスライドは、[hcpc-hokudai/archive](https://github.com/hcpc-hokudai/archive) リポジトリにもまとめられています。``git clone`` ・ダウンロード等可能ですので、ぜひご活用ください。**

# 勉強会資料

<!-- ///// template /////
| タイトル | リンク                                       |
|----------|----------------------------------------------|
|          | [Archive (PDF)]({{ site.hcpc_archive_url }}) |
/// template end ///// -->

{% details 入門者向け (For Beginners) %}
| タイトル                                                                    | リンク                                                               |
|-----------------------------------------------------------------------------|----------------------------------------------------------------------|
| プログラミングコンテスト入門                                                | [Archive (PDF)]({{ site.hcpc_archive_url }}introduction_001.pdf)     |
| Introduction to Programming                                                 | [Archive (PDF)]({{ site.hcpc_archive_url }}introduction_002.pdf) [Archive (pptx)]({{ site.hcpc_archive_url }}introduction_002.pptx)   |
| プログラミングコンテスト基礎テクニック                                      | [Archive (PDF)]({{ site.hcpc_archive_url }}introduction_003.pdf)     |
| プログラミングコンテスト入門 - AtCoder Beginners Selection を解いてみよう - | [Archive (PDF)]({{ site.hcpc_archive_url }}introduction_abs_001.pdf) |

{% enddetails %}

{% details 動的計画法 (Dynamic Programming) %}

| タイトル                                                 | リンク                                                                                                                                            |
|----------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------|
| 動的計画法: DP                                           | [Archive (PDF)]({{ site.hcpc_archive_url }}dynamic_programming_001.pdf)                                                                           |
| 動的計画法を極める！ (蟻本 3-4 + α)                     | [Archive (PDF)]({{ site.hcpc_archive_url }}dynamic_programming_002.pdf) [Archive (pptx)]({{ site.hcpc_archive_url }}dynamic_programming_002.pptx) |
| EDPC 解説 (A 〜 E)                                       | [Archive (PDF)]({{ site.hcpc_archive_url }}dynamic_programming_edpc_001.pdf)                                                                      |
| 基礎的な動的計画法トピック - ICPC 国内予選突破に向けて - | [Archive (PDF)]({{ site.hcpc_archive_url }}dynamic_programming_fundamental_dp.pdf)                                                                |
| 確率 DP を極めよう - 確率と期待値の問題解説 -            | [Archive (PDF)]({{ site.hcpc_archive_url }}dynamic_programming_probability_dp.pdf)                                                                |
| 文字列 DP (応用編) - 文字列を華麗に扱おう -              | [Archive (PDF)]({{ site.hcpc_archive_url }}dynamic_programming_string_dp.pdf)                                                                     |
| こわくない全方位木 DP                                    | [Archive (PDF)]({{ site.hcpc_archive_url }}dynamic_programming_rerooting.pdf)                                                                     |

{% enddetails %}

{% details グラフ (Graph) %}

| タイトル                               | リンク                                                                       |
|----------------------------------------|------------------------------------------------------------------------------|
| グラフネットワーク 〜フロー & カット〜 | [Archive (PDF)]({{ site.hcpc_archive_url }}graph_flow_001.pdf)               |
| 最大流（Ford-Fulkerson）・最小カット   | [Archive (PDF)]({{ site.hcpc_archive_url }}graph_flow_002.pdf)               |
| 最大流（Dinic）・最小流量制約付き最大流| [Archive (PDF)]({{ site.hcpc_archive_url }}graph_flow_003.pdf)               |
| グラフマスターに、俺はなる！           | [Archive (PDF)]({{ site.hcpc_archive_url }}graph_master_001.pdf)             |
| 木のテクニック（DFS, オイラーツアー, HL 分解）| [Archive (PDF)]({{ site.hcpc_archive_url }}graph_tree_001.pdf)         |
| 最大マッチングアルゴリズム             | [Archive (PDF)]({{ site.hcpc_archive_url }}graph_max_matching_001.pdf)       |
| ICPC 練習会 〜全域木いろいろ〜         | [Archive (PDF)]({{ site.hcpc_archive_url }}graph_mst_001.pdf)                |
| グラフを扱おう: 最短路問題             | [Archive (PDF)]({{ site.hcpc_archive_url }}graph_shortest_path_001.pdf)      |
| 最短経路問題 & 最小全域木              | [Archive (PDF)]({{ site.hcpc_archive_url }}graph_shortest_path_mst_001.pdf)  |
| 強連結成分分解&トポロジカルソート      | [Archive (PDF)]({{ site.hcpc_archive_url }}graph_scc_001.pdf)                |
| トポロジカルソート                     | [Archive (PDF)]({{ site.hcpc_archive_url }}graph_topological_sort_001.pdf) [Archive (pptx)]({{ site.hcpc_archive_url }}graph_topological_sort_001.pptx) |
| 最小全域技列挙（マニアック）           | [Archive (PDF)]({{ site.hcpc_archive_url }}graph_listing_spanning_tree_001.pdf) |
| 木幅と動的計画法（マニアック）         | [Archive (PDF)]({{ site.hcpc_archive_url }}graph_treewidth_001.pdf) |

{% enddetails %}

{% details 数学 (Mathematics) %}

| タイトル                                                        | リンク                                                                       |
|-----------------------------------------------------------------|------------------------------------------------------------------------------|
| 写像 12 相を題材にした、基本的な数え上げ問題に対するアプローチ  | [Archive (PDF)]({{ site.hcpc_archive_url }}math_twelvefold_way_001.pdf)      |
| xor に関連したテクニック                                        | [Archive (PDF)]({{ site.hcpc_archive_url }}math_xor_001.pdf)    |
| 数え上げテクニック Hard                                         | [Archive (PDF)]({{ site.hcpc_archive_url }}math_enumeration_hard_001.pdf)    |
| 競技プログラミングのための FFT - 多項式乗算の高速化ことはじめ - | [Archive (PDF)]({{ site.hcpc_archive_url }}math_fft_001.pdf)                 |
| 競技プログラミング だれでもわかる FFT/NTT 入門                 | [Archive (PDF)]({{ site.hcpc_archive_url }}math_fft_002.pdf)                 |
| 包除原理 - 解ける数え上げの範囲を広げよう -                     | [Archive (PDF)]({{ site.hcpc_archive_url }}math_inclusion_exclusion_001.pdf) |

{% enddetails %}

{% details 文字列 (String) %}

| タイトル                          | リンク                                                                                |
|-----------------------------------|---------------------------------------------------------------------------------------|
| 文字列アルゴリズム                | [Archive (PDF)]({{ site.hcpc_archive_url }}string_algorithms_001.pdf)                 |
| ローリングハッシュと Suffix Array | [Archive (PDF)]({{ site.hcpc_archive_url }}string_rollinghash_suffixarray_001.pdf) |

{% enddetails %}

{% details データ構造 (Data Structure) %}

| タイトル                        | リンク                                                                            |
|---------------------------------|-----------------------------------------------------------------------------------|
| Binary Indexed Tree             | [Archive (PDF)]({{ site.hcpc_archive_url }}structure_binary_indexed_tree_001.pdf) |
| 蟻本輪講 データ構造 (P69 〜 86) | [Archive (PDF)]({{ site.hcpc_archive_url }}structure_data_strc_001.pdf)           |
| RMQ クエリ処理                  | [Archive (PDF)]({{ site.hcpc_archive_url }}structure_rmq_001.pdf)                 |
| 非再帰セグ木                    | [Archive (PDF)]({{ site.hcpc_archive_url }}structure_segtree_001.pdf)             |
| UnionFind                       | [Archive (PDF)]({{ site.hcpc_archive_url }}structure_union_find_001.pdf)          |

{% enddetails %}

{% details 幾何 (Geometry) %}

| タイトル                 | リンク                                                       |
|--------------------------|--------------------------------------------------------------|
| ICPC 勉強会 〜幾何入門〜 | [Archive (PDF)]({{ site.hcpc_archive_url }}geometry_001.pdf) |
| 計算幾何入門 〜円〜      | [Archive (PDF)]({{ site.hcpc_archive_url }}geometry_002.pdf) |
| 計算幾何入門 〜多角形〜  | [Archive (PDF)]({{ site.hcpc_archive_url }}geometry_003.pdf) |
| 計算幾何入門 〜入門とゲームプログラミング〜 | [Archive (PDF)]({{ site.hcpc_archive_url }}geometry_004.pdf) |

{% enddetails %}

{% details その他アルゴリズム (Other Algorithms) %}

| タイトル                                    | リンク                                                                               |
|---------------------------------------------|--------------------------------------------------------------------------------------|
| 二分探索をはじめからていねいに              | [Archive (PDF)]({{ site.hcpc_archive_url }}algorithm_binary_search_001.pdf)          |
| すべての基本 "全探索"                       | [Archive (PDF)]({{ site.hcpc_archive_url }}algorithm_bruteforce_001.pdf) [Archive (pptx)]({{ site.hcpc_archive_url }}algorithm_bruteforce_001.pptx)           |
| Convex Hull Trick                           | [Archive (PDF)]({{ site.hcpc_archive_url }}algorithm_convex_hull_trick_001.pdf)      |
| 座標圧縮                                    | [Archive (PDF)]({{ site.hcpc_archive_url }}algorithm_coordinate_compression_001.pdf) |
| 半分全列挙                                  | [Archive (PDF)]({{ site.hcpc_archive_url }}algorithm_meet_in_the_middle_001.pdf)    |
| ソート (整列)                               | [Archive (PDF)]({{ site.hcpc_archive_url }}algorithm_sort_001.pdf)                   |
| 繰り返し 2 乗法 (バイナリ法)                | [Archive (PDF)]({{ site.hcpc_archive_url }}algorithm_binary_001.pdf)                 |
| 分割統治法 - 問題を小さく分けてまとめよう - | [Archive (PDF)]({{ site.hcpc_archive_url }}algorithm_divide_and_conquer_001.pdf)     |

{% enddetails %}

{% details 実装テクニック (Implementation Technique) %}

| タイトル                                          | リンク                                                                              |
|---------------------------------------------------|-------------------------------------------------------------------------------------|
| C++ における実装テクニック                        | [Archive (PDF)]({{ site.hcpc_archive_url }}etc_implement_technique_001.pdf)         |
| Introduction to Using Standard Template Libraries | [Archive (PDF)]({{ site.hcpc_archive_url }}etc_standard_template_libraries_001.pdf) |

{% enddetails %}

# HCPC で出題した問題セット

ぜひ解いてみてください！解説スライドも公開しています。

<!-- ///// template /////

- [合宿の案内 ()]()
- コンテスト日程: yyyy 年 mm 月 dd 日 hh:mm 〜 hh:mm
- [問題セットへのリンク]()

|問題タイトル|解説|
|---|---|
|[A: ]()||
|[B: ]()||
|[C: ]()||
|[D: ]()||
|[E: ]()||
|[F: ]()||
|[G: ]()||

///// template end ///// -->

{% details 2020 %}

### 北海道大学プログラミング合宿 2020 Day1
- [合宿の案内 (connpass)]({{ site.reg_connpass_url }}179414)
- コンテスト日程: 2020 年 9 月 14 日 13:00 〜 16:00
- [問題セットへのリンク]({{ site.aoj_contest_url }}HUPC2020Day1)

| 問題タイトル                                           | 解説                                                                 |
|--------------------------------------------------------|----------------------------------------------------------------------|
| [A: 最安保証]({{ site.aoj_hupc_url }}3164)             | [Archive (PDF)]({{ site.hcpc_archive_url }}hupc/2020/hupc2020_A.pdf) |
| [B: 三角形足し算]({{ site.aoj_hupc_url }}3165)         | [Archive (PDF)]({{ site.hcpc_archive_url }}hupc/2020/hupc2020_B.pdf) |
| [C: Not Found]({{ site.aoj_hupc_url }}3166)            | [Archive (PDF)]({{ site.hcpc_archive_url }}hupc/2020/hupc2020_C.pdf) |
| [D: Many Points]({{ site.aoj_hupc_url }}3167)          | [Archive (PDF)]({{ site.hcpc_archive_url }}hupc/2020/hupc2020_D.pdf) |
| [E: えびちゃんを捕獲せよ]({{ site.aoj_hupc_url }}3168) | [Archive (PDF)]({{ site.hcpc_archive_url }}hupc/2020/hupc2020_E.pdf) |
| [F: n-角錐グラフ]({{ site.aoj_hupc_url }}3169)         | [Archive (PDF)]({{ site.hcpc_archive_url }}hupc/2020/hupc2020_F.pdf) |
| [G: Freqs]({{ site.aoj_hupc_url }}3170)                | [Archive (PDF)]({{ site.hcpc_archive_url }}hupc/2020/hupc2020_G.pdf) |
| [H: Traditional Company]({{ site.aoj_hupc_url }}3171)  | [Archive (PDF)]({{ site.hcpc_archive_url }}hupc/2020/hupc2020_H.pdf) |

### 会津大学競技プログラミング合宿 2020 day3
- [合宿の案内 (connpass)]({{ site.reg_connpass_url }}183498)
- コンテスト日程: 2020 年 9 月 21 日 13:00 〜 16:00
- [問題セットへのリンク]({{ site.aoj_contest_url }}ACPC2019Day3)

| 問題タイトル                                                       | 解説                                                                 |
|--------------------------------------------------------------------|----------------------------------------------------------------------|
| [A: 雲の移動]({{ site.aoj_hupc_url }}3185)                         | [Archive (PDF)]({{ site.hcpc_archive_url }}acpc/2020/acpc2020_A.pdf) |
| [B: 累積差]({{ site.aoj_hupc_url }}3186)                           | [Archive (PDF)]({{ site.hcpc_archive_url }}acpc/2020/acpc2020_B.pdf) |
| [C: mod reap]({{ site.aoj_hupc_url }}3187)                         | [Archive (PDF)]({{ site.hcpc_archive_url }}acpc/2020/acpc2020_C.pdf) |
| [D: mod rally]({{ site.aoj_hupc_url }}3188)                        | [Archive (PDF)]({{ site.hcpc_archive_url }}acpc/2020/acpc2020_D.pdf) |
| [E: mod rush]({{ site.aoj_hupc_url }}3189)                         | [Archive (PDF)]({{ site.hcpc_archive_url }}acpc/2020/acpc2020_E.pdf) |
| [F: Ribbons on A Perfect Binary Tree]({{ site.aoj_hupc_url }}3190) | [Archive (PDF)]({{ site.hcpc_archive_url }}acpc/2020/acpc2020_F.pdf) |
| [G: 水やり]({{ site.aoj_hupc_url }}3191)                           | [Archive (PDF)]({{ site.hcpc_archive_url }}acpc/2020/acpc2020_G.pdf) |
| [H: パラレル H 言ったら勝ちゲーム]({{ site.aoj_hupc_url }}3192)    | [Archive (PDF)]({{ site.hcpc_archive_url }}acpc/2020/acpc2020_H.pdf) |

{% enddetails %}
{% details 2019 %}

### 立命館大学競技プログラミング合宿 2019 Day3

- [合宿の案内 (ATND)]({{ site.reg_atnd_url }}103718)
- コンテスト日程: 2019 年 3 月 7 日 10:00 〜 13:00
- [問題セットへのリンク]({{ site.aoj_contest_url }}RitsCamp19Day3)

| 問題タイトル                                         | 解説                                                                 |
|------------------------------------------------------|----------------------------------------------------------------------|
| [A: 情報検索]({{ site.aoj_hupc_url }}2930)           | [Archive (PDF)]({{ site.hcpc_archive_url }}rupc/2019/rupc2019_A.pdf) |
| [B: 括弧を語る数]({{ site.aoj_hupc_url }}2931)       | [Archive (PDF)]({{ site.hcpc_archive_url }}rupc/2019/rupc2019_B.pdf) |
| [C: 約数ゲーム]({{ site.aoj_hupc_url }}2932)         | [Archive (PDF)]({{ site.hcpc_archive_url }}rupc/2019/rupc2019_C.pdf) |
| [D: 矢]({{ site.aoj_hupc_url }}2933)                 | [Archive (PDF)]({{ site.hcpc_archive_url }}rupc/2019/rupc2019_D.pdf) |
| [E: 往復文字列]({{ site.aoj_hupc_url }}2934)         | [Archive (PDF)]({{ site.hcpc_archive_url }}rupc/2019/rupc2019_E.pdf) |
| [F: 赤黒そーるじぇむ]({{ site.aoj_hupc_url }}2935)   | [Archive (PDF)]({{ site.hcpc_archive_url }}rupc/2019/rupc2019_F.pdf) |
| [G: Donuts Orientation]({{ site.aoj_hupc_url }}2936) | [Archive (PDF)]({{ site.hcpc_archive_url }}rupc/2019/rupc2019_G.pdf) |

### 北海道大学プログラミング合宿 2019 Day1

- [合宿の案内 (ATND)]({{ site.reg_atnd_url }}105815)
- コンテスト日程: 2019 年 7 月 14 日 14:30 〜 17:30
- [問題セットへのリンク]({{ site.aoj_contest_url }}HUPC2019Day1)

| 問題タイトル                                      | 解説                                                                           |
|---------------------------------------------------|--------------------------------------------------------------------------------|
| [A: four tea]({{ site.aoj_hupc_url }}2960)        | [Archive (PDF)]({{ site.hcpc_archive_url }}hupc/2019/day1/hupc2019_day1_A.pdf) |
| [B: 自身の 2 倍]({{ site.aoj_hupc_url }}2961)     | [Archive (PDF)]({{ site.hcpc_archive_url }}hupc/2019/day1/hupc2019_day1_B.pdf) |
| [C: 短絡評価]({{ site.aoj_hupc_url }}2962)        | [Archive (PDF)]({{ site.hcpc_archive_url }}hupc/2019/day1/hupc2019_day1_C.pdf) |
| [D: 貪欲が最適？]({{ site.aoj_hupc_url }}2963)    | [Archive (PDF)]({{ site.hcpc_archive_url }}hupc/2019/day1/hupc2019_day1_D.pdf) |
| [E: 最短経路の復元]({{ site.aoj_hupc_url }}2964)  | [Archive (PDF)]({{ site.hcpc_archive_url }}hupc/2019/day1/hupc2019_day1_E.pdf) |
| [F: グリッドの番号]({{ site.aoj_hupc_url }}2965)  | [Archive (PDF)]({{ site.hcpc_archive_url }}hupc/2019/day1/hupc2019_day1_F.pdf) |
| [G: Treasure Hunter]({{ site.aoj_hupc_url }}2966) | [Archive (PDF)]({{ site.hcpc_archive_url }}hupc/2019/day1/hupc2019_day1_G.pdf) |

### 北海道大学プログラミング合宿 2019 Day2

- [合宿の案内 (ATND)]({{ site.reg_atnd_url }}105815)
- コンテスト日程: 2019 年 7 月 15 日 10:00 〜 13:00
- [問題セットへのリンク]({{ site.aoj_contest_url }}HUPC2019Day2)
- 有志による作問 (staff: drken, idsigma, tempura0224, tsutaj, tubuann)

| 問題タイトル                                               | 解説                                                                           |
|------------------------------------------------------------|--------------------------------------------------------------------------------|
| [A: Hokkaido University Easy]({{ site.aoj_hupc_url }}2952) | [Archive (PDF)]({{ site.hcpc_archive_url }}hupc/2019/day2/hupc2019_day2_AB.pdf) |
| [B: Hokkaido University Hard]({{ site.aoj_hupc_url }}2953) | [Archive (PDF)]({{ site.hcpc_archive_url }}hupc/2019/day2/hupc2019_day2_AB.pdf) |
| [C: 串刺し]({{ site.aoj_hupc_url }}2954)                   | [Archive (PDF)]({{ site.hcpc_archive_url }}hupc/2019/day2/hupc2019_day2_C.pdf) |
| [D: Two Colors Sort]({{ site.aoj_hupc_url }}2955)          | [Archive (PDF)]({{ site.hcpc_archive_url }}hupc/2019/day2/hupc2019_day2_D.pdf) |
| [E: ジャム]({{ site.aoj_hupc_url }}2956)                   | [Archive (PDF)]({{ site.hcpc_archive_url }}hupc/2019/day2/hupc2019_day2_E.pdf) |
| [F: MOD Rush]({{ site.aoj_hupc_url }}2957)                 | [Archive (PDF)]({{ site.hcpc_archive_url }}hupc/2019/day2/hupc2019_day2_F.pdf) |
| [G: 木]({{ site.aoj_hupc_url }}2958)                       | [Archive (PDF)]({{ site.hcpc_archive_url }}hupc/2019/day2/hupc2019_day2_G.pdf) |
| [H: Revenge of UMG]({{ site.aoj_hupc_url }}2959)           | [Archive (PDF)]({{ site.hcpc_archive_url }}hupc/2019/day2/hupc2019_day2_H.pdf) |

### 会津大学競技プログラミング合宿 2019 Day3

- [合宿の案内 (ATND)]({{ site.reg_atnd_url }}107805)
- コンテスト日程: 2019 年 9 月 20 日 10:00 〜 13:00
- [問題セットへのリンク]({{ site.aoj_contest_url }}ACPC2019Day3)

| 問題タイトル                                            | 解説                                                                 |
|---------------------------------------------------------|----------------------------------------------------------------------|
| [A: 間違い探し]({{ site.aoj_hupc_url }}3107)            | [Archive (PDF)]({{ site.hcpc_archive_url }}acpc/2019/acpc2019_A.pdf) |
| [B: テトリス]({{ site.aoj_hupc_url }}3108)              | [Archive (PDF)]({{ site.hcpc_archive_url }}acpc/2019/acpc2019_B.pdf) |
| [C: カニサル暗号]({{ site.aoj_hupc_url }}3109)          | [Archive (PDF)]({{ site.hcpc_archive_url }}acpc/2019/acpc2019_C.pdf) |
| [D: Many Decimal Integers]({{ site.aoj_hupc_url }}3110) | [Archive (PDF)]({{ site.hcpc_archive_url }}acpc/2019/acpc2019_D.pdf) |
| [E: 総和の切り取り]({{ site.aoj_hupc_url }}3111)        | [Archive (PDF)]({{ site.hcpc_archive_url }}acpc/2019/acpc2019_E.pdf) |
| [F: 部分文字列分解]({{ site.aoj_hupc_url }}3112)        | [Archive (PDF)]({{ site.hcpc_archive_url }}acpc/2019/acpc2019_F.pdf) |
| [G: Restricted DFS]({{ site.aoj_hupc_url }}3113)          | [Archive (PDF)]({{ site.hcpc_archive_url }}acpc/2019/acpc2019_G.pdf) |

{% enddetails %}

{% details 2018 %}

### 立命館大学競技プログラミング合宿 2018 Day3

- [合宿の案内 (ATND)]({{ site.reg_atnd_url }}94033)
- コンテスト日程: 2018 年 3 月 28 日 10:00 〜 13:00
- [問題セットへのリンク]({{ site.aoj_contest_url }}RitsCamp18Day3)

| 問題タイトル                                                   | 解説                                                                 |
|----------------------------------------------------------------|----------------------------------------------------------------------|
| [A: 沢山の種類の林檎]({{ site.aoj_hupc_url }}2867)             | [Archive (PDF)]({{ site.hcpc_archive_url }}rupc/2018/rupc2018_A.pdf) |
| [B: 階層的計算機]({{ site.aoj_hupc_url }}2868)                 | [Archive (PDF)]({{ site.hcpc_archive_url }}rupc/2018/rupc2018_B.pdf) |
| [C: AA グラフ]({{ site.aoj_hupc_url }}2869)                    | [Archive (PDF)]({{ site.hcpc_archive_url }}rupc/2018/rupc2018_C.pdf) |
| [D: 素因数分解の多様性]({{ site.aoj_hupc_url }}2870)           | [Archive (PDF)]({{ site.hcpc_archive_url }}rupc/2018/rupc2018_D.pdf) |
| [E: ブロッコリー？カリフラワー？]({{ site.aoj_hupc_url }}2871) | [Archive (PDF)]({{ site.hcpc_archive_url }}rupc/2018/rupc2018_E.pdf) |
| [F: 最短距離を伸ばすえびちゃん]({{ site.aoj_hupc_url }}2872)   | [Archive (PDF)]({{ site.hcpc_archive_url }}rupc/2018/rupc2018_F.pdf) |
| [G: 検閲により置換]({{ site.aoj_hupc_url }}2873)               | [Archive (PDF)]({{ site.hcpc_archive_url }}rupc/2018/rupc2018_G.pdf) |

### 会津大学競技プログラミング合宿 2018 Day3

- [合宿の案内 (ATND)]({{ site.reg_atnd_url }}98718)
- コンテスト日程: 2018 年 9 月 21 日 10:00 〜 13:00
- [問題セットへのリンク]({{ site.aoj_contest_url }}ACPC2018Day3)

| 問題タイトル                                    | 解説                                                                 |
|-------------------------------------------------|----------------------------------------------------------------------|
| [A: IP アドレス]({{ site.aoj_hupc_url }}2889)   | [Archive (PDF)]({{ site.hcpc_archive_url }}acpc/2018/acpc2018_A.pdf) |
| [B: Pivots]({{ site.aoj_hupc_url }}2890)        | [Archive (PDF)]({{ site.hcpc_archive_url }}acpc/2018/acpc2018_B.pdf) |
| [C: な○りカット]({{ site.aoj_hupc_url }}2891)  | [Archive (PDF)]({{ site.hcpc_archive_url }}acpc/2018/acpc2018_C.pdf) |
| [D: しりとり圧縮]({{ site.aoj_hupc_url }}2892)  | [Archive (PDF)]({{ site.hcpc_archive_url }}acpc/2018/acpc2018_D.pdf) |
| [E: 均衡な辺削除]({{ site.aoj_hupc_url }}2893)  | [Archive (PDF)]({{ site.hcpc_archive_url }}acpc/2018/acpc2018_E.pdf) |
| [F: 01 文字列と窓]({{ site.aoj_hupc_url }}2894) | [Archive (PDF)]({{ site.hcpc_archive_url }}acpc/2018/acpc2018_F.pdf) |
| [G: 回文部分列]({{ site.aoj_hupc_url }}2895)    | [Archive (PDF)]({{ site.hcpc_archive_url }}acpc/2018/acpc2018_G.pdf) |

{% enddetails %}

{% details 2017 %}

### 立命館大学競技プログラミング合宿 2017 Day3

- [合宿の案内 (ATND)]({{ site.reg_atnd_url }}85691)
- コンテスト日程: 2017 年 3 月 24 日 10:00 〜 13:00
- [問題セットへのリンク]({{ site.aoj_contest_url }}RitsCamp17Day3)

| 問題タイトル                                                    | 解説                                                                 |
|-----------------------------------------------------------------|----------------------------------------------------------------------|
| [A: アルファベットブロック]({{ site.aoj_hupc_url }}2816)        | [Archive (PDF)]({{ site.hcpc_archive_url }}rupc/2017/rupc2017_A.pdf) |
| [B: だんすなうｗｗｗ]({{ site.aoj_hupc_url }}2817)              | [Archive (PDF)]({{ site.hcpc_archive_url }}rupc/2017/rupc2017_B.pdf) |
| [C: 今川焼きマン]({{ site.aoj_hupc_url }}2818)                  | [Archive (PDF)]({{ site.hcpc_archive_url }}rupc/2017/rupc2017_C.pdf) |
| [D: 歪みの国]({{ site.aoj_hupc_url }}2819)                      | [Archive (PDF)]({{ site.hcpc_archive_url }}rupc/2017/rupc2017_D.pdf) |
| [E: バイナリ列]({{ site.aoj_hupc_url }}2820)                    | [Archive (PDF)]({{ site.hcpc_archive_url }}rupc/2017/rupc2017_E.pdf) |
| [F: 木を隠すのなら森の中]({{ site.aoj_hupc_url }}2821)          | [Archive (PDF)]({{ site.hcpc_archive_url }}rupc/2017/rupc2017_F.pdf) |
| [G: 恋のジュンレツ Run! Run! Run!]({{ site.aoj_hupc_url }}2822) | [Archive (PDF)]({{ site.hcpc_archive_url }}rupc/2017/rupc2017_G.pdf) |

### 会津大学競技プログラミング合宿 2017 Day3

- [合宿の案内 (ATND)]({{ site.reg_atnd_url }}90222)
- コンテスト日程: 2017 年 9 月 20 日 10:00 〜 13:00
- [問題セットへのリンク]({{ site.aoj_contest_url }}ACPC2017Day3)

| 問題タイトル                                                 | 解説                                                                 |
|--------------------------------------------------------------|----------------------------------------------------------------------|
| [A: A-Z-]({{ site.aoj_hupc_url }}2838)                       | [Archive (PDF)]({{ site.hcpc_archive_url }}acpc/2017/acpc2017_A.pdf) |
| [B: えびちゃんと数列]({{ site.aoj_hupc_url }}2839)           | [Archive (PDF)]({{ site.hcpc_archive_url }}acpc/2017/acpc2017_B.pdf) |
| [C: たったひとつの部分列]({{ site.aoj_hupc_url }}2840)       | [Archive (PDF)]({{ site.hcpc_archive_url }}acpc/2017/acpc2017_C.pdf) |
| [D: 優柔不断]({{ site.aoj_hupc_url }}2841)                   | [Archive (PDF)]({{ site.hcpc_archive_url }}acpc/2017/acpc2017_D.pdf) |
| [E: たい焼きマスターと食べ盛り]({{ site.aoj_hupc_url }}2842) | [Archive (PDF)]({{ site.hcpc_archive_url }}acpc/2017/acpc2017_E.pdf) |
| [F: 掛け算は楽しい]({{ site.aoj_hupc_url }}2843)             | [Archive (PDF)]({{ site.hcpc_archive_url }}acpc/2017/acpc2017_F.pdf) |
| [G: ほぼ無限グリコ]({{ site.aoj_hupc_url }}2844)             | [Archive (PDF)]({{ site.hcpc_archive_url }}acpc/2017/acpc2017_G.pdf) |

{% enddetails %}

{% details 2016 %}

### 立命館大学競技プログラミング合宿 2016 Day3

- [合宿の案内 (ATND)]({{ site.reg_atnd_url }}74939)
- コンテスト日程: 2016 年 3 月 8 日 10:00 〜 13:00
- [問題セットへのリンク]({{ site.aoj_contest_url }}RitsCamp16Day3)

| 問題タイトル                                             | 解説                                                                 |
|----------------------------------------------------------|----------------------------------------------------------------------|
| [A: マイナンバー]({{ site.aoj_hupc_url }}2772)           | [Archive (PDF)]({{ site.hcpc_archive_url }}rupc/2016/rupc2016_A.pdf) |
| [B: 周期数列]({{ site.aoj_hupc_url }}2773)               | [Archive (PDF)]({{ site.hcpc_archive_url }}rupc/2016/rupc2016_B.pdf) |
| [C: 成長する点]({{ site.aoj_hupc_url }}2774)             | [Archive (PDF)]({{ site.hcpc_archive_url }}rupc/2016/rupc2016_C.pdf) |
| [D: Complex Oracle]({{ site.aoj_hupc_url }}2775)         | [Archive (PDF)]({{ site.hcpc_archive_url }}rupc/2016/rupc2016_D.pdf) |
| [E: Arai's]({{ site.aoj_hupc_url }}2776)                 | [Archive (PDF)]({{ site.hcpc_archive_url }}rupc/2016/rupc2016_E.pdf) |
| [F: きっちり]({{ site.aoj_hupc_url }}2777)               | [Archive (PDF)]({{ site.hcpc_archive_url }}rupc/2016/rupc2016_F.pdf) |
| [G: 運命力]({{ site.aoj_hupc_url }}2778)                 | [Archive (PDF)]({{ site.hcpc_archive_url }}rupc/2016/rupc2016_G.pdf) |
| [H: われわれの努力について]({{ site.aoj_hupc_url }}2779) | [Archive (PDF)]({{ site.hcpc_archive_url }}rupc/2016/rupc2016_H.pdf) |

### 会津大学競技プログラミング合宿 2016 Day3

- [合宿の案内 (ATND)]({{ site.reg_atnd_url }}79743)
- コンテスト日程: 2016 年 9 月 19 日 10:00 〜 13:00
- [問題セットへのリンク]({{ site.aoj_contest_url }}ACPC2016Day3)

| 問題タイトル                                           | 解説                                                                 |
|--------------------------------------------------------|----------------------------------------------------------------------|
| [A: 席取り]({{ site.aoj_hupc_url }}2798)               | [Archive (PDF)]({{ site.hcpc_archive_url }}acpc/2016/acpc2016_A.pdf) [Archive (pptx)]({{ site.hcpc_archive_url }}acpc/2016/acpc2016_A.pptx) |
| [B: 山手線ゲーム]({{ site.aoj_hupc_url }}2799)         | [Archive (PDF)]({{ site.hcpc_archive_url }}acpc/2016/acpc2016_B.pdf) [Archive (pptx)]({{ site.hcpc_archive_url }}acpc/2016/acpc2016_B.pptx) |
| [C: Mod! Mod!]({{ site.aoj_hupc_url }}2800)            | [Archive (PDF)]({{ site.hcpc_archive_url }}acpc/2016/acpc2016_C.pdf) |
| [D: 日焼け]({{ site.aoj_hupc_url }}2801)               | [Archive (PDF)]({{ site.hcpc_archive_url }}acpc/2016/acpc2016_D.pdf) |
| [E: 鬼畜ババ抜き]({{ site.aoj_hupc_url }}2802)         | [Archive (PDF)]({{ site.hcpc_archive_url }}acpc/2016/acpc2016_E.pdf) [Archive (pptx)]({{ site.hcpc_archive_url }}acpc/2016/acpc2016_E.pptx) |
| [F: 風呂がオーバーフロー]({{ site.aoj_hupc_url }}2803) | [Archive (PDF)]({{ site.hcpc_archive_url }}acpc/2016/acpc2016_F.pdf) |
| [G: 最小包含矩形]({{ site.aoj_hupc_url }}2804)         | [Archive (PDF)]({{ site.hcpc_archive_url }}acpc/2016/acpc2016_G.pdf) [Archive (pptx)]({{ site.hcpc_archive_url }}acpc/2016/acpc2016_G.pptx) |

{% enddetails %}

{% details 2015 %}

### 立命館大学競技プログラミング合宿 2015 Day3

- [合宿の案内 (ATND)]({{ site.reg_atnd_url }}62742)
- コンテスト日程: 2015 年 3 月 16 日 10:00 〜 13:00
- [問題セットへのリンク]({{ site.aoj_contest_url }}RitsCamp15Day3)

| 問題タイトル                                       | 解説                                                                 |
|----------------------------------------------------|----------------------------------------------------------------------|
| [A: A-Z キャット]({{ site.aoj_hupc_url }}2669)     | [Archive (PDF)]({{ site.hcpc_archive_url }}rupc/2015/rupc2015_A.pdf) |
| [B: 塾の時間割]({{ site.aoj_hupc_url }}2670)       | [Archive (PDF)]({{ site.hcpc_archive_url }}rupc/2015/rupc2015_B.pdf) |
| [C: デジタル時計]({{ site.aoj_hupc_url }}2671)     | [Archive (PDF)]({{ site.hcpc_archive_url }}rupc/2015/rupc2015_C.pdf) |
| [D: 郵便局員を救え]({{ site.aoj_hupc_url }}2672)   | [Archive (PDF)]({{ site.hcpc_archive_url }}rupc/2015/rupc2015_D.pdf) |
| [E: 切り刻む気か？]({{ site.aoj_hupc_url }}2673)   | [Archive (PDF)]({{ site.hcpc_archive_url }}rupc/2015/rupc2015_E.pdf) |
| [F: 異常検知]({{ site.aoj_hupc_url }}2674)         | [Archive (PDF)]({{ site.hcpc_archive_url }}rupc/2015/rupc2015_F.pdf) |
| [G: カードの迷宮]({{ site.aoj_hupc_url }}2675)     | [Archive (PDF)]({{ site.hcpc_archive_url }}rupc/2015/rupc2015_G.pdf) |
| [H: タイピングゲーム]({{ site.aoj_hupc_url }}2676) | [Archive (PDF)]({{ site.hcpc_archive_url }}rupc/2015/rupc2015_H.pdf) |

### 会津大学競技プログラミング合宿 2015 Day3

- [合宿の案内 (ATND)]({{ site.reg_atnd_url }}69709)
- コンテスト日程: 2015 年 9 月 23 日 10:00 〜 13:00
- [問題セットへのリンク]({{ site.aoj_contest_url }}ACPC2015Day3)

| 問題タイトル                                           | 解説                                                                 |
|--------------------------------------------------------|----------------------------------------------------------------------|
| [A: 磯野、あれやろうぜ！]({{ site.aoj_hupc_url }}2758) | [Archive (PDF)]({{ site.hcpc_archive_url }}acpc/2015/acpc2015_A.pdf) |
| [B: 中島、あれやろうぜ！]({{ site.aoj_hupc_url }}2759) | [Archive (PDF)]({{ site.hcpc_archive_url }}acpc/2015/acpc2015_B.pdf) |
| [C: 買い出し]({{ site.aoj_hupc_url }}2760)             | [Archive (PDF)]({{ site.hcpc_archive_url }}acpc/2015/acpc2015_C.pdf) |
| [D: みゃんぱすーれつ]({{ site.aoj_hupc_url }}2761)     | [Archive (PDF)]({{ site.hcpc_archive_url }}acpc/2015/acpc2015_D.pdf) |
| [E: 星の作り方]({{ site.aoj_hupc_url }}2762)           | [Archive (PDF)]({{ site.hcpc_archive_url }}acpc/2015/acpc2015_E.pdf) |
| [F: みこみー文字列]({{ site.aoj_hupc_url }}2763)       | [Archive (PDF)]({{ site.hcpc_archive_url }}acpc/2015/acpc2015_F.pdf) |
| [G: 旅費支給]({{ site.aoj_hupc_url }}2764)             | [Archive (PDF)]({{ site.hcpc_archive_url }}acpc/2015/acpc2015_G.pdf) |

{% enddetails %}

{% details 2014 %}

### 立命館大学競技プログラミング合宿 2014 Day3

- [合宿の案内 (こくちーず)]({{ site.reg_kokucheese_url }}144283)
- コンテスト日程: 2014 年 3 月 19 日 10:00 〜 13:00
- [問題セットへのリンク]({{ site.aoj_contest_url }}RitsCamp14Day3)

| 問題タイトル                                         | 解説                                                                 |
|------------------------------------------------------|----------------------------------------------------------------------|
| [A: D のやぼう]({{ site.aoj_hupc_url }}2575)         | [Archive (PDF)]({{ site.hcpc_archive_url }}rupc/2014/rupc2014_A.pdf) |
| [B: D 進どうですか？]({{ site.aoj_hupc_url }}2576)   | [Archive (PDF)]({{ site.hcpc_archive_url }}rupc/2014/rupc2014_B.pdf) |
| [C: ダウジングマシーン]({{ site.aoj_hupc_url }}2577) | [Archive (PDF)]({{ site.hcpc_archive_url }}rupc/2014/rupc2014_C.pdf) |
| [D: 弟子はつらいよ]({{ site.aoj_hupc_url }}2578)     | [Archive (PDF)]({{ site.hcpc_archive_url }}rupc/2014/rupc2014_D.pdf) |
| [E: 消えるドライヴ]({{ site.aoj_hupc_url }}2579)     | [Archive (PDF)]({{ site.hcpc_archive_url }}rupc/2014/rupc2014_E.pdf) |
| [F: 危険な輸送]({{ site.aoj_hupc_url }}2580)         | [Archive (PDF)]({{ site.hcpc_archive_url }}rupc/2014/rupc2014_F.pdf) |
| [G: 完全順列]({{ site.aoj_hupc_url }}2581)           | [Archive (PDF)]({{ site.hcpc_archive_url }}rupc/2014/rupc2014_G.pdf) |

{% enddetails %}
