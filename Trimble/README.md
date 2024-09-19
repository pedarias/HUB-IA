# Projeto Trimble Transportation - HUB-IA SENAI

![](images/Trimble-logo.png)

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
Na **Sprint 1**, foi realizada uma análise exploratória dos dados com o objetivo de investigar padrões de uso e interação dos usuários na plataforma Trimble, utilizando dados fornecidos pela empresa. Foi desenvolvido um dashboard interativo em Streamlit que permite a filtragem e análise dos dados de forma eficiente.

Na **Sprint 2**, o objetivo foi identificar padrões operacionais relacionados à fadiga dos motoristas. Utilizando técnicas de Big Data com PySpark, aplicamos algoritmos de segmentação como K-means e DBSCAN (Aprendizado Não Supervisionado), além de modelos preditivos como Random Forest (Aprendizado Supervisionado). Os resultados incluíram a identificação de clusters operacionais com maior incidência de fadiga e a correlação de variáveis operacionais que mais contribuem para esse cenário.

![](images/PCA.png)

### POC2: Identificação e Segmentação de Objetos Soltos e Classificação de Chuva

#### Tema
Visão Computacional

#### Tecnologias
- **Data Visualization**: Matplotlib, Plotly
- **Deep Learning**: PyTorch, Keras e TensorFlow

#### Sobre o Projeto
Na **Sprint 3**, o foco foi Visão Computacional, visando identificar objetos soltos nas cabines dos veículos para aumentar a segurança e a organização interna. Foi implementado um modelo de segmentação de objetos utilizando o algoritmo YOLOv9-SEG. Também foi proposta uma solução para automação da rotulação de imagens, empregando as tecnologias GroundingDINO e SAM para detecção e segmentação zero-shot, permitindo a identificação e segmentação de novos objetos sem necessidade de re-treinamento.

Na **Sprint 4**, o objetivo foi desenvolver um classificador de condições de chuva com base em imagens capturadas pelas câmeras frontais dos veículos. O sistema visa aumentar a segurança ao detectar condições adversas, como chuva, que elevam o risco de acidentes. Implementamos um modelo de rede neural convolucional (CNN) utilizando as bibliotecas Keras e TensorFlow. O modelo foi treinado para identificar a presença de chuva nas imagens, empregando **Transfer Learning e Fine Tuning** para ajustar os modelos pré-treinados ao nosso dataset específico. Embora o modelo inicial tenha apresentado bons resultados no conjunto de teste, observamos sinais de overfitting. Assim, foram aplicadas camadas de regularização e Callbacks para monitorar a perda no conjunto de validação e mitigar o overfitting. O modelo regularizado demonstrou melhora no desempenho no conjunto de teste.

![Ilustração Transfer Learning and Fine Tuning](images/EnsembleTransferLearning.png)
*Fonte Imagem: [Ensemble Transfer Learning Framework for Vessel Size Estimation from 2D Images](https://www.researchgate.net/publication/333619654_Ensemble_Transfer_Learning_Framework_for_Vessel_Size_Estimation_from_2D_Images)*