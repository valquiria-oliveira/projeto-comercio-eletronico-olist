# 📊 Projeto Power BI – Análise de E-Commerce Brasileiro (Olist)

> **Desenvolvido por:** Valquiria Oliveira
> **Duração:** 5 dias | **Nível:** Iniciante  
> **Ferramentas:** Power BI, Excel (Power Query), GitHub

---

## 🎯 Objetivos

1. **Entender padrões de compra** das famílias brasileiras no e-commerce Olist  
2. **Analisar avaliações** de pedidos e tempo médio de entrega  
3. **Descobrir insights logísticos** (atrasos, regiões críticas)  
4. **Visualizar tendências** por categoria, estado e forma de pagamento

---

## 📁 Estrutura do projeto

- **dados/**: arquivos CSV originais  
- **dashboards/**: arquivos .pbix do Power BI  
- **notebook/**: notebooks de exploração e documentação passo a passo
- **imagens/**: screenshots e previews


---

## 🔗 Fonte dos Dados

- **Dataset:** Brazilian E-Commerce Public Dataset by Olist  
- **Origem:** Kaggle – https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

---

## 📝 Plano de Trabalho (5 Dias)

| Dia | Atividade                                                                 |
|-----|---------------------------------------------------------------------------|
| 1   | Importar CSVs no Power BI / Conexão via Power Query                       |
| 2   | Limpeza e transformação de dados (remover nulos, tipos, colunas extras)   |
| 3   | Modelagem: criar dimensões (clientes, produtos) e fatos (vendas, entregas)|
| 4   | Montar visualizações: tabelas, gráficos de barras, mapas e KPI’s           |
| 5   | Refino estético, storytelling, exportar imagens e documentar insights      |

---

## 🔧 Fluxo de Trabalho

1. **Power Query**  
   - Conectar aos CSVs  
   - Filtrar colunas irrelevantes  
   - Tratar erros, converter tipos e criar colunas calculadas

2. **Modelagem de Dados**  
   - Definir relacionamento entre tabelas  
   - Criar tabelas de dimensão (ex: `DimCliente`, `DimProduto`)  
   - Criar tabela fato (`FatoVendas`)

3. **Construção do Dashboard**  
   - Página de Visão Geral (KPIs)  
   - Análise por Categoria e Região  
   - Mapa de Entregas x Tempo  
   - Gráfico de Avaliações x Valor do Pedido

4. **Documentação e Apresentação**  
   - Capturar screenshots em `/imagens/`  
   - Escrever principais insights no `plano-projeto.md`

---

## 💡 Insights Esperados

- Quais 5 categorias mais geraram receita?  
- Estados com maior atraso médio nas entregas  
- Correlação entre valor do frete e avaliação do cliente  
- Padrões de repetição de compra por cliente  

---

## 🚀 Próximos Passos

- Publicar o relatório no Power BI Service  
- Agendar atualização diária via gateway  
- Evoluir com análises preditivas (ML)

---

> ⚠️ *Este repositório está em constante evolução. Feedbacks e sugestões são bem-vindos!*  


