# recommender-systems-tcc
Este repositório contém o código e os experimentos realizados para o Trabalho de Conclusão de Curso (TCC) em Engenharia de Computação, intitulado:

**"Estudo Comparativo entre Sistemas de Recomendação Tradicionais e Baseados em Deep Learning: Análise de Desempenho e Eficiência Computacional"**

## 📌 Objetivo

Comparar o desempenho preditivo e a eficiência computacional de quatro modelos de recomendação:

- **FunkSVD** (filtragem colaborativa tradicional)
- **TF-IDF** (filtragem baseada em conteúdo tradicional)
- **AutoRec** (modelo deep learning - colaborativo)
- **DistilRoBERTa** (modelo deep learning - baseado em conteúdo)

## 📊 Métricas Avaliadas

- **Desempenho preditivo**:
  - Precision@10
  - Recall@10
  - NDCG@10

- **Eficiência computacional**:
  - Tempo de treinamento
  - Tempo de inferência por usuário
  - Pico de uso de memória RAM

## 📁 Estrutura

- `recommender-systems-comparison.ipynb`: Notebook principal com os experimentos.
- `/results`: Métricas e gráficos gerados.


## 📦 Requisitos

- Python 3.10+
- Bibliotecas:
  - pandas, numpy, scikit-learn, surprise, torch, transformers, etc.
