<!-- Samuel Pires — GitHub Profile README (atualizado em 25/10/2026) -->

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)"
      srcset="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,40:0d2b55,100:1f6feb&height=180&section=header&text=Samuel%20Pires&fontSize=50&fontColor=58a6ff&fontAlignY=38&desc=Engenheiro%20de%20Dados%20Jr.%20%7C%20Python%20%2B%20SQL%20%2B%20Airflow&descAlignY=60&descSize=15&descColor=8b949e">
    <source media="(prefers-color-scheme: light)"
      srcset="https://capsule-render.vercel.app/api?type=waving&color=0:1f6feb,40:388bfd,100:58a6ff&height=180&section=header&text=Samuel%20Pires&fontSize=50&fontColor=ffffff&fontAlignY=38&desc=Engenheiro%20de%20Dados%20Jr.%20%7C%20Python%20%2B%20SQL%20%2B%20Airflow&descAlignY=60&descSize=15&descColor=dde3ea">
    <img alt="Samuel Pires — Engenheiro de Dados Júnior"
      src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,40:0d2b55,100:1f6feb&height=180&section=header&text=Samuel%20Pires&fontSize=50&fontColor=58a6ff&fontAlignY=38&desc=Engenheiro%20de%20Dados%20Jr.%20%7C%20Python%20%2B%20SQL%20%2B%20Airflow&descAlignY=60&descSize=15&descColor=8b949e">
  </picture>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/samuel-pires-de-miranda-767255349/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:samuelpires727@gmail.com"><img alt="E-mail" src="https://img.shields.io/badge/E--mail-samuelpires727%40gmail.com-1f6feb?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <img alt="Aberto a vagas de Engenharia de Dados Júnior" src="https://img.shields.io/badge/Aberto%20a%20vagas-Eng.%20de%20Dados%20Jr.-238636?style=for-the-badge"/>
</p>

## Sobre mim

Engenheiro de dados júnior em transição de carreira, em Goiânia. Construo pipelines com **Python, SQL e Apache Airflow**, com atenção a qualidade de dado, idempotência e testes.
Graduando em **Sistemas de Informação** (UniALFA). Aberto a vagas remotas ou híbridas.

## Stack

| Área | Ferramentas |
|---|---|
| Linguagens e dados | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black) |
| Orquestração e infra | ![Apache Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) |
| Qualidade e testes | ![Pandera](https://img.shields.io/badge/Pandera-1f6feb?style=flat-square) ![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white) |
| APIs e apps | ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white) ![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white) ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white) |

## Projetos em destaque

### [Pipeline ETL de Energia com Apache Airflow](https://github.com/SamuelzinPires/airflow-etl-orchestration_ONS)
Pipeline orquestrado com **Airflow 3** sobre o balanço de energia do ONS: responde qual percentual da energia gerada no Brasil foi renovável, por dia e por subsistema. Validação com **Pandera**, carga **idempotente** em PostgreSQL (DELETE + INSERT por data, numa transação), retry testado com falha forçada, **backfill de ~280 dias** e testes com pytest rodando no **CI**.
`Airflow 3` `PostgreSQL` `Pandera` `Docker Compose` `pytest` `GitHub Actions`

### [Data Quality Engineering](https://github.com/SamuelzinPires/data-quality-engineering)
Qualidade de dados sobre **541 mil transações** reais (Online Retail): profiling com DuckDB e **6 regras** em Pandera (completude, faixa, formato e unicidade), com relatório de todas as violações encontradas.
`DuckDB` `Pandera` `Pandas`

### [CRUD API Data Application](https://github.com/SamuelzinPires/crud-api-data-app)
API REST com **FastAPI** e PostgreSQL (5 endpoints), validação com Pydantic, testes com pytest e interface em Streamlit. Carrega as 643 vagas coletadas pelo ETL Vagas Tech.
`FastAPI` `PostgreSQL` `SQLAlchemy` `Pydantic` `pytest` `Docker`

### [SQL Advanced Analytics — Northwind](https://github.com/SamuelzinPires/northwind-sql-analytics)
7 views de negócio em PostgreSQL com CTEs e Window Functions (LAG, NTILE, SUM OVER), em Docker.
`PostgreSQL` `CTEs` `Window Functions`

**Outros:** [Data Project Foundations](https://github.com/SamuelzinPires/data-project-foundations) (pytest + Poetry + CI) · [ETL Vagas Tech](https://github.com/SamuelzinPires/etl-vagas-tech) (API JSON paginada → SQLite) · [FinOps Pessoal](https://github.com/SamuelzinPires/finops-data-engineering) (ETL + Streamlit) · [Pipeline ELT AgroTech](https://github.com/SamuelzinPires/Projeto-agro-elt-pipeline-aws) (camadas bronze/prata/ouro em Parquet)

## Agora

- Próximo projeto (nov/2026): pipeline com a API do Mercado Livre e dbt.
- Montando meu **portfólio** (Astro). O link entra aqui quando a primeira versão estiver no ar.
