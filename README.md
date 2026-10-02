# 💄 Principia x Creamy x Sallve: interesse de busca por marcas nativas digitais de skincare

Análise exploratória de dados comparando o interesse de busca no Google por três marcas brasileiras de skincare — **Principia, Creamy e Sallve** — ao longo do tempo, considerando evolução temporal, sazonalidade, consultas relacionadas e distribuição regional.

## 🎯 Objetivo

Investigar como o interesse de busca por cada marca evoluiu ao longo do período analisado e identificar padrões de sazonalidade, comportamento de busca e diferenças regionais.

> **Importante:** os dados do Google Trends representam interesse relativo de busca, e não faturamento, vendas ou participação de mercado.

## 🔎 Perguntas da análise

1. **Como evoluiu o interesse médio nas buscas do Google por Creamy, Principia e Sallve ao longo do período analisado?**

2. **Existem picos de interesse recorrentes ao longo do ano e eles coincidem com períodos comerciais, como a Black Friday?**

3. **Quais consultas relacionadas aparecem para cada marca e o que elas indicam sobre a intenção de busca?**

4. **Quais regiões do Brasil apresentam maior interesse relativo por cada marca?**

## 📊 Principais insights

* **Principia** apresentou o maior nível de interesse relativo entre as três marcas na análise temporal e também liderou a comparação regional nos estados analisados.

* **Creamy** apresentou crescimento consistente ao longo de boa parte do período, seguido por uma estabilização nos anos mais recentes. Seu interesse relativo foi especialmente relevante nas regiões Sul e Sudeste.

* **Sallve** apresentou níveis de interesse inferiores aos das demais marcas na maior parte das comparações, mas apresentou padrões específicos nas consultas relacionadas e maior destaque relativo em alguns grandes centros urbanos.

* **Novembro apresentou níveis elevados de interesse para as três marcas**, indicando um possível padrão sazonal. A associação com a Black Friday é uma hipótese que pode ser investigada por meio do cruzamento com dados de campanhas ou períodos comerciais.

* As **consultas relacionadas** revelaram diferentes tipos de intenção de busca, incluindo pesquisas sobre produtos e ingredientes, avaliações/opiniões e comparações entre marcas.

## 🗂️ Dados

**Fonte:** Google Trends — Brasil

Dados coletados por exportação manual em CSV:

* **Interesse ao longo do tempo:** dados semanais de 01/01/2020 a 21/09/2026
* **Consultas relacionadas:** consultas frequentes e em alta para cada marca
* **Interesse por sub-região:** dados relativos para os estados brasileiros

## 🛠️ Ferramentas

* Python
* Pandas
* Matplotlib

## 🔬 Etapas da análise

1. Importação dos dados
2. Organização e tratamento das colunas
3. Conversão e padronização das datas
4. Análise do interesse ao longo do tempo
5. Análise de sazonalidade
6. Análise das consultas relacionadas
7. Comparação regional
8. Visualização dos resultados
9. Interpretação dos principais padrões encontrados

## ⚠️ Ressalvas metodológicas

* O período de **2026 é parcial**, com dados disponíveis até setembro. Comparações envolvendo esse ano devem, portanto, ser interpretadas com cautela.

* A janela de análise foi definida de **01/01/2020 a 21/09/2026**, permitindo comparar períodos equivalentes ao longo dos anos.

* Os dados do Google Trends são **relativos**, variando de acordo com o período, local e termos comparados. Eles não representam volume absoluto de pesquisas.

* Os dados de interesse por sub-região representam o **interesse relativo entre as três marcas dentro de cada estado**, e não o número absoluto de buscas.

* O Google Trends não permite, isoladamente, concluir sobre **faturamento, vendas, participação de mercado ou crescimento comercial** das marcas.

## 📌 Tipo de projeto

Projeto de estudo de análise exploratória de dados, desenvolvido para investigar comportamento de busca e gerar hipóteses a partir de dados públicos.

- O período de 2026 é parcial (até setembro), então comparações envolvendo esse ano devem ser lidas com cautela.
- A janela de coleta foi ajustada para começar em 01/01/2020 (em vez de "últimos 5 anos") para garantir que todos os meses tivessem a mesma quantidade de anos completos na comparação de sazonalidade.
- Os dados de interesse por sub-região são relativos entre as três marcas (somam 100% por estado), não representam volume absoluto de busca.
