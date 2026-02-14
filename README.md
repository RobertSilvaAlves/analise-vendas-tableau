# Análise de Vendas e Lucratividade com Tableau

## Sobre o Projeto

Este projeto apresenta uma análise de vendas desenvolvida integralmente no Tableau a partir de um dataset consolidado (`data_frame_principal`).

O objetivo foi transformar dados brutos em informações estratégicas por meio da construção de um dashboard executivo, permitindo avaliar desempenho de vendas, lucratividade, comportamento ao longo do tempo e concentração de resultados por categoria, região e produto.

Toda a modelagem, agregações e cálculos foram realizados diretamente no Tableau, utilizando uma única fonte de dados.

---

## Estrutura do Repositório

analise-vendas-tableau/

├── data/  
│   └── data_frame_principal.xls  

├── dashboard/  
│   ├── Analise_de_Vendas_e_Lucratividade.twb  
│   └── preview_dashboard.png  

├── images/  
│   ├── dashboard_overview.png  
│   ├── evolucao_vendas.png  
│   ├── lucro_categoria.png  
│   ├── vendas_regiao.png  
│   └── top_produtos.png  

└── README.md  

---

## Visão Geral do Dashboard

![Visão Geral do Dashboard](images/dashboard_overview.png)

O dashboard foi estruturado com KPIs principais no topo, seguidos por análises temporais, comparações por categoria e região, ranking de produtos e previsão de vendas.

A organização foi pensada para permitir leitura rápida e interpretação executiva dos dados.

---

## Evolução das Vendas

![Evolução das Vendas](images/evolucao_vendas.png)

A análise temporal permite identificar tendências de crescimento, oscilações ao longo do período e possíveis padrões sazonais.

Foi aplicado forecast automático do Tableau sobre as vendas mensais para estimar comportamento futuro com base no histórico disponível.

---

## Lucro por Categoria

![Lucro por Categoria](images/lucro_categoria.png)

Essa visualização destaca quais categorias apresentam maior contribuição para o lucro total e evidencia diferenças relevantes de desempenho.

---

## Vendas por Região

![Vendas por Região](images/vendas_regiao.png)

A comparação regional permite identificar mercados com maior volume de vendas e possíveis oportunidades estratégicas.

---

## Top Produtos por Lucro

![Top Produtos por Lucro](images/top_produtos.png)

O ranking evidencia que uma parcela significativa do lucro está concentrada em um grupo reduzido de produtos, reforçando a importância de análise de portfólio.

---

## Principais Insights

- As vendas apresentaram trajetória de crescimento ao longo do período analisado.
- O lucro não cresce de forma perfeitamente proporcional às vendas, indicando variações de margem.
- A categoria Technology demonstrou maior impacto no resultado financeiro.
- Algumas regiões concentram maior volume de vendas.
- A previsão automática sugere continuidade da tendência observada no curto prazo.

---

## Ferramentas Utilizadas

- Tableau Desktop  
- Tableau Story  
- GitHub  

---

## Como Visualizar o Projeto

1. Baixe o arquivo `.twb` disponível na pasta `dashboard/`.
2. Abra no Tableau Desktop.
3. Navegue pelas Sheets, Dashboard e Story para visualizar a análise completa.

---

## Aprendizados

Durante o desenvolvimento deste projeto, foi possível aprofundar conhecimentos em:

- Modelagem de métricas dentro do Tableau  
- Construção de KPIs executivos  
- Aplicação de forecast automático  
- Organização de dashboards com foco em narrativa  
- Estruturação de projeto para portfólio  

---

## Autor

Seu Nome  
LinkedIn: seu link  
GitHub: seu link
