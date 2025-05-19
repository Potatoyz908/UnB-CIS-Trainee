# Student Clustering with K-Means

Este repositório apresenta um estudo de caso completo sobre agrupamento de estudantes com base em seus hábitos e desempenho acadêmico, utilizando o algoritmo K-Means implementado do zero.

## 📌 Objetivo

Aplicar técnicas de aprendizado não supervisionado para identificar padrões ocultos em um conjunto de dados multidimensional sobre hábitos de estudantes. O objetivo principal é investigar como fatores comportamentais (como tempo de estudo, sono, uso de redes sociais, qualidade da saúde mental, entre outros) se relacionam com o desempenho acadêmico (nota final em exames).

## 📊 Dataset

O dataset utilizado foi **Student Habits vs Academic Performance**, contendo 17 variáveis (numéricas e categóricas) que descrevem o perfil de comportamento de cada estudante.

| Tipo de variáveis | Exemplos                           |
|-------------------|------------------------------------|
| Numéricas          | study_hours_per_day, sleep_hours   |
| Categóricas        | gender, diet_quality, part_time_job |
| Alvo de análise    | exam_score                         |

## 🔍 Etapas do Estudo

1. **Leitura e análise inicial dos dados**
2. **Levantamento de hipóteses** com base em observações do DataFrame
3. **Análise exploratória de dados (EDA)** com visualizações e estatísticas descritivas
4. **Pré-processamento:** codificação de variáveis categóricas e normalização
5. **Implementação do algoritmo K-Means from scratch**
6. **Justificativa do valor de K com o método do cotovelo**
7. **Visualização dos clusters com PCA**
8. **Análise crítica dos agrupamentos em relação às hipóteses**
9. **Tarefas extras:** estudo teórico dos algoritmos DBSCAN, Hierarchical e do state-of-the-art HDBSCAN

## 📈 Resultados

- O valor de **K = 3** foi escolhido como ideal com base no método do cotovelo.
- Foram identificados três perfis principais de estudantes:
  - Baixo desempenho, baixa carga de estudo e alto uso de redes sociais.
  - Desempenho intermediário, com trabalho de meio período.
  - Alto desempenho, bons hábitos de estudo, sono e saúde mental.

A clusterização revelou padrões coerentes com as hipóteses formuladas, validando a abordagem utilizada.

## 🧠 Tarefas Extras

Inclui explicações teóricas sobre os seguintes algoritmos:
- **DBSCAN**
- **Hierarchical Clustering**
- **HDBSCAN** como algoritmo state-of-the-art para clusterização.

## ▶️ Como Executar

1. Faça o clone do repositório:
   ```bash
   git clone https://github.com/seu-usuario/student-clustering-kmeans.git
    ```

2. Abra o notebook no Google Colab ou Jupyter Notebook:

   * `estudo_clusterizacao_student_habits.ipynb`

3. Certifique-se de ter o dataset `student_habits_performance.csv` na pasta correta (ou montado via Google Drive no Colab).

## 🛠️ Tecnologias Utilizadas

* Python 3.10+
* Pandas, NumPy
* Seaborn, Matplotlib
* Scikit-learn (para normalização e PCA)

## 📎 Licença

Este projeto é apenas para fins educacionais, desenvolvido no contexto do **Treinamento CIS - 2º Período**.
