# Exemplo de utilização do Optuna

Este repositório contém um exemplo de utilização do framework Optuna em Python para otimização de parâmetros de um modelo de machine learning. O Optuna é uma biblioteca de otimização de hiperparâmetros automatizada e de código aberto, que permite encontrar automaticamente os melhores hiperparâmetros para um modelo através de técnicas de busca em espaço hiperparamétrico.

# Requerimentos
Certifique-se de ter os seguintes requisitos instalados em seu ambiente de desenvolvimento:

- Python 3.8 ou superior
- Bibliotecas necessárias: podem ser instaladas usando pip install -r requirements.txt

# Arquivos

- exemplo_optuna.ipynb: Notebbok com todo o exemplo de utilização, desde a criação dos dados sintéticos, busca paramétrica e modelagem final.
- optuna-journal-xgboost-shap.log: log do optuna com os dados da otimização. Se esse arquivo existir e for chamado no código, o estudo anterior é carregado e pode ser continuado.
