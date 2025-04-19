# Pronunciamentos do Presidente - Raspagem e Mineração de Dados

⚠️ **Atenção**: Este projeto é um exercício de raspagem, mineração e transformação de dados, inspirado no canal [Programação Dinâmica](https://www.youtube.com/c/ProgramacaoDinamica). O objetivo é extrair pronunciamentos oficiais do Presidente Lula em 2025 e transformá-los em dados estruturados (JSON).

## 📌 Visão Geral
Este projeto realiza:
- Raspagem de dados dos discursos presidenciais do site oficial do Planalto
- Processamento e limpeza dos dados
- Armazenamento em formato JSON para análise posterior

## 🌐 Fonte dos Dados
Todos os dados são coletados do portal oficial do Governo Federal:
- [Discursos e Pronunciamentos do Presidente Lula (2025)](https://www.gov.br/planalto/pt-br/acompanhe-o-planalto/discursos-e-pronunciamentos)

## ⚙️ Tecnologias Utilizadas
- **Python** como linguagem principal
- Bibliotecas:
  - `requests` - Para fazer requisições HTTP
  - `bs4` (BeautifulSoup) - Para parsing e extração de dados HTML
  - `json` - Para manipulação de arquivos JSON
  - `os` - Para operações com sistema de arquivos
  - `jupyter` - Para desenvolvimento interativo (opcional)