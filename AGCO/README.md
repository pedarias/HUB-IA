# Projeto AGCO - HUB-IA SENAI

## Sobre o Projeto

Este repositório documenta o desenvolvimento de uma solução para analisar e corrigir discrepâncias em dados financeiros e operacionais da AGCO, comparando informações entre três sistemas distintos. O projeto integra um pipeline de ETL robusto para manipular diferentes formatos de dados (CSV, XML, XLSX), transformá-los e armazená-los em um banco de dados PostgreSQL. Através de uma API construída com FastAPI, o frontend desenvolvido em Streamlit interage com o backend, permitindo uploads de dados e visualização de análises diretamente pela interface do usuário.

## Arquitetura do Sistema

- **ETL Pipeline**: Extração de dados de diversos formatos, transformação dos mesmos e carga no banco de dados PostgreSQL.
- **FastAPI**: API que facilita as operações CRUD no banco de dados e serve como ponte entre o frontend e o backend.
- **Streamlit**: Interface gráfica que permite aos usuários interagir com os dados, fazer uploads e visualizar resultados de divergências.
- **Docker**: Utilizado para containerizar e orquestrar os componentes do sistema, garantindo facilidade de implantação e ambiente consistente.

## Funcionalidades

- **Divergência de Preço Unitário**: Identifica divergências entre os preços unitários nas NF-es comparando com os registrados nos contratos e outro sistema.
- **Divergência de Valor Total**: Compara valores totais de NF-es com os valores contratuais.
- **Verificação de Data de Emissão**: Confirma que todas as NF-es emitidas estão dentro do período de vigência dos contratos.
- **Análise por Município**: Analisa divergências distribuídas geograficamente.

## Tecnologias Utilizadas

- **Python**: Linguagem principal para o backend e scripts de ETL.
- **FastAPI**: Framework para construção de APIs de alto desempenho.
- **PostgreSQL**: Banco de dados relacional para armazenamento de dados.
- **Streamlit**: Framework para desenvolvimento do frontend.
- **Docker**: Plataforma para containerização do ambiente de desenvolvimento e produção.
