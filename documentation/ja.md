<!-- ELUCENIA technical documentation · indice-de-mentzer · ja · no clinical/professional/rights approval -->

# Mentzer指数

[条件・出典・許諾](https://elucenia.org/ja/tools/indice-de-mentzer)

## 使い方

ポータルでツールを使用するか、ローカルHTTPサーバー経由でindex.htmlを開いてください。言語を選択し、項目を入力して計算してください。

## 入力項目と単位

### 平均赤血球容積（MCV）

`vcm`

fL · 範囲: 40–130

### 赤血球

`hem`

百万/µL · 範囲: 1–9

## 方法の版

Mentzer 1973：MCV/赤血球、百万/µL；スクリーニング、診断ではない

## 記載された計算式

Mentzer指数=MCV（fL）÷赤血球（百万/µL）.

## 限界・対象集団

Mentzer指数は小球性赤血球に対するスクリーニング規則で、MCVをfL、赤血球数を百万/µLで計算します。µL当たりの未換算の個数は使いません。鉄欠乏やサラセミア保因を確定するものではありません。Hoffmann2015のメタ解析では、鑑別指数の感度・特異度は100%ではなく、全体として小児より成人で良い性能を示しました。示唆的な結果には確認検査が必要で、すべての集団で同じ精度を前提にしません。

## 参考文献

- [Mentzer WC Jr. Differentiation of iron deficiency from thalassaemia trait. Lancet, 1973.](https://doi.org/10.1016/S0140-6736(73)91446-3)

- [Hoffmann JJ et al. Discriminant indices for distinguishing thalassemia and iron deficiency in patients with microcytic anemia: a meta-analysis. Clin Chem Lab Med, 2015.](https://doi.org/10.1515/cclm-2015-0179)

## 技術テストの再現

このリポジトリのルートディレクトリでnode test.cjsを実行すると、記録された合成ケースを再実行できます。元の入力、期待結果、許容誤差は保持されています。技術テストは臨床的検証を意味しません。

```sh
node test.cjs
```

tool.jsonには出典、版、確認範囲が記録されています。examples.jsonには合成入力と期待結果が保持され、results.jsonには実際に得られた結果が記録されています。

[記録・参考文献](../tool.json) · [JavaScriptコード](../calculator.js) · [参照ケース](../examples.json) · [results.json](../results.json)

## 確認状況と使用条件

独立した臨床レビューは実施されていません。

このインターフェースは独自に作成した翻訳であり、公式版や認証済みの版ではありません。独立した臨床レビュー、専門家による言語レビュー、評価尺度等の権利許諾の確認は実施されていません。

式または分類の結果です。解釈、対応、適用可能性は専門家による評価と選択した出典に依存します。

## ライセンスと帰属表示

Apache-2.0はELUCENIAのコードにのみ適用されます。評価尺度等、出版物、翻訳、データの権利は、それぞれの権利者に帰属します。LICENSEとNOTICEを保持してください。

ELUCENIA · Felipe Guedes · Copyright © 2026
