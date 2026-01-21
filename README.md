# C-lculo-de-M-tricas-de-Avalia-o-de-Aprendizado-
Matriz de Confusão Criada para a Premier League 2026
Baseado em estatísticas históricas da Premier League e projeções para 2026, criei a seguinte matriz de confusão hipotética:

Cenário: Previsão de Vitórias do Time Favorito
Total de jogos: 380 (uma temporada completa)

Classes:

Positiva: Time favorito vence

Negativa: Time favorito não vence (empate ou derrota)

Matriz de Confusão:
text
                     Previsto
                  Positivo  Negativo
Real  Positivo     180       45
      Negativo     60        95
Valores:
VP (Verdadeiros Positivos): 180

Vitórias corretamente previstas

FP (Falsos Positivos): 45

Vitórias previstas que não ocorreram (Erro Tipo I)

FN (Falsos Negativos): 60

Vitórias que ocorreram mas não foram previstas (Erro Tipo II)

VN (Verdadeiros Negativos): 95

Não-vitórias corretamente previstas

Métricas Calculadas pelo Programa
1. Acurácia (Accuracy)
text
Fórmula: (VP + VN) / Total
Cálculo: (180 + 95) / 380
Resultado: 0.7237 (72.37%)
Interpretação: O modelo acerta 72.37% das previsões

2. Sensibilidade/Recall
text
Fórmula: VP / (VP + FN)
Cálculo: 180 / (180 + 60)
Resultado: 0.7500 (75.00%)
Interpretação: O modelo identifica 75% das vitórias reais

3. Especificidade
text
Fórmula: VN / (VN + FP)
Cálculo: 95 / (95 + 45)
Resultado: 0.6786 (67.86%)
*Interpretação: O modelo identifica 67.86% das não-vitórias*

4. Precisão (Precision)
text
Fórmula: VP / (VP + FP)
Cálculo: 180 / (180 + 45)
Resultado: 0.8000 (80.00%)
Interpretação: Das vitórias previstas, 80% são realmente vitórias

5. F1-Score
text
Fórmula: 2 × (Precisão × Recall) / (Precisão + Recall)
Cálculo: 2 × (0.80 × 0.75) / (0.80 + 0.75)
Resultado: 0.7742 (77.42%)
Interpretação: Média harmônica balanceada entre Precisão e Recall

Como Usar o Programa
python
# Executar o programa principal
python matriz_confusao.py

# O programa oferece:
# 1. Três cenários diferentes para análise
# 2. Explicações detalhadas das métricas
# 3. Cálculos passo a passo
# 4. Interpretação dos resultados
Características do Programa
Implementação Completa: Todas as métricas calculadas do zero

Explicações Detalhadas: Cada cálculo é mostrado passo a passo

Cenários Realistas: Baseados em estatísticas reais de futebol

Visualização Clara: Matrizes formatadas para fácil leitura

Análise Estatística: Informações adicionais sobre distribuição dos dados

Métricas Adicionais Calculadas
O programa também calcula:

Taxa de Falsos Positivos (FPR): 32.14%

Taxa de Falsos Negativos (FNR): 25.00%

Valor Preditivo Negativo (NPV): 61.29%

Este projeto é ideal para entender na prática como funcionam as métricas de avaliação de modelos de classificação, com um exemplo concreto baseado em previsões esportivas!
