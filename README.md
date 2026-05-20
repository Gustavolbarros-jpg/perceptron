# Perceptron — Learning from Data

Implementação do PLA (Perceptron Learning Algorithm) aplicado ao dataset de dígitos.
Classificação binária: **dígito 1 vs todos os outros**.

## Resultados

| | Erro |
|---|---|
| E_in (treino) | 1.51% |
| E_out (teste) | 2.14% |

## Como rodar

**Opção 1 — Jupyter local**
```bash
pip install jupyter numpy matplotlib
jupyter notebook perceptron_digits.ipynb
```

**Opção 2 — Google Colab**

1. [colab.research.google.com](https://colab.research.google.com) → fazer upload do `.ipynb`
2. No painel esquerdo (ícone de pasta) → subir `digits.train` e `digits.test`
3. `Ctrl+F9` pra rodar tudo

## Arquivos

```
perceptronml/
├── perceptron_digits.ipynb   # notebook principal
├── digits.train              # dados de treino
├── digits.test               # dados de teste
└── fronteira_decisao.png     # plot gerado
```
