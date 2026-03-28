# Regressão de Impacto - Implementação Pura (Scikit-Learn)

Este projeto realiza a modelagem de aceleração em impactos de motocicleta utilizando apenas bibliotecas base e o Scikit-Learn, sem a necessidade de dependências pesadas como Pandas ou NumPy para o processamento de dados.

## 1. Destaques da Implementação
- **Processamento de Dados:** Leitura via módulo `csv` nativo do Python.
- **Cálculos Matemáticos:** Implementação manual de RMSE e geração de intervalos utilizando o módulo `math`.
- **Modelagem:** Comparação entre Adaline e arquiteturas MLP (Adam vs LBFGS).

## 2. Requisitos de Ambiente
O código foi projetado para rodar nativamente no **Google Colab**, utilizando as bibliotecas já disponíveis no ambiente:
- `scikit-learn`
- `matplotlib`
- `csv`

## 3. Como usar no Colab
1. Abra um novo notebook no Google Colab.
2. No menu lateral esquerdo, clique no ícone de pasta (**Arquivos**) e faça o upload do arquivo `dataset-mycicle.csv`.
3. Cole o código e execute as células.
