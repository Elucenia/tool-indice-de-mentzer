<!-- ELUCENIA technical documentation · indice-de-mentzer · zh · no clinical/professional/rights approval -->

# Mentzer 指数

[条件、来源与许可](https://elucenia.org/zh/tools/indice-de-mentzer)

## 使用方法

在门户中使用工具，或通过本地 HTTP 服务器打开 index.html。选择语言，填写各字段，然后计算。

## 输入与单位

### 平均红细胞体积（MCV）

`vcm`

fL · 范围: 40–130

### 红细胞

`hem`

百万/µL · 范围: 1–9

## 方法版本

Mentzer 1973：MCV/红细胞，百万/µL；筛查规则，非诊断

## 已记录的公式

Mentzer指数=MCV（fL）÷红细胞（百万/µL）.

## 限制与适用人群

Mentzer指数是小细胞症的筛查规则，计算时MCV使用fL，红细胞计数使用百万/µL，而非每µL的原始计数。它不能确认缺铁或地中海贫血携带状态。Hoffmann2015的荟萃分析显示，各鉴别指数的敏感度和特异度并非100%，且总体上在成人中的表现优于儿童。提示性结果仍需确认性检查；不能假定所有人群的准确度相同。

## 参考文献

- [Mentzer WC Jr. Differentiation of iron deficiency from thalassaemia trait. Lancet, 1973.](https://doi.org/10.1016/S0140-6736(73)91446-3)

- [Hoffmann JJ et al. Discriminant indices for distinguishing thalassemia and iron deficiency in patients with microcytic anemia: a meta-analysis. Clin Chem Lab Med, 2015.](https://doi.org/10.1515/cclm-2015-0179)

## 复现技术测试

在此仓库的根目录中运行 node test.cjs，以重复已记录的合成案例。原始输入、预期结果和容差保持不变。技术测试不构成临床验证。

```sh
node test.cjs
```

tool.json 包含来源、版本和审查范围。examples.json 保留合成输入与预期结果；results.json 记录实际得到的结果。

[记录与参考文献](../tool.json) · [JavaScript代码](../calculator.js) · [参考案例](../examples.json) · [results.json](../results.json)

## 审查与使用条件

尚未开展独立临床审查。

此界面为自主编写的翻译，并非官方或认证版本。尚未完成独立临床审查、专业语言审查或工具权利授权。

公式或分类结果。解释、处理及适用性须结合专业评估和所选来源。

## 许可与署名

Apache-2.0 仅适用于 ELUCENIA 代码。工具、出版物、翻译和数据的权利仍归各自权利人所有。请保留 LICENSE 和 NOTICE。

ELUCENIA · Felipe Guedes · Copyright © 2026
