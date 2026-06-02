[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kenzo12032/IA-Agricultura-Drone/blob/main/Projeto_IA_Agricultura_Final.ipynb)
![GitHub repo size](https://img.shields.io/github/repo-size/kenzo12032/IA-Agricultura-Drone)
![GitHub last commit](https://img.shields.io/github/last-commit/kenzo12032/IA-Agricultura-Drone)
![Python](https://img.shields.io/badge/Python-3.12-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)

# 🌱 IA-Agricultura-Drone

Sistema de Inteligência Artificial para classificação de imagens agrícolas obtidas por drones e estimativa de vigor vegetativo utilizando Redes Neurais Convolucionais (CNN).

## 📋 Objetivo

Desenvolver um sistema capaz de analisar imagens agrícolas obtidas por drones, identificar padrões visuais presentes nas lavouras e estimar o vigor vegetativo com base na cobertura vegetal detectada.

## 🚁 Aplicação

O projeto foi desenvolvido com foco em Agricultura de Precisão, permitindo automatizar análises que normalmente exigiriam inspeções manuais em campo.

## 🧠 Tecnologias Utilizadas

* Python
* TensorFlow
* Keras
* OpenCV
* NumPy
* Matplotlib
* Scikit-Learn
* Gradio
* Google Colab

## 📦 Dataset.zip

O dataset utilizado neste projeto está disponível no próprio repositório através do arquivo:

- archive.zip

Após baixar o repositório, extraia o arquivo ou envie-o para o Google Colab antes da execução do notebook.
## 📊 Dataset

O conjunto de dados utilizado possui 1.927 imagens agrícolas divididas em quatro classes:

* Dolomite gypsum
* Fallow (left bare)
* Indian mustard (Brassica juncea)
* Rice husk charcoal

## ⚙️ Arquitetura

Foi utilizada uma Rede Neural Convolucional (CNN) composta por:

* Camadas Convolucionais
* Max Pooling
* Camadas Densas
* Dropout para redução de overfitting

## 📈 Resultados

O modelo apresentou excelente desempenho durante a validação:

* Accuracy: 100%
* Precision: 100%
* Recall: 100%
* F1-Score: 100%

## 🌿 Funcionalidades

* Classificação automática de imagens agrícolas
* Identificação da cobertura vegetal
* Estimativa de vigor vegetativo
* Interface de análise utilizando Gradio

## 👨‍🎓 Autor

Kenzo Ramos Otaguiri

Bacharelado em Sistemas de Informação

Universidade de Uberaba (UNIUBE)

2026
## 📊 Resultados

### Evolução da Acurácia

![Acurácia](Acurácia.png)

### Evolução do Erro (Loss)

![Loss](Loss.png)

### Matriz de Confusão

![Matriz](Matriz%20de%20confusão.png)

### Análise de Vigor Vegetativo

![Vigor](Vigor%20Vegetativo.png)
