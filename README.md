## Objetivo
O objetivo entender melhor como classificar títulos de notícias e textos em geral, a partir de dados pré-rotulados, utilizando modelos de aprendizado de máquina.

![Amostras](/imgs/under_samples_freqs.png)

## Descrição do Projeto
Este projeto visa resolver o desafio de classificação automática de títulos de notícias, um problema comum em processamento de linguagem natural (PLN). Ao treinar e avaliar diferentes modelos de aprendizado de máquina, buscamos encontrar a melhor abordagem para essa tarefa, o que pode ter aplicações em diversas áreas, como organização de conteúdo, recomendação de notícias e detecção de tendências.

## Classificador
Este classificador utiliza bibliotecas como:
- scikit-learn (sklearn)
- NLTK

Analisando dados, treinando e avaliando modelos como:
- Regressão Logística (LR)
- Naive Bayes Multinomial (NB)
- Máquina de Vetores de Suporte Linear (SVM)
- Floresta Aleatória (RF)

![Precisão](/imgs/accuracy.png)

### Exemplos de Classificação
- **Texto:** Os estudantes de engenharia demoram o dobro do tempo na faculdade.
  - **Predição:** educação

- **Texto:** O vírus comeu o soldo.
  - **Predição:** saúde

- **Texto:** Jogar League of Legends dá raiva.
  - **Predição:** esporte

- **Texto:** Eu gosto de carros
  - **Predição:** carro