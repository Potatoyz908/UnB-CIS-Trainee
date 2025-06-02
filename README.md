Aqui está a atualização do seu **README** para incluir a parte sobre **Redes Neurais** baseada no que fizemos na atividade:

---

# Student Clustering with K-Means & Neural Networks

Este repositório apresenta dois estudos de caso completos: **agrupamento de estudantes** com o algoritmo **K-Means** e **classificação utilizando redes neurais** para prever categorias de objetos astronômicos (galáxias, estrelas e quasares).

## 📌 Objetivo

* **K-Means Clustering**: Aplicar técnicas de aprendizado não supervisionado para identificar padrões ocultos em um conjunto de dados multidimensional sobre hábitos de estudantes e seu desempenho acadêmico.
* **Redes Neurais**: Aplicar redes neurais para resolver problemas de classificação, com foco em dados astronômicos, como a classificação de galáxias, estrelas e quasares, utilizando técnicas de aprendizado supervisionado.

## 📊 Datasets

### 1. **Student Habits vs Academic Performance**

O dataset utilizado contém informações sobre os hábitos de estudo e desempenho acadêmico de estudantes.

| Tipo de variáveis | Exemplos                               |
| ----------------- | -------------------------------------- |
| Numéricas         | study\_hours\_per\_day, sleep\_hours   |
| Categóricas       | gender, diet\_quality, part\_time\_job |
| Alvo de análise   | exam\_score                            |

### 2. **Stellar Classification Dataset (SDSS17)**

Este dataset contém informações sobre objetos astronômicos e é utilizado para a classificação de **galáxias, estrelas e quasares**.

| Tipo de variáveis | Exemplos                                |
| ----------------- | --------------------------------------- |
| Numéricas         | alpha, delta, u, g, r, i, z, redshift   |
| Categóricas       | class (galaxy, star, quasar)            |
| Alvo de análise   | class (categoria do objeto astronômico) |

## 🔍 Etapas do Estudo

### **Parte 1: K-Means Clustering**

1. **Leitura e análise inicial dos dados**
2. **Levantamento de hipóteses** com base em observações do DataFrame
3. **Análise exploratória de dados (EDA)** com visualizações e estatísticas descritivas
4. **Pré-processamento:** codificação de variáveis categóricas e normalização
5. **Implementação do algoritmo K-Means from scratch**
6. **Justificativa do valor de K com o método do cotovelo**
7. **Visualização dos clusters com PCA**
8. **Análise crítica dos agrupamentos em relação às hipóteses**

### **Parte 2: Redes Neurais para Classificação Astronômica**

1. **Leitura e análise inicial dos dados**
2. **Pré-processamento dos dados**, incluindo normalização e codificação de variáveis categóricas
3. **Construção de um modelo de rede neural com regularização L2 e Dropout**
4. **Treinamento e avaliação do modelo**, com visualização do histórico de treinamento
5. **Análise de resultados** com métricas de precisão, recall, f1-score e matriz de confusão
6. **Avaliação final no conjunto de teste** para avaliar a performance real do modelo.

## 📈 Resultados

### **K-Means Clustering**

* O valor de **K = 3** foi escolhido como ideal com base no método do cotovelo.
* Foram identificados três perfis principais de estudantes:

  * Baixo desempenho, baixa carga de estudo e alto uso de redes sociais.
  * Desempenho intermediário, com trabalho de meio período.
  * Alto desempenho, bons hábitos de estudo, sono e saúde mental.

### **Redes Neurais**

* O modelo de rede neural alcançou uma **acurácia de 96,98%** no conjunto de teste.
* A **classe GALAXY** teve o melhor desempenho, seguida por **QSO** e **STAR**, com uma boa generalização para dados não vistos.
* Técnicas de **regularização L2** e **Dropout** ajudaram a evitar overfitting e garantiram uma boa capacidade de generalização do modelo.

## 🧠 Tarefas Extras

Inclui explicações teóricas sobre os seguintes algoritmos:

* **DBSCAN**
* **Hierarchical Clustering**
* **HDBSCAN** como algoritmo state-of-the-art para clusterização.

## ▶️ Como Executar

1. Faça o clone do repositório:

   ```bash
   git clone https://github.com/seu-usuario/UnB-CIS-Trainee.git
   ```

2. Abra o notebook no Google Colab ou Jupyter Notebook:

   * `estudo_clusterizacao_student_habits.ipynb`
   * `rede_neural_classificacao_astronomica.ipynb`

3. Certifique-se de ter os datasets (`student_habits_performance.csv` e `stellar_classification.csv`) na pasta correta ou montados via Google Drive no Colab.

## 🛠️ Tecnologias Utilizadas

* Python 3.10+
* Pandas, NumPy
* Seaborn, Matplotlib
* Scikit-learn (para normalização e PCA)
* TensorFlow (para redes neurais)

## 📎 Licença

Este projeto é apenas para fins educacionais, desenvolvido no contexto do **Treinamento CIS - 2º Período**.

---

Essa atualização inclui a parte sobre **Redes Neurais** e mantém as informações sobre o estudo de **K-Means Clustering**. Assim, o seu repositório estará completo com ambos os estudos de caso!
