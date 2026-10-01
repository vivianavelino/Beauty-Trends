# Principia x Creamy x Sallve: como marcas nativas digitais estão conquistando o mercado brasileiro de skincare?

Análise exploratória de dados comparando o interesse de busca no Google por três marcas brasileiras de skincare , **Principia**, **Creamy** e **Sallve** ao longo do tempo, por sazonalidade, por tipo de intenção de busca e por região do Brasil.

## Objetivo

Investigar se o crescimento dessas marcas no Google Trends reflete uma tendência sólida de mercado ou apenas picos pontuais de interesse, e entender como cada marca se posiciona em relação às concorrentes.

## Perguntas respondidas

1. **Como evoluiu o interesse médio nas buscas do Google por Creamy, Principia e Sallve ao longo do período analisado?**
2. **Existem picos de interesse recorrentes ao longo do ano (sazonalidade), e eles coincidem com datas comerciais como a Black Friday?**
3. **Quais consultas relacionadas aparecem para cada marca, e o que elas revelam sobre o tipo de busca (produto/ingrediente, opinião pré-compra ou comparação com concorrentes)?**
4. **Quais regiões possuem maior interesse por cada marca?**

## Principais achados

**Principia** lidera a participação de interesse em todos os estados, cresce de forma contínua ao longo de todo o período analisado e tem foco maior nas regiões Norte e Nordeste. Quase todas as suas consultas relacionadas aparecem como recentes ("Breakout"), reforçando a leitura de uma marca em fase de expansão acelerada.
**Creamy** cresceu de forma consistente até 2024 e depois estagnou, domina as regiões Sul e Sudeste, e é a única das três sem sinal de dúvida/review nas buscas relacionadas,o que sugere um público mais formado, que já decidiu pela marca.
**Sallve** é a menor em quase todas as métricas, mas tem um padrão próprio: a participação de interesse é mais concentrada em grandes centros urbanos (Rio de Janeiro, São Paulo e Distrito Federal). Novembro é o mês de maior interesse nas três marcas, provavelmente puxado pela Black Friday.

## Fonte de dados

Google Trends (Brasil), coletado via exportação manual de CSV:
- Interesse ao longo do tempo (semanal, 01/01/2020 a 21/09/2026)
- Consultas relacionadas (frequentes e em alta) por marca, usando "Termo de pesquisa"
- Interesse por sub-região (estados do Brasil)

## Ferramentas

- Python
- Pandas
- Matplotlib

## Ressalvas metodológicas

- O período de 2026 é parcial (até setembro), então comparações envolvendo esse ano devem ser lidas com cautela.
- A janela de coleta foi ajustada para começar em 01/01/2020 (em vez de "últimos 5 anos") para garantir que todos os meses tivessem a mesma quantidade de anos completos na comparação de sazonalidade.
- Os dados de interesse por sub-região são relativos entre as três marcas (somam 100% por estado), não representam volume absoluto de busca.
