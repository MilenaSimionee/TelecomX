# TelecomX

📊 Análise de Churn - Telecom X

Este repositório contém a análise exploratória de dados (EDA) aplicada ao conjunto de dados da empresa fictícia **Telecom X**, com o objetivo de investigar os principais fatores relacionados à evasão de clientes (churn).

---

## 🔍 Objetivo

Analisar o comportamento dos clientes da Telecom X para entender os principais motivos de cancelamento de contrato, utilizando visualizações e métricas para apoiar recomendações estratégicas voltadas à retenção de clientes.

---

## 🧪 Etapas do Projeto

- **Extração dos Dados**  
  Leitura do arquivo `TelecomX_Data.json` via `pandas.read_json()`.

- **Transformação e Limpeza**  
  - Explosão de colunas aninhadas (`customer`, `phone`, `internet`, `account`)
  - Conversão de tipos (como `MonthlyCharges`, `TotalCharges`)
  - Tratamento de dados ausentes e remoção de inconsistências

- **Análise Exploratória de Dados (EDA)**  
  Geração de gráficos e estatísticas para entender padrões de churn.

---

## 📊 Principais Análises

- 📈 **Distribuição Geral de Churn**  
  26,5% dos clientes cancelaram o serviço.

- 👤 **Churn por Gênero**  
  Diferenças pequenas entre homens e mulheres.

- 📄 **Churn por Tipo de Contrato**  
  Contratos mensais têm churn muito maior (~42,7%).

- 💳 **Método de Pagamento**  
  Débito automático tem menor churn; cheque eletrônico tem maior.

- 💸 **Custo Mensal e Total**  
  Clientes com `MonthlyCharges` altos tendem a sair mais;  
  `TotalCharges` altos indicam fidelidade (clientes antigos).

- 📶 **Serviços de Internet**  
  Internet via fibra tem mais churn; ausência de internet indica baixa evasão.

- 📞 **Serviços Adicionais (Suporte, Backup, Proteção)**  
  Clientes com serviços ativados têm menor churn.

---

## 📌 Recomendações

- Incentivar **contratos de longo prazo**
- Promover **melhoria no suporte técnico** e **serviços adicionais**
- Reavaliar o **modelo de preços da fibra**
- Investir em **modelos preditivos** para identificar clientes com risco de churn

---

## 🛠️ Tecnologias Utilizadas

- 🐍 [Python](https://www.python.org/)
- 🐼 [Pandas](https://pandas.pydata.org/)
- 📊 [Matplotlib](https://matplotlib.org/)

