# Modelo de Predição de Churn de Clientes

Este repositório contém um script Python projetado para prever o churn de clientes com base em dados históricos. Utilizando um modelo de regressão logística, este projeto visa ajudar empresas a identificar clientes em risco de cancelamento, permitindo intervenções proativas para melhorar a retenção.

## Funcionalidades

- Carrega e limpa dados de um arquivo Excel.
- Transforma variáveis categóricas usando `pd.get_dummies`.
- Aplica um modelo de regressão logística para prever o churn.
- Calcula e exibe métricas de desempenho do modelo, como acurácia, precisão, recall, F1 Score e ROC-AUC.
- Exibe matrizes de confusão para dados de treino e teste.

## Como Usar

1. Clone este repositório para sua máquina local.
2. Instale as dependências necessárias utilizando `pip install -r requirements.txt` (você precisará criar este arquivo).
3. Execute o script com `python metricaschurn.py`.

## Dependências

- pandas
- numpy
- scikit-learn
- matplotlib

## Dados

Os dados usados neste script são fornecidos em um arquivo Excel chamado `churn_data.xlsx`. Assegure-se de que este arquivo esteja no diretório correto ou atualize o caminho no script conforme necessário.

## Contribuições

Contribuições são bem-vindas! Se você tem sugestões de melhorias ou correções, faça um fork do repositório e submeta um pull request.

## Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo LICENSE.md para detalhes.
