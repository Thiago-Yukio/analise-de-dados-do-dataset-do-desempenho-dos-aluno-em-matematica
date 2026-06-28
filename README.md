# Análise de Dados do Dataset de Desempenho dos Alunos em Matemática

## Contexto do Problema

### Descrição do conjunto de dados

Esta análise utiliza o conjunto de dados **Student Performance**, disponibilizado por **Cortez (2008)** no UCI Machine Learning Repository. O dataset reúne informações sobre o desempenho de estudantes do ensino secundário (ensino médio) de duas escolas portuguesas, incluindo características demográficas, sociais, familiares e escolares, obtidas por meio de boletins escolares e questionários.

No trabalho original, o conjunto de dados foi utilizado para o desenvolvimento de modelos de **regressão**, **classificação binária** e **classificação multiclasse**, com o objetivo de prever o desempenho acadêmico dos estudantes.

Neste projeto foi utilizado o arquivo **`student-mat.csv`**, que contém informações referentes ao desempenho dos alunos na disciplina de Matemática. Além das notas, o conjunto apresenta diversas variáveis que podem influenciar o desempenho escolar, permitindo a construção e avaliação de modelos de aprendizado de máquina.

### Referência

> Cortez, P. (2008). *Student Performance* [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5TG7T

---

# Pré-processamento dos Dados

Antes do treinamento dos modelos, foi realizada uma etapa de preparação dos dados, contemplando:

* tratamento e padronização dos dados;
* renomeação das colunas para facilitar a interpretação e a manipulação durante a análise.

---

# Objetivos

O projeto possui dois objetivos principais:

## 1. Previsão das notas finais dos estudantes

Desenvolver e comparar diferentes modelos de aprendizado de máquina para prever a nota final dos alunos na disciplina de Matemática.

**Resultados**

### Modelos de Regressão

<img width="427" height="124" alt="image" src="https://github.com/user-attachments/assets/15e7ecb9-d059-47c2-a259-f4cd77e7f36b" />

### Modelos de Classificação

<img width="361" height="126" alt="image" src="https://github.com/user-attachments/assets/207c8e43-e1c1-424a-9891-ffd8c33c25d1" />

---

## 2. Previsão da reprovação dos estudantes

Desenvolver e comparar modelos capazes de prever se um estudante será aprovado ou reprovado na disciplina de Matemática.

**Resultados**

### Modelos de Regressão

<img width="416" height="123" alt="image" src="https://github.com/user-attachments/assets/cce954cf-1931-4857-b44c-bcdebff9e64d" />

### Modelos de Classificação

<img width="360" height="122" alt="image" src="https://github.com/user-attachments/assets/e782e033-f598-48fb-8849-55105420990c" />

---

# Conclusão:

