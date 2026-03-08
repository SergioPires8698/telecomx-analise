# 📊 Telecom X — Análise de Evasão de Clientes (Churn)

Este projeto tem como objetivo analisar os dados de clientes da empresa **Telecom X** para identificar fatores relacionados à evasão de clientes (Churn).

A evasão de clientes representa um desafio importante para empresas de telecomunicações, pois impacta diretamente a receita e o crescimento do negócio.

---

# 🎯 Objetivo

Identificar padrões e fatores que influenciam o cancelamento de clientes utilizando técnicas de **Análise Exploratória de Dados (EDA)**.

---

# 📘 Dicionário de Dados

O dataset contém informações sobre clientes da Telecom X.

Principais variáveis analisadas:

* **customerID** → identificador do cliente
* **tenure** → tempo de permanência do cliente
* **Contract** → tipo de contrato
* **PaymentMethod** → método de pagamento
* **Charges.Monthly** → valor mensal pago
* **Charges.Total** → valor total pago
* **InternetService** → tipo de internet
* **Churn** → indica se o cliente cancelou o serviço

---

# 🔧 Tratamento de Dados

Durante a preparação dos dados foram realizadas as seguintes etapas:

* Verificação de valores ausentes
* Remoção de registros duplicados
* Conversão de variáveis numéricas
* Padronização de colunas
* Criação da variável **Contas_Diarias**

Essa etapa garante que os dados estejam consistentes para análise.

---

# 📊 Análise Exploratória de Dados

A análise exploratória foi realizada para identificar padrões relacionados ao churn.

Foram analisadas:

* Distribuição de churn
* Churn por tipo de contrato
* Churn por método de pagamento
* Churn por tempo de permanência
* Relação entre valor mensal e evasão
* Quantidade de serviços contratados

Também foi realizada uma análise de **correlação entre variáveis** para identificar fatores associados ao cancelamento de clientes.

---

# 🔎 Principais Insights

A análise revelou alguns padrões importantes:

* Clientes com **contratos mensais** apresentam maior taxa de cancelamento.
* Clientes com **menor tempo de permanência** possuem maior probabilidade de churn.
* Clientes com **menos serviços contratados** tendem a cancelar com maior frequência.

---

# 📄 Conclusão

Os resultados indicam que fatores como tipo de contrato, tempo de relacionamento e quantidade de serviços influenciam diretamente na evasão de clientes.

Com base nesses resultados, recomenda-se que a empresa invista em estratégias de **retenção de clientes**, como incentivos para contratos de longo prazo e melhorias na experiência inicial dos clientes.

---

# 🛠️ Tecnologias Utilizadas

* Python
* Pandas
* Matplotlib
* Seaborn
* Google Colab

---

