Sobre a empresa: A Trimble Transportation é uma divisão da Trimble Inc., especializada em soluções tecnológicas para transporte e logística, visando aumentar a eficiência e segurança na gestão de frotas através de inovações tecnológicas. Em parceria com o HUB de IA, foi propôsto a criação de POCs para analisar padrões de tráfego na plataforma, prever a fadiga dos motoristas, segmentar objetos soltos em cabines de veículos e detectar a presença de chuva nas imagens. 

 

POC1: Análise e Predição de Dados na Gestão de Frotas  

Tema: Análise exploratória de dados, Predição e Segmentação com Machine Learning 

Equipe:  Pedro H. Arias Oliveira, Renan Shibukawa 

Tecnologias: 

 

[Data Visualization]: Matplotlib, Plotly 

[Data Science]: Pandas, SciPy, PySpark 

[Machine Learning]: Scikit-Learn, K-means, Random Forest 

[Web Framework]: Streamlit 

Sobre o projeto: Na Sprint 1, fizemos uma análise exploratória dos dados, cujo objetivo foi investigar padrões de uso e interação dos usuários na plataforma Trimble utilizando dados do Google Analytics. Para facilitar a visualização, desenvolvemos um dashboard interativo em Streamlit que permite filtrar e analisar os dados de maneira eficiente. 

Na sprint 2, nosso objetivo foi identificar padrões operacionais que contribuem para a fadiga dos motoristas. Para isso utilizamos técnicas de Big Data com PySpark, algoritmos de segmentação como K-means e DBSCAN, e modelos preditivos como Random Forest. Os resultados incluíram a identificação de clusters de unidades operacionais com maior incidência de fadiga e a correlação de variáveis operacionais relevantes. 

 

POC2: Identificação e Segmentação de Objetos Soltos e Classificação de Chuva  

Tema: Visão Computacional  

Equipe: Pedro H. Arias Oliveira, Fernando Urizzi 

Tecnologias: 

 

[Data Visualization]: Matplotlib, Plotly 

[Deep Learning]: PyTorch e TensorFlow 

[Web Framework]: Streamlit 

 


 

Na sprint 3, a demanda foi voltada para Visão Computacional com o objetivo de identificar objetos soltos dentro das cabines dos veículos aumentando assim a segurança e organização interna. Portanto, implementamos um modelo de segmentação de objetos utilizando o algoritmo YOLOv9-SEG, o estado da arte até então. Adicionalmente, propusemos uma solução para automatizar a rotulação das imagens, empregando GroundingDINO e SAM para detecção e segmentação zero-shot. Essas tecnologias permitem identificar e segmentar novos objetos sem a necessidade de re-treinamento, tornando o processo mais eficiente podendo focar no que realmente importa. 

Na sprint4, nosso objetivo foi desenvolver um classificador de chuva utilizando imagens capturadas pelas câmeras frontais dos veículos. Este sistema visa aumentar a segurança ao identificar condições adversas, como chuva, que aumentam o risco de acidentes, especialmente em casos de alta velocidade ou comportamentos inadequados. Para isso, implementamos um modelo de rede neural convolucional (CNN) utilizando as bibliotecas Keras e TensorFlow. Este modelo foi treinado para detectar a presença de chuva nas imagens. 
