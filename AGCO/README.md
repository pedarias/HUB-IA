# Projetos POC para AGCO

## Sobre a AGCO

A AGCO, localizada em Duluth, Geórgia, é uma líder global na produção de equipamentos agrícolas. Anualmente, a empresa enfrenta desafios relacionados à emissão e análise de Notas Fiscais Eletrônicas (NF-e) devido a discrepâncias nos dados. Para superar esses desafios, a AGCO colaborou com o HUB de IA do SENAI para desenvolver um sistema automatizado e eficiente de gestão de NF-e, com análises estatísticas e visualizações gráficas interativas.

## Projetos Desenvolvidos

### Sprint 1: Automatização da Extração e Análise de Dados de NF-e

#### Objetivo
Focar na extração automática de dados das NF-es e estruturação em DataFrames com Python.

#### Tecnologias
- **Data Manipulation**: Pandas
- **Data Extraction**: XML parsing with `xml.etree.ElementTree`
- **Visualization**: Matplotlib, Plotly

#### Desenvolvimento
Utilizamos dados fictícios para simular a estrutura de NF-e, o que permitiu a experimentação com métodos de extração e visualização de dados. Desenvolvemos funções para filtrar e organizar esses dados, facilitando análises futuras e o entendimento das necessidades da empresa.

### Sprint 2: Desenvolvimento de Dashboards Interativos para Análise de NF-e

#### Objetivo
Criar visualizações interativas para análise detalhada dos dados de NF-e extraídos.

#### Tecnologias
- **Web Framework**: Streamlit
- **Data Analysis**: Pandas, SciPy

#### Desenvolvimento
Focamos na extração detalhada de dados dos arquivos XML das NF-e e na criação de um dashboard interativo em Streamlit que permitiu a visualização dinâmica dos dados, incluindo a correlação entre variáveis e identificação de padrões e anomalias.

### Sprint 3: Sistema de Gestão e Emissão de NF-e

#### Objetivo
Implementar um sistema completo para a gestão de NF-es, incluindo backend com FastAPI e frontend interativo com Streamlit.

#### Tecnologias
- **Backend**: FastAPI
- **Frontend**: Streamlit
- **Database**: DuckDB, SQLite

#### Desenvolvimento
Desenvolvemos funcionalidades para a automação da extração de dados de NF-e, armazenamento em DuckDB, e uma função de comparação de dados com um banco de dados fictício SQLite para identificar discrepâncias. A interface de usuário foi simplificada e otimizada para garantir uma experiência intuitiva e eficiente.

## Conclusão

Este projeto proporcionou uma solução robusta que atendeu às necessidades específicas da AGCO, melhorando significativamente a gestão e análise de dados fiscais. A colaboração entre a AGCO e o HUB de IA do SENAI demonstrou como a tecnologia pode ser utilizada para resolver problemas complexos em ambientes corporativos.

## Contato

Para mais informações ou discussões sobre colaborações futuras, entre em contato através de [Seu Email].

## Licença

Este repositório está licenciado sob a [Licença XYZ] - veja o arquivo LICENSE.md para mais detalhes.
