# minicurso_dl_medical
Repositório para mini-curso Aprendizado Profundo para análise de imagens médicas: dicas, truques e armadilhas

## Público-alvo: 

Estudantes e pesquisadores que desejam expandir seu conhecimento sobre o uso de IA para processamento de imagens médicas, incluindo aplicações como segmentação, classificação, detecção de imagens médicas e geração de relatórios textuais em variados tipos de imagens, como raios-X, tomografia computadorizada e ressonância magnética, incluindo notebooks com códigos e exemplos práticos.

## Resumo e Objetivos:

O aprendizado profundo (do inglês deep learning) faz parte do estado da arte no processamento de imagens médicas. Métodos baseados em aprendizado profundo geralmente envolvem a otimização de modelos para aprender a realizar tarefas com base em dados de exemplos de tarefas realizadas por médicos especialistas. Essas tarefas vão além de simplesmente detectar se uma imagem é de um paciente com uma doença, ou seja, diagnóstico automatizado, e também envolvem muitos outros fatores além da simples determinação de uma arquitetura de deep learning.

Neste curso, apresentaremos uma introdução ao campo, não focando em aplicações específicas, mas explorando muitos casos de uso, como segmentação semântica automatizada, diagnóstico e previsão de desfechos, regressão de informações demográficas, detecção de achados e até geração de texto. O curso será estruturado em três partes principais que resumem o processo de pesquisa na área: entrada, modelo e saída. Em cada parte, passaremos por um resumo teórico seguido de uma demonstração prática hands-on de problemas comuns e os benefícios de seguir certas diretrizes e melhores práticas em geral, muitas derivadas de nossa experiência na área.

A entrada, ou seja, os dados, é uma das partes mais importantes do processamento de imagens médicas. Como diz o ditado, "se entra lixo, sai lixo". Neste curso, os participantes terão uma visão geral desde ética e gestão de laboratório, até demonstrações práticas de maneiras otimizadas de ler dados durante o treinamento, com uma demonstração prática envolvendo a classificação de modalidades de RM. A arquitetura do modelo envolve muitos fatores e não há uma resposta definitiva sobre qual é a melhor arquitetura. Neste curso, os participantes terão uma compreensão básica do funcionamento interno dos dois paradigmas mais usados no processamento de imagens médicas: transformers e redes neurais convolucionais. Além disso, alunos verão na prática como esses modelos são capazes de realizar tarefas como geração de texto guiada por imagens. Finalmente, será apresentada uma visão ampla de métricas de avaliação e como usá-las no contexto da avaliação de classificação e segmentação de imagens médicas, focando nos pontos positivos e negativos de múltiplas métricas e como conduzir uma avaliação justa de sua pesquisa.

## Programa do Curso:
1. Visão geral do aprendizado profundo no processamento de imagens médicas 
2. Garbage in, garbage out 
  Teoria: Diretrizes e armadilhas a serem evitadas para não ter dores de cabeça com dados: da ética à curadoria, organização e armazenamento de dados em um ambiente de laboratório de pesquisa.
  Prática: pré-processamento e uso dos seus dados. Uma rede neural convolucional pode identificar modalidades de RM?
2. Modelos: o melhor? Depende. (1h)
  Teoria: Como funcionam realmente os modelos baseados em CNN e Transformer?
  Prática: Modelos multimodais envolvendo imagens e textos médicos.
3. Processamento e avaliação de saída: dos and don'ts. (40min)
  Teoria: Métricas são mais complicadas do que parece.
  Prática: O Dice não é tudo na avaliação de segmentação de imagens médicas.


