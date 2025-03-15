# 🚀 Portfólio de Análise de Dados  
**Olá! Sou João Pedro Chagas, um estudante aspirante a analista de dados com expertise em Excel, Power BI e SQL.**  

## 📌 Habilidades Técnicas  
- **Excel**: Dashboards, tabelas dinâmicas, funções avançadas (VLOOKUP, INDEX/MATCH).  
- **Power BI**: Modelagem de dados, DAX, visualizações interativas.  
- **SQL**: Consultas complexas, otimização de queries, joins.  

## 🛠 Projetos Destacados  
### **1. Dashboard de Vendas (Excel)**  
- **Objetivo**: Analisar tendências de vendas por região.  
- **Ferramentas**: Tabelas dinâmicas, gráficos interativos.  
- **Resultado**: Identificação de crescimento de 20% na região Sul.  
- [Ver Projeto](Excel/Imagens/dashboard_vendas.png)  

### **2. Análise de Rotatividade de Funcionários (Power BI)**  
- **Objetivo**: Reduzir custos com turnover.  
- **Ferramentas**: Medidas DAX, mapas interativos.  
- **Resultado**: Sugestão de foco em treinamento para o setor X.  
- [Ver Dashboard](https://app.powerbi.com/links/...)  

### **3. Otimização de Estoque (SQL)**  
- **Objetivo**: Identificar produtos com excesso de estoque.  
- **Query**:  
  ```sql
  SELECT produto_id, SUM(estoque) - SUM(vendas) AS excesso  
  FROM estoque  
  JOIN vendas ON estoque.produto_id = vendas.produto_id  
  GROUP BY produto_id  
  HAVING excesso > 100;  
