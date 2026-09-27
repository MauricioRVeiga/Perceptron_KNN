# Perceptron_KNN

## AT1 - Perceptron e KNN em Prática

Trabalho prático individual de implementação dos modelos **Perceptron com Treinamento Automático**, **Classificador K-Nearest Neighbors (KNN)** e **Recomendador por Similaridade Espacial**, utilizando a biblioteca NumPy.

### Conteúdo

O notebook [`at1_am.ipynb`](at1_am.ipynb) está dividido em três seções:

1. **Desafio 1 — Classificação Binária com Perceptron Treinável**: triagem de transações financeiras com potencial risco de fraude, a partir do valor normalizado da transação e da frequência de operações recentes.
2. **Desafio 2 — Predição de Risco de Churn com Classificador KNN**: antecipação de risco de cancelamento de clientes SaaS, a partir dos dias de inatividade e chamados críticos em aberto.
3. **Desafio 3 — Recomendação de Servidores Cloud por Similaridade Espacial**: dimensionamento automático de VMs recomendadas por menor distância euclidiana em relação ao perfil de hardware demandado.

### Como executar

```bash
pip install numpy notebook
jupyter notebook at1_am.ipynb
```

Execute todas as células do início ao fim (Restart Kernel and Run All Cells) para reproduzir os resultados.
