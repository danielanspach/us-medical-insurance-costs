# U.S. Medical Insurance Costs

Análise exploratória de 1.338 registros de custos médicos nos Estados Unidos, usando fundamentos de Python para comparar valores por tabagismo, idade e região.

Projeto de portfólio desenvolvido durante meus estudos no **Codecademy**.

## Principais resultados

| Indicador | Valor (USD) |
| --- | ---: |
| Custo médio geral | 13.270,42 |
| Custo mediano geral | 9.382,03 |
| Custo médio de fumantes | 32.050,23 |
| Custo médio de não fumantes | 8.434,27 |

Nesta amostra, fumantes apresentam custos médios aproximadamente **3,8 vezes maiores**. As médias e medianas também aumentam entre as faixas etárias analisadas. As comparações descrevem associações e não demonstram causalidade.

## O que foi feito

- Verificação de campos vazios, registros repetidos e categorias.
- Conversão e organização dos dados em listas e dicionários.
- Criação de funções para calcular médias e comparar grupos.
- Comparação de médias e medianas por tabagismo, região e faixa etária.
- Discussão das limitações dos dados e de possibilidades de análise futura.

## Ferramentas

**Python 3 · Jupyter Notebook · `csv` · `statistics`**

A análise utiliza apenas bibliotecas da biblioteca padrão do Python.

## Como explorar

1. Abra o [notebook com a análise](us-medical-insurance-costs.ipynb) para consultar o código, os resultados salvos e as conclusões.
2. Para executar, baixe este repositório e mantenha `insurance.csv` e o notebook na mesma pasta.
3. Abra o notebook no JupyterLab ou Jupyter Notebook, selecione um ambiente Python 3 e execute as células em ordem.

## Dados e limitações

Fonte: [Medical Cost Personal Datasets — Kaggle](https://www.kaggle.com/datasets/mirichoi0218/insurance), utilizado no projeto U.S. Medical Insurance Costs do Codecademy.

A amostra contém pessoas de 18 a 64 anos e não deve ser considerada representativa de toda a população. Um registro repetido foi mantido porque não há identificador individual que permita confirmar uma duplicação indevida. O projeto não inclui modelo preditivo.

## Autor

Daniel Anspach — estudando Python e análise de dados, com interesse em automação de processos administrativos.
