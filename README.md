# pythonDataProject

Análise exploratória da evolução da Covid-19 comparando **Brasil e China**, feita em 2021 como projeto acadêmico em dupla.

> 📚 Projeto de estudo de 2021, mantido como registro da minha evolução. Para os meus projetos atuais de engenharia de dados, veja o [meu perfil](https://github.com/thalesreiser).

## Pergunta

Uma reportagem da BBC Brasil de fevereiro de 2020 mostrava o avanço da Covid-19 na China. O projeto compara essa situação com o Brasil **no mesmo estágio da pandemia** (o primeiro mês de cada série) e também no último mês disponível nos dados.

## O que foi analisado

| Variável | Descrição |
|---|---|
| `total_cases` | Casos confirmados acumulados |
| `total_cases_per_million` | Casos acumulados por milhão de habitantes |
| `total_deaths` | Óbitos acumulados |
| `total_deaths_per_million` | Óbitos acumulados por milhão de habitantes |

Gráficos gerados:
- Casos totais e óbitos totais no primeiro mês da série (linhas)
- Óbitos por milhão no último mês da série (linhas)
- Casos por milhão no último mês da série (dispersão)

A normalização **por milhão de habitantes** é o ponto central da comparação: em números absolutos, dois países com populações tão diferentes não são comparáveis.

## Stack

Python · Pandas · NumPy · Matplotlib · Jupyter (Google Colab)

## Dados

[COVID-19 dataset do Our World in Data](https://github.com/owid/covid-19-data) (`owid-covid-data.csv`). O arquivo não está versionado aqui. Para rodar, baixe-o e ajuste o caminho na segunda célula do notebook.

## Autores

Thales Reiser Pedreira e Guilherme Machado.
