# project_7_TripleTen
Data analysis project for Zuber to understand passenger habits in Chicago. Used SQL for data extraction (ETL) and Python to test the impact of weather conditions on ride duration.

---

# Análise de Dados: Comportamento do Usuário e Fatores Externos (Zuber) 👋

## 📋 Descrição do Projeto
Este projeto foi desenvolvido para a **Zuber**, uma nova empresa de compartilhamento de caronas em Chicago. O foco principal foi analisar as preferências dos passageiros e o impacto de fatores externos, como o clima, na duração das viagens, fornecendo inteligência de dados para o lançamento do serviço.

## 🎯 Objetivos Estratégicos
* Identificar as empresas de táxi líderes em volume de corridas.
* Mapear os destinos mais frequentes em Chicago (Top 10 bairros).
* **Testar Hipótese Estatística:** "A duração média das viagens do Loop para o Aeroporto Internacional O'Hare muda nos sábados chuvosos".

## 🛠️ Tecnologias e Ferramentas
* **SQL:** Essencial no processo de **ETL**, utilizado para extrair dados de corridas, meteorologia e bairros diretamente do banco de dados da empresa.
* **Linguagem:** Python.
* **Bibliotecas:** Pandas, Matplotlib, Seaborn e Scipy (para testes de hipóteses).
* **Técnicas:** Extração via SQL, Análise Exploratória de Dados (EDA) e Teste t de Student.

## 📉 Metodologia e Insights
1.  **Extração de Dados (SQL):** Realizei consultas complexas com joins para unir informações de clima e duração de viagens em datas específicas.
2.  **Análise de Mercado:** Identificação das frotas mais competitivas e das rotas com maior demanda.
3.  **Teste de Hipóteses:** Aplicação de rigor estatístico para validar se a variação no tempo de viagem em dias de chuva era significativa ou apenas ruído nos dados.

## ✅ Resultados
* Identificação clara dos bairros com maior volume de desembarques, permitindo otimizar a distribuição da frota.
* Validação de que fatores climáticos alteram significativamente a logística das viagens para o aeroporto, subsidiando estratégias de precificação e planejamento operacional.
* Comprovação da viabilidade do uso de dados externos para prever padrões de comportamento dos usuários.

---

### 💡 Como utilizar este repositório
1. O notebook documenta desde a lógica das queries SQL utilizadas até a conclusão do teste estatístico.
2. As visualizações ajudam a entender a distribuição do mercado de transporte em Chicago.
