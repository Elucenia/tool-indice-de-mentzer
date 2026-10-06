<!-- ELUCENIA technical documentation · indice-de-mentzer · pt-BR · no clinical/professional/rights approval -->

# Índice de Mentzer

[condições, fontes e permissões](https://elucenia.org/pt-br/ferramentas/indice-de-mentzer)

## Como usar

Use a ferramenta no portal ou abra index.html em um servidor HTTP local. Selecione o idioma, preencha os campos e calcule.

## Entradas e unidades

### VCM

`vcm`

fL · intervalo: 40–130

### Hemácias

`hem`

milhões/µL · intervalo: 1–9

## Edição do método

Mentzer 1973:VCM/hemácias, milhões/µL; regra de triagemnão diagnóstico

## Fórmula documentada

Índice de Mentzer = VCM (fL) ÷ hemácias (milhões/µL).

## Limites e população

O índice de Mentzer é uma regra de triagem em microcitose, calculada com VCM em fL e hemácias em milhões/µL, não com a contagem bruta por µL. Não confirma deficiência de ferro nem traço talassêmico. A meta-análise de Hoffmann 2015 mostrou que os índices discriminantes não têm sensibilidade e especificidade de 100% e, em conjunto, tiveram desempenho melhor em adultos que em crianças. Resultados sugestivos exigem investigação confirmatória; não se presume a mesma acurácia em todas as populações.

## Referências

- [Mentzer WC Jr. Differentiation of iron deficiency from thalassaemia trait. Lancet, 1973.](https://doi.org/10.1016/S0140-6736(73)91446-3)

- [Hoffmann JJ et al. Discriminant indices for distinguishing thalassemia and iron deficiency in patients with microcytic anemia: a meta-analysis. Clin Chem Lab Med, 2015.](https://doi.org/10.1515/cclm-2015-0179)

## Reproduzir os testes técnicos

Execute node test.cjs na pasta raiz deste repositório para repetir os casos sintéticos registrados. As entradas, expectativas e tolerâncias originais são preservadas. Testes técnicos não constituem validação clínica.

```sh
node test.cjs
```

tool.json contém fontes, edição e escopo de revisão. examples.json conserva as entradas e expectativas sintéticas; results.json registra os resultados obtidos.

[Ficha e referências](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referência](../examples.json) · [results.json](../results.json)

## Revisão e condições de uso

Revisão clínica independente não realizada.

Esta interface é uma tradução autoral, não uma edição oficial ou certificada. Revisão clínica independente, revisão linguística profissional e autorização de direitos de instrumentos não foram realizadas.

Resultado da fórmula ou classificação. Interpretação, conduta e aplicabilidade dependem da avaliação profissional e da fonte selecionada.

## Licença e atribuição

Apache-2.0 aplica-se somente ao código da ELUCENIA. Os instrumentos, publicações, traduções e dados mantêm os direitos dos respectivos titulares. Preserve LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Resultados documentados

As informações abaixo preservam as saídas do método para exemplos sintéticos. Não constituem validação clínica independente.

### 1

Índice < 13: sugere traço de talassemia (β ou α)

O índice orienta, mas não diagnostica: confirme com ferritina e eletroforese de hemoglobina (HbA2).


### 2

Índice > 13: sugere anemia ferropriva

O índice orienta, mas não diagnostica: confirme com ferritina e eletroforese de hemoglobina (HbA2).


### 3

Índice = 13: indeterminado

O índice orienta, mas não diagnostica: confirme com ferritina e eletroforese de hemoglobina (HbA2).

