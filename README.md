# 🦷 Dental Implant Recognition

Sistema de Inteligência Artificial para **identificação de marcas de implantes dentários em radiografias**, utilizando técnicas de Deep Learning e Transfer Learning.

Projeto desenvolvido como Trabalho de Conclusão de Curso em **Bacharel em Ciências Exatas e Tecnologias na Universidade Federal do Recôncavo da Bahia (UFRB)**.

---

## 📌 Sobre o Projeto

Em situações clínicas, pacientes podem retornar anos após a instalação de um implante dentário sem possuir informações sobre o fabricante ou modelo utilizado.

A ausência dessas informações pode dificultar a escolha de componentes protéticos compatíveis.

Este projeto investiga o uso de **Inteligência Artificial e Visão Computacional** para auxiliar na identificação automática da marca de implantes dentários a partir de imagens radiográficas.

---

## 🎯 Objetivo

Desenvolver um modelo de classificação capaz de identificar diferentes marcas de implantes dentários presentes em radiografias utilizando redes neurais convolucionais e aprendizado por transferência.

---

## 🧠 Metodologia

O projeto utiliza:

- Redes Neurais Convolucionais (CNN)
- Transfer Learning
- ResNet50
- Processamento de imagens
- Data Augmentation
- Avaliação por métricas de classificação

---

## 🛠️ Tecnologias

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google_Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)

---

## 🏗️ Modelo

Foi utilizada a arquitetura **ResNet50** com Transfer Learning.

A ResNet utiliza conexões residuais (*skip connections*), permitindo o treinamento eficiente de redes neurais profundas.

O modelo pré-treinado é utilizado como extrator de características e posteriormente adaptado para a classificação das marcas de implantes presentes no conjunto de dados.

---

## 📊 Resultados

Os resultados obtidos pelo modelo foram:

| Métrica | Resultado |
|---|---:|
| Acurácia | **96,95%** |
| Precision Macro | **90,98%** |
| Recall Macro | **83,33%** |
| F1-score Macro | **86,82%** |
| AUC-ROC Macro | **95,57%** |
| AUC-PR Macro | **90,39%** |

---

## 📈 Avaliação

A avaliação do modelo inclui:

- Matriz de confusão
- Precision
- Recall
- F1-score
- AUC-ROC
- AUC-PR

Os gráficos e resultados experimentais serão disponibilizados na pasta `results/`.

---

## 📂 Estrutura do Projeto

```text
dental-implant-recognition/
│
├── notebooks/
│   └── training.ipynb
│
├── results/
│   ├── confusion_matrix.png
│   └── metrics/
│
├── images/
│
├── README.md
└── requirements.txt
