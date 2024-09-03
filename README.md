# Minicurso: Aprendizado Profundo para análise de imagens médicas
Repositório para mini-curso Aprendizado Profundo para análise de imagens médicas: dicas, truques e armadilhas

## Público-alvo: 

Estudantes e pesquisadores que desejam expandir seu conhecimento sobre o uso de IA para processamento de imagens médicas, incluindo aplicações como segmentação, classificação, detecção de imagens médicas e geração de relatórios textuais em variados tipos de imagens, como raios-X, tomografia computadorizada e ressonância magnética, incluindo notebooks com códigos e exemplos práticos.

## Resumo e Objetivos:

Neste curso, apresentaremos uma introdução ao campo do aprendizado profundo em imagens médicas, não focando em aplicações específicas, mas explorando muitos casos de uso, como segmentação semântica automatizada, diagnóstico e previsão de desfechos, regressão de informações demográficas, detecção de achados e até geração de texto. O curso será estruturado em três partes principais que resumem o processo de pesquisa na área: entrada, modelo e saída. Em cada parte, passaremos por um resumo teórico seguido de uma demonstração prática hands-on de problemas comuns e os benefícios de seguir certas diretrizes e melhores práticas em geral, muitas derivadas de nossa experiência na área.

## Programa do Curso:
1. Visão geral do aprendizado profundo no processamento de imagens médicas 
2. Garbage in, garbage out 
  - *Teoria:* Diretrizes e armadilhas a serem evitadas para não ter dores de cabeça com dados: da ética à curadoria, organização e armazenamento de dados em um ambiente de laboratório de pesquisa.
  - *Prática:* pré-processamento e uso dos seus dados. Uma rede neural convolucional pode identificar modalidades de RM?
2. Modelos: o melhor? Depende
  - *Teoria:* Como funcionam realmente os modelos baseados em CNN e Transformer?
  - *Prática:* Modelos multimodais envolvendo imagens e textos médicos.
3. Processamento e avaliação de saída: dos and don'ts
  - *Teoria:* Métricas são mais complicadas do que parece.
  - *Prática:* O Dice não é tudo na avaliação de segmentação de imagens médicas.

## Materiais utilizados

- [Slides](slides/.)
- Notebooks

## Outros materiais interessantes sobre o assunto

### Parte 1 - sobre dados
1. Diaz, Oliver, et al. "Data preparation for artificial intelligence in medical imaging: A comprehensive guide to open-access platforms and tools." Physica medica 83 (2021): 25-37. [Link](https://www.physicamedica.com/article/S1120-1797(21)00095-8/fulltext)
2. Carmo, Diedre, et al. "Automated computed tomography and magnetic resonance imaging segmentation using deep learning: a beginner's guide." arXiv preprint arXiv:2304.05901 (2023). [Link](https://arxiv.org/pdf/2304.05901)

### Parte 2 - sobre modelos
1. Vaswani, A. "Attention is all you need." Advances in Neural Information Processing Systems (2017). [Link](https://user.phil.hhu.de/~cwurm/wp-content/uploads/2020/01/7181-attention-is-all-you-need.pdf)
2. Tan, Mingxing. "Efficientnet: Rethinking model scaling for convolutional neural networks." arXiv preprint arXiv:1905.11946 (2019). [Link](https://arxiv.org/pdf/1905.11946)
3. Visualizando CNNs: CNN Explainer [Link](https://poloclub.github.io/cnn-explainer/)
4. Visualizando Transformers: Transformer Explainer [Link](https://poloclub.github.io/transformer-explainer/)

### Parte 3 - sobre métricas
1. Maier-Hein, Lena, et al. "Metrics reloaded: recommendations for image analysis validation." Nature methods 21.2 (2024): 195-212. [Link](https://www.nature.com/articles/s41592-023-02151-z) [Framework](https://metrics-reloaded.dkfz.de/)
3. Reinke, Annika, et al. "Understanding metric-related pitfalls in image analysis validation." Nature methods 21.2 (2024): 182-194. [Link](https://www.nature.com/articles/s41592-023-02150-0)
4. Müller, Dominik, Iñaki Soto-Rey, and Frank Kramer. "Towards a guideline for evaluation metrics in medical image segmentation." BMC Research Notes 15.1 (2022): 210. [Link](https://bmcresnotes.biomedcentral.com/articles/10.1186/s13104-022-06096-y)
5. Taha, Abdel Aziz, and Allan Hanbury. "Metrics for evaluating 3D medical image segmentation: analysis, selection, and tool." BMC medical imaging 15 (2015): 1-28. [Link](https://link.springer.com/content/pdf/10.1186/s12880-015-0068-x.pdf)

## Sobre os organizadores deste curso

*Letícia Rittner, PhD* - Professora na Faculdade de Engenharia Elétrica e de Computação, UNICAMP
[LinkedIn](https://www.linkedin.com/in/leticia-rittner-918482/) [Google Scholar](https://scholar.google.com.br/citations?user=pVEK9qkAAAAJ&hl=en)

*Diedre Carmo, PhD* - Pesquisador de pós-doutorado na Faculdade de Engenharia Elétrica e de Computação, UNICAMP
[LinkedIn](https://www.linkedin.com/in/diedre-carmo-4490572b/) [Google Scholar](https://scholar.google.com.br/citations?user=YjA3hdoAAAAJ&hl=en)

Medical Image Computing Lab ([MICLab](https://miclab.fee.unicamp.br/))

