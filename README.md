# Coletor de Taxa CDI e Gráfico

Este projeto foi feito com base no Curso de Python para Análise de Dados da EBAC (Escola Britânica de Artes Criativas & Tecnologia), que fiz em 03/2023.
Ele consiste em um script em Python para coletar a taxa CDI do site da B3 e gerar um gráfico com as taxas coletadas ao longo do tempo. O script utiliza bibliotecas como `requests`, `json`, `time`, `pandas`, `seaborn`, `os` e `datetime` para realizar as operações.

## Coleta de Taxa CDI

O script faz uma requisição para o site da B3 para obter a taxa CDI. Em seguida, armazena a data, hora e a taxa em um arquivo CSV chamado "taxa-cdi.csv". O processo é repetido várias vezes para simular a coleta ao longo do tempo.

## Geração do Gráfico

Após a coleta dos dados, o script utiliza a biblioteca `pandas` para ler o arquivo CSV e extrair as colunas de hora e taxa. Em seguida, a biblioteca `seaborn` é utilizada para criar um gráfico de linha que representa a variação da taxa CDI ao longo do tempo. O gráfico é salvo como uma imagem chamada "grafico-cdi.png".

## Utilização

Ao executar o script, ele realizará a coleta de dados em intervalos regulares e gerará o gráfico com as taxas acumuladas.

## Tecnologias Utilizadas

- **Python:** Linguagem de programação utilizada para desenvolver o script.
- **Bibliotecas Python:** `requests`, `json`, `time`, `pandas`, `seaborn`, `os` e `datetime`.

## Contato

- **Email:** mahtostes.dev@gmail.com
- **LinkedIn:** [LinkedIn - Marília Ribeiro Tostes](https://www.linkedin.com/in/marilia-ribeiro-tostes/)
- **Whatsapp:** [Fale comigo!](https://wa.me/5567981443147)
