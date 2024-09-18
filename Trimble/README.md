# Projeto Trimble Transportation - HUB-IA SENAI

## Sobre a Empresa
Trimble Transportation é uma divisão da Trimble Inc., especializada em soluções tecnológicas para transporte e logística, visando aumentar a eficiência e segurança na gestão de frotas através de inovações tecnológicas. Em parceria com o HUB de IA, foi proposta a criação de Provas de Conceito (POCs) divididas em 4 Sprints.

### POC1: Análise e Predição de Dados na Gestão de Frotas

#### Tema
Análise exploratória de dados, Predição e Segmentação com Machine Learning.

#### Tecnologias
- **Data Visualization**: Matplotlib, Plotly
- **Data Science**: Pandas, SciPy, PySpark
- **Machine Learning**: Scikit-Learn

#### Sobre o Projeto
Na **Sprint 1**, realizamos uma análise exploratória dos dados, com o objetivo de investigar padrões de uso e interação dos usuários na plataforma Trimble, utilizando dados fornecidos por eles. Desenvolvemos um dashboard interativo em Streamlit que permite filtrar e analisar os dados de maneira eficiente.

Na **Sprint 2**, nosso objetivo foi identificar padrões operacionais que contribuem para a fadiga dos motoristas. Utilizamos técnicas de Big Data com PySpark, algoritmos de segmentação como K-means e DBSCAN (Aprendizado Não Supervisionado), e modelos preditivos como Random Forest (Aprendizado Supervisionado). Os resultados incluíram a identificação de clusters de unidades operacionais com maior incidência de fadiga e a correlação de variáveis operacionais mais contribuintes para fadiga.

### POC2: Identificação e Segmentação de Objetos Soltos e Classificação de Chuva

#### Tema
Visão Computacional

#### Tecnologias
- **Data Visualization**: Matplotlib, Plotly
- **Deep Learning**: PyTorch, Keras e TensorFlow

#### Sobre o Projeto
Na **Sprint 3**, a demanda foi voltada para Visão Computacional com o objetivo de identificar objetos soltos dentro das cabines dos veículos, aumentando assim a segurança e organização interna. Implementamos um modelo de segmentação de objetos utilizando o algoritmo YOLOv9-SEG, o estado da arte até então. Propusemos uma solução para automatizar a rotulação das imagens, empregando GroundingDINO e SAM para detecção e segmentação zero-shot. Essas tecnologias permitem identificar e segmentar novos objetos sem a necessidade de re-treinamento.

Na **Sprint 4**, nosso objetivo foi desenvolver um classificador de chuva utilizando imagens capturadas pelas câmeras frontais dos veículos. Este sistema visa aumentar a segurança ao identificar condições adversas, como chuva, que aumentam o risco de acidentes, especialmente em casos de alta velocidade ou comportamentos inadequados. Implementamos um modelo de rede neural convolucional (CNN) utilizando as bibliotecas Keras e TensorFlow. O modelo foi treinado para detectar a presença de chuva nas imagens, utilizando o conceito de Transfer Learning e Fine Tuning para ajustar os modelos pré-treinados para o nosso dataset específico. O modelo inicialmente atingiu 91% de acurácia no conjunto de teste, demonstrando Overfitting. Portanto, aplicamos camadas de regularização e Callbacks para monitorar a perda no conjunto de validação e lidar com o overfitting. O modelo com regularizadores aumentou sua acurácia para 93% no conjunto de teste.
