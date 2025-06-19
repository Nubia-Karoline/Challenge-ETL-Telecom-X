<h1 align="center"> Projeto Churn de Clientes – Telecom X </h1>

Este repositório contém soluções e análise para o desafio proposto pela Telecom X. A análise foi realizada sobre os dados de clientes da empresa com o objetivo de entender os principais fatores que contribuem para o cancelamento dos serviços.

# 📌 Objetivo

A Telecom X tem enfrentado um alto índice de cancelamento de clientes. Este projeto tem como objetivo analisar os dados fornecidos pela empresa, tratar as inconsistências e aplicar técnicas de Análise Exploratória de Dados (EDA) para extrair insights valiosos sobre o comportamento dos clientes que evadem.

# 🛠️ Tecnologias Utilizadas
Python 3.10+
Pandas
NumPy
Matplotlib & Seaborn
Jupyter Notebook

# 📂 Estrutura do Repositório
◻ Challenge_ETL_telecomX.ipynb              # Notebook com o pipeline de ETL e análise exploratória

◻ dataset/telecomx_data_gold.csv            # Pasta com os dados tratados 

◻ requirements.txt                          # Bibliotecas necessárias para rodar o projeto

◻ README.md                                 # Este arquivo

# 🔍 Etapas Realizadas
1. Importação e Tratamento dos Dados
Extração de dados de uma API em formato JSON.
Normalização das colunas e correção de tipos de dados.
Preenchimento e tratamento de valores nulos.
Criação de novas features, como Daily_Charges.
2. Análise Exploratória de Dados (EDA)
Análise da variável alvo Churn, que representa se o cliente evadiu ou não.
Geração de gráficos para entender o comportamento dos clientes por:
Tipo de contrato
Tempo de permanência (tenure)
Serviços contratados
Tipo de pagamento
Fatura diária
3. Análise de Correlação
Verificação da relação entre variáveis e a variável alvo.
Criação de mapa de calor e gráficos de dispersão.

# Análise de dados - Gráficos




# 📈 Principais Insights

Clientes com contratos mensais têm maior chance de evadir.
Menor tempo de permanência está fortemente relacionado ao churn.
A ausência de serviços como suporte técnico, backup e segurança online está associada ao cancelamento.
Clientes com faturas diárias mais altas também demonstram maior churn.
Cobrança eletrônica (Paperless Billing) também está relacionada a maior evasão.

# ✅ Conclusões e Recomendações

Incentivar contratos de longo prazo com benefícios adicionais.
Oferecer pacotes combinados de serviços essenciais com desconto.
Foco em retenção nos primeiros meses de uso, pois o churn ocorre majoritariamente no início do ciclo.
Criar campanhas de reengajamento para perfis com alto risco de churn.

# 💡 Próximos Passos

Aplicar modelos preditivos após balanceamento da variável Churn.
Explorar técnicas como SMOTE e validação cruzada.
Construir dashboards interativos para acompanhamento contínuo de churn.

# 🚀 Como Executar

Clone o repositório:
git clone https://github.com/Nubia-Karoline/Challenge-ETL-Telecom-X/blob/main/TelecomX_BR.ipynb

Crie um ambiente virtual:
python -m venv venv
source venv/bin/activate  # Linux/macOS
venv\Scripts\activate   # Windows

Instale as dependências:
pip install -r requirements.txt

Execute o notebook:
jupyter notebook

# 👤 Autora

Projeto desenvolvido por Núbia Karoline como parte do Challenge da Trilha de Especialização em Data Science do Programa ONE: Oracle Next Education em parceria com a Alura.

# 📄 Licença

Distribuído livremente sob a MIT License.
