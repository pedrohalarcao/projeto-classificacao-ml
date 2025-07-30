# 🔄 Projeto: Predição de Churn (Evasão) de Clientes com Machine Learning

Este projeto foi desenvolvido como parte dos estudos em **Machine Learning aplicado à retenção de clientes**, com foco em construir um pipeline de classificação capaz de prever a **probabilidade de churn (evasão)** de clientes.

---

## 🎯 Objetivo

Desenvolver um modelo preditivo capaz de identificar clientes com maior probabilidade de **abandono da empresa (churn)**, auxiliando na tomada de decisão estratégica e ações de retenção.

---

## 🛠️ Tecnologias e Bibliotecas Utilizadas

- **Python 3.x**
- **Google Colab**
- **Pandas** – manipulação e análise de dados
- **Plotly** – visualização interativa (histograma, boxplot)
- **Scikit-learn (sklearn)** – construção, validação e salvamento dos modelos
- **Pickle** – persistência e reutilização do modelo treinado

---

## 📁 Dataset Utilizado

- Dados fictícios relacionados a **clientes de uma empresa de serviços**
- Variáveis incluem: score de crédito, sexo biológico, serviços adquiridos, salário estimado, saldo da conta, etc.
- **Target**: variável `churn` (sim/não)

---

## ⚙️ Pipeline do Projeto

1. **Leitura e inspeção dos dados**
   - Conversão de variáveis categóricas
   - Análise exploratória com boxplots, histogramas e métricas estatísticas

2. **Modelagem Preditiva**
   - Criação de um **modelo base** (Baseline)
   - Treinamento com dois algoritmos de classificação:
     - 🌳 **Árvore de Decisão**
     - 👥 **K-Nearest Neighbors (KNN)**

3. **Avaliação dos Modelos**
   - Métricas utilizadas:
     - Acurácia
     - Precisão
     - Recall
     - F1-Score
   - Comparação de desempenho entre os modelos

4. **Salvamento do Modelo com Pickle**
   - Exportação do modelo final (Árvore de Decisão)
   - Reaproveitamento em um novo conjunto de dados para validação

---

## ✅ Resultados

- O modelo **Árvore de Decisão** demonstrou o melhor desempenho nas métricas de classificação, tornando-se a escolha final para deployment.
- A análise inicial permitiu identificar **padrões críticos** de comportamento de clientes com alta taxa de evasão.
- O modelo final é capaz de prever com boa precisão a chance de churn, possibilitando ações proativas por parte da empresa.

---

## 📊 Visualizações Geradas

- **Boxplots** de variáveis contínuas para entender a distribuição por classe
- **Histogramas** interativos com Plotly
- **Matriz de Confusão** para validação dos modelos



---

## 🚀 Como Executar

1. Clone o repositório:
   ```bash
   git clone git@github.com:pedrohalarcao/projeto-classificacao-ml.git
   cd projeto-classificacao-ml


---

## 👤 Autor

Pedro Alarcão

Entusiasta em Ciência de Dados e Inteligência Artificial, com foco em aplicações práticas para tomada de decisão estratégica.


---

## 📌 Observações

O projeto é didático e faz parte do processo de aprendizado em projetos reais de Machine Learning supervisionado.
Os dados utilizados são simulados, sem qualquer relação com empresas reais.


---

## 📝 Licença

Este projeto está licenciado sob os termos da licença MIT. Consulte o arquivo LICENSE para mais informações.
