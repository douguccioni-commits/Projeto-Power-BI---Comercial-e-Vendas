# Dashboard Estratégico de Vendas | Megatop

## Sobre o projeto

Desenvolvimento de uma solução de Business Intelligence voltada à análise de desempenho comercial da empresa fictícia **Megatop**, utilizando Microsoft Power BI.

O projeto tem como objetivo consolidar informações de vendas em um ambiente analítico interativo, permitindo acompanhar indicadores de faturamento, cumprimento de metas, desempenho de produtos, produtividade de vendedores e distribuição geográfica das vendas.

A solução foi estruturada para oferecer diferentes perspectivas do negócio, transformando dados operacionais em informações estratégicas que apoiam a análise de resultados, o monitoramento de desempenho e o processo de tomada de decisão.

O desenvolvimento contempla desde a preparação e transformação dos dados até a modelagem dimensional, criação de indicadores analíticos e construção de uma interface visual intuitiva.

## Visualização do Dashboard

**Acesse o relatório interativo publicado no Power BI Service:**

[**ACESSAR DASHBOARD ONLINE | MEGATOP**](https://app.powerbi.com/view?r=eyJrIjoiMTIwYjk5MjQtY2JkYy00Mzk0LWI5ZmQtMWQ1NzMxZTg2YzdmIiwidCI6IjY1OWNlMmI4LTA3MTQtNDE5OC04YzM4LWRjOWI2MGFhYmI1NyJ9)

O relatório pode ser acessado diretamente pelo navegador, permitindo a navegação entre páginas, aplicação de filtros e exploração dos indicadores sem necessidade de instalar o Power BI Desktop.

## Estrutura analítica do dashboard

O relatório está organizado em três perspectivas principais:

### 1. Visão Consolidada

Apresenta uma visão geral do desempenho comercial, reunindo os principais indicadores e resultados da operação.

- Faturamento total e acompanhamento de metas.
- Total de dias úteis e máximo de unidades vendidas.
- Evolução temporal do faturamento e análise por média móvel.
- Distribuição do faturamento por estado.
- Comparativo entre faturamento anual e metas estabelecidas.
- Análise de faturamento por produto e localização geográfica.

### 2. Análise de Produtos

Permite avaliar o desempenho comercial sob a perspectiva do portfólio de produtos.

- Faturamento por categoria e produto.
- Comparativo entre resultados realizados e metas.
- Análise de variação do faturamento por ano e produto.
- Utilização de gráficos de cascata (Waterfall Chart).
- Projeções de vendas por produto.

### 3. Análise de Vendedores

Apresenta indicadores de produtividade e desempenho individual da equipe comercial.

- Ranking de desempenho por vendedor.
- Faturamento individual e cumprimento de metas.
- Evolução dos resultados ao longo do tempo.
- Comparativo entre vendedores.
- Distribuição geográfica das vendas por estado.

## Tecnologias e ferramentas

| Tecnologia | Aplicação |
|---|---|
| Microsoft Power BI | Desenvolvimento do dashboard e visualização analítica |
| DAX | Criação de medidas, indicadores, rankings, metas e cálculos de inteligência temporal |
| Power Query (M) | Extração, limpeza, tratamento e transformação dos dados |
| Modelagem Dimensional | Estruturação dos dados seguindo o conceito de Star Schema |
| Power BI Service | Publicação e disponibilização do relatório interativo |
| UI/UX Design | Construção da interface, navegação e identidade visual |

## Modelagem de dados

O modelo de dados foi estruturado seguindo a abordagem **Star Schema (Esquema Estrela)**, buscando organizar as informações e estabelecer relacionamentos adequados para análises multidimensionais.

**Tabela fato:**
- `fatos_Vendas` — concentra os registros transacionais de vendas.

**Tabelas dimensão:**
- `Calendario` — estrutura temporal para análises e cálculos de inteligência de tempo.
- `Produto` — informações e classificações dos produtos.
- `Vendedor` — dados relacionados à equipe comercial.
- `Estado` — informações geográficas para análise regional.

**Organização das medidas:**

Foi criada uma tabela centralizada para organização das medidas DAX, facilitando a manutenção, identificação e gestão
