# Detecção de Capacetes com YOLO

Este repositório contém os códigos e materiais desenvolvidos para o Trabalho de Conclusão de Curso (TCC), cujo objetivo é realizar a detecção de capacetes de segurança utilizando técnicas de Visão Computacional e modelos da família YOLO.

O projeto foi desenvolvido em Python, utilizando o Google Colab para treinamento e execução dos modelos.

## Objetivo

O projeto tem como objetivo desenvolver e avaliar modelos de detecção de objetos capazes de identificar a utilização de capacetes em imagens e vídeos.

Para isso, foram utilizados e comparados diferentes modelos da arquitetura YOLO:

* YOLOv5n
* YOLOv8n
* YOLOv9

Os modelos são avaliados utilizando métricas de desempenho para detecção de objetos, como:

* Precisão (Precision)
* Revocação (Recall)
* F1-Score
* mAP@0.5
* mAP@0.5:0.95
* Matriz de Confusão
* Losses durante o treinamento

## Estrutura do projeto


helmet_detection_tcc/
│
├── notebooks/
│   └── helmet_detection_tcc.ipynb
│
├── models/
│   └── pesos dos modelos treinados
│
├── results/
│   ├── gráficos
│   ├── matrizes de confusão
│   └── métricas
│
├── README.md
└── requirements.txt


A estrutura dos diretórios poderá ser atualizada conforme a organização final dos arquivos do projeto.

## Dataset

Para o desenvolvimento do projeto foi utilizado um dataset público de detecção de capacetes, contendo imagens utilizadas para treinamento, validação e teste dos modelos.

Para executar o treinamento ou reproduzir os experimentos, é necessário possuir o dataset utilizado no projeto.

O dataset não está incluído diretamente neste repositório devido ao seu tamanho. Ele deverá ser disponibilizado separadamente.

## Pesos dos modelos

Os modelos utilizados neste projeto foram previamente treinados com o dataset utilizado no TCC.

Para executar os modelos já treinados, é necessário possuir os respectivos arquivos de pesos (.pt).

Os pesos treinados utilizados nos experimentos serão disponibilizados separadamente neste projeto.

Os principais pesos utilizados sã
