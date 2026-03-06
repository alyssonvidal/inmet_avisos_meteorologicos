[![status](https://img.shields.io/badge/status-dev-green)](https://img.shields.io/badge/status-dev-green) &nbsp;[![lang](https://img.shields.io/badge/language-python-blue)](https://img.shields.io/badge/language-python-blue)

# ETL INMET Avisos Meteorológicos

## Resumo

Este projeto tem como objetivo realizar a **extração, Este projeto tem como objetivo realizar a **extração, transformação e armazenamento (ETL)** dos **avisos meteorológicos emitidos pelo Instituto Nacional de Meteorologia (INMET)**, disponibilizados por meio de um **feed RSS no padrão CAP (Common Alerting Protocol)**.

Os dados coletados são processados em **Python**, estruturados e armazenados em banco de dados da **Secretaria da Saúde do Estado da Bahia (SESAB)**.

Além da carga de dados, o projeto também gera **relatórios automáticos em PDF contendo mapas e resumo dos alertas meteorológicos vigentes para o Estado da Bahia.**

Fonte dos dados:
**INMET – RSS de Avisos Meteorológicos**  
https://apiprevmet3.inmet.gov.br/avisos/rss


## Arquitetura Basica
- Parsing XML
- Filtragem por municípios da Bahia
- Estruturação dos campos
- Banco de Dados SESAB
- Mapas dos alertas
- Relatórios PDF

## Documentação
- [Common Alerting Protocol (CAP)](https://docs.oasis-open.org/emergency/cap/v1.2/CAP-v1.2.html)

## Desenvolvedores
- alysson.vidal@saude.ba.gov.br
- carlos.freitas@saude.ba.gov.br