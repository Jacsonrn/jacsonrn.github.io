---
layout: post
title: "Olá Mundo: Introdução à MLOps"
date: 2026-07-11 15:00:00 -0300
---

Bem-vindo ao novo blog técnico! Este é o seu primeiro artigo gerado automaticamente pelo Jekyll.

## O que é MLOps?

MLOps (Machine Learning Operations) é um conjunto de práticas que visa implantar e manter modelos de aprendizado de máquina em produção de forma confiável e eficiente. A palavra é um composto de "Machine Learning" e a prática de desenvolvimento contínuo "DevOps" do campo da engenharia de software.

### Exemplo de Código em Python

Aqui está como um bloco de código se parece no seu novo blog:

```python
import pandas as pd
from sklearn.model_selection import train_test_split
from sklearn.ensemble import RandomForestClassifier

# Carregando dados fictícios
def treinar_modelo(caminho_dados):
    df = pd.read_csv(caminho_dados)
    X = df.drop('alvo', axis=1)
    y = df['alvo']
    
    # Dividindo dados
    X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.2)
    
    # Treinando
    modelo = RandomForestClassifier()
    modelo.fit(X_train, y_train)
    
    return modelo

print("Pronto para deploy!")
```

## Próximos Passos
A partir de agora, para adicionar novos artigos, basta criar um arquivo `.md` na pasta `_posts/` seguindo a nomenclatura `ANO-MES-DIA-titulo.md`. O GitHub Pages cuidará de todo o resto.
