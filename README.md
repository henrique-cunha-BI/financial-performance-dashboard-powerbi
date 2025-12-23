# Financial Performance Dashboard - Power BI

## Overview
Dashboard criada para análise de receitas de uma empresa onde a mesma pode ser utilizada por gestores financeiros e diretores, ajudando os mesmos a tomar decisões conforme a performance de produtos e segmentos lucrativos.

## Objetivo do Projeto
- Monitorar performance financeira
- Análisar lucro ao longo do tempo
- Comparação de produtos, segmentos e países
- Avaliar crescimento (MoM, YoY, YTD)

## DATASET
Dataset proveniente da Microsoft (Microsoft Financial Sample), com aproximadamente 700 registros, possuindo métricas como vendas, lucro, segmento, países e datas.
Dados totalmente fictícios.

## Modelagem de Dados
Utilizado o modelo estrela devido a performance e clareza do modelo, dividindo o dataset inicial em tabelas fato ('F_Financials') e dimensão('D_Country', 'D_Dband', 'D_Product', 'D_Segment') além de criação de utilização de uma tabela calendário ('D_Calendar') para análises temporais.

## Métricas DAX Utilizadas
- Receita
- Receita YTD
- Lucro Bruto
- Lucro Líquido
- Lucro Líquido YTD
- Margens (%)
- Crescimento MoM
- Crescimento YoY

## Principais Análises Disponíveis
- Evolução mensal de Receita e Lucro
- Comparação por Produto
- Comparação por País
- Comparação por Segmento

## Visualizações Utilizadas
Utilizado cards para KPIs importantes devido a importância da métrica, gráficos de linha para análises temporais devido a facilidade de análise de tendências com apoio de tooltips customizados para maior detalhe nas análises e gráficos de barra para melhor comparação entre categorias.

## Ferramentas Utilizadas
- Power BI Desktop
- DAX
- Power Query
- GitHub
- Excel

## Como Utilizar o Projeto
Baixe o arquivo .pbix e abra-o utilizando Power BI desktop, o usuário pode interagir com os visuias e clicar em métricas desejadas nos gráficos de barra ou passar o mouse por cima dos gráficos para análise detalhadas com tooltips.

## Aprendizados
- Aplicação prática de modelagem dimensional (modelo estrela), separando corretamente tabelas fato e dimensões para garantir performance, clareza e escalabilidade do modelo.
- Criação e utilização de uma tabela calendário dedicada, permitindo análises temporais consistentes e corretas, como YTD, MoM e YoY.
- Desenvolvimento de medidas DAX financeiras, incluindo Receita, Lucro Bruto, Lucro Líquido e Margens, priorizando medidas calculadas em vez de colunas prontas do dataset.
- Implementação de análises de crescimento temporal, utilizando funções de inteligência de tempo para avaliar performance ao longo dos meses e anos.
- Uso de tooltips customizados para aprofundar análises sem poluir a visualização principal do dashboard, melhorando a experiência do usuário.
- Organização do layout seguindo boas práticas de data visualization, com foco em KPIs no topo, hierarquia visual clara e escolha adequada de gráficos para cada tipo de análise.
- Desenvolvimento de storytelling orientado ao negócio, transformando dados financeiros em insights acionáveis para gestores e tomadores de decisão.
- Consolidação de boas práticas no uso do Power Query para tratamento e padronização dos dados antes da modelagem.