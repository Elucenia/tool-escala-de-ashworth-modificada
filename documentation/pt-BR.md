<!-- ELUCENIA technical documentation · escala-de-ashworth-modificada · pt-BR · no clinical/professional/rights approval -->

# Escala de Ashworth modificada

[condições, fontes e permissões](https://elucenia.org/pt-br/ferramentas/escala-de-ashworth-modificada)

## Como usar

Use a ferramenta no portal ou abra index.html em um servidor HTTP local. Selecione o idioma, preencha os campos e calcule.

## Entradas e unidades

### Resistência ao movimento passivo (em cerca de 1 segundo)

`grau`

- `0` — 0 – Sem aumento do tônus muscular
- `1` — 1 – Aumento leve: “trava e solta” ou resistência mínima no fim do arco de movimento
- `2` — 2 – Aumento mais marcado na maior parte do arco, mas o segmento move-se com facilidade
- `3` — 3 – Aumento considerável: movimento passivo difícil
- `4` — 4 – Segmento rígido em flexão ou extensão
- `1p` — 1+ – Aumento leve: “trava” seguida de resistência mínima em menos da metade do arco

## Edição do método

Modified Ashworth/Bohannon Smith 1987:0/1/1+/2/3/4; grau 1+ específico

## Fórmula documentada

Com o paciente relaxado em decúbito dorsal, mova passivamente o segmento em todo o arco de movimento em cerca de 1 segundo e escolha o grau que descreve a resistência. O grau 1+ foi acrescentado por Bohannon e Smith à escala original de Ashworth.

## Limites e população

Graduação clínica da resistência ao movimento passivo, distinta da força muscular. O estudo original de confiabilidade examinou flexores do cotovelo em pacientes com lesão intracraniana. Não se pode transportar automaticamente esse desempenho para toda articulação ou condição neurológica.

## Referências

- [Bohannon RW, Smith MB. Interrater reliability of a modified Ashworth scale of muscle spasticity. Phys Ther, 1987.](https://doi.org/10.1093/ptj/67.2.206)

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
