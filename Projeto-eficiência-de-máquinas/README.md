# 🔧 Análise de Eficiência Energética de Máquinas Industriais

## 🎯 Objetivo
Este projeto com finalidade de treinamento visa analisar a eficiência energética de 50 máquinas industriais reais de diferentes tipos, utilizando Python e Power BI. A análise busca identificar oportunidades de otimização no consumo de energia e na produtividade, contribuindo para uma operação mais sustentável e econômica. 

## 🛠️ Ferramentas Utilizadas
- **Python (Pandas)**: Geração e pré-processamento do dataset
- **Power BI**: Análise visual, segmentação de dados e insights
- **Power Query**: Criação de colunas derivadas e formatação de dados
- **ChatGPT** : Auxílio na formatação das documentações e nas formulações de ideias.

## 📊 Dataset
Cada máquina possui os seguintes dados:
- Tipo e nome da máquina (ex: Compressor 1)
- Tempo de operação (em horas)
- Consumo de energia (em kWh)
- Produção (em peças)
- Eficiência = Produção / Consumo, com 4 casas decimais

Os dados foram gerados com simulações realistas usando tipos comuns em ambientes industriais.

## 🔍 Principais Insights

1. **🏆 Destaques de Eficiência**
   - *Moinho de Martelos 49* foi a mais eficiente, com **5,128 peças/kWh**
   - Outros destaques:
     - *Motor Elétrico 26* – **5,0968 peças/kWh**
     - *Moinho Vertical 28* – **4,8649 peças/kWh**
     - *Bomba Centrífuga 45* – **4,4258 peças/kWh**

2. **⚠️ Baixa Eficiência**
   - *Compressor de Parafuso 9* – **1,9526 peças/kWh**
   - *Exaustor 44* – **2,0000 peças/kWh**
   - Máquinas candidatas à manutenção ou substituição.

3. **⚙️ Desempenho por Tipo**
   - *Moinhos Verticais* apresentaram desempenho consistente, aparecendo frequentemente entre os mais eficientes.

4. **⏱️ Tempo vs Eficiência**
   - Tempo de operação alto não garante eficiência. Ex: *Motor Elétrico 26* teve alta eficiência mesmo com operação média (137h).

5. **💡 Oportunidades**
   - Máquinas com eficiência < 2,5 devem ser analisadas.
   - Padronizar operação com base nas mais eficientes pode gerar **redução de custos** e **aumento de produtividade**.

## 📌 Conclusão
A análise mostrou como dados industriais podem ser aplicados de forma prática à engenharia para decisões mais inteligentes e sustentáveis. A análise apesar de simples mostram que tipo de embasamento é possível ter na tomada de decisão para o encaminhamento para a manutenção e revisão do maquinário.

## 🔗 Arquivos do Projeto
- `Gerador de dataset de máquinas.ipynb`: Script de geração dos dados
- `dados_50_maquinas.csv`: Dataset
- `Eficiência de máquinas dashboard.pbix`: Dashboard Power BI
