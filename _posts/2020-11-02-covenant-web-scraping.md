---
layout: post
title: "Identifying tables and text blocks"
date: 2020-11-02
excerpt: "(pt-br) Web scraping of HTML text and tables in government covenants"
tags: [business, web-scraping, nlp]
comments: true
---

# [Identificar blocos de texto específicos em Convênios ICMS](https://github.com/pedroafleite/convenios)

[Ver em Github](https://github.com/pedroafleite/convenios)

## Objetivos
1. Fazer um scrapping de todos os convênios do ano 2019. ([Link](https://www.confaz.fazenda.gov.br/legislacao/convenios/2019))
2. De cada convênio, extrair os itens coloridos em vermelho e verde.
3. Exportar itens de cada convênio em arquivos txt diferentes.

### Resultados
Objetivos alcançados, exceto pelos termos em verde, que não foram encontrados nos documentos.

#### Códigos
[Python](https://github.com/pedroafleite/convenios/blob/main/convenios.py) 

[Jupyter Notebook](https://github.com/pedroafleite/convenios/blob/main/convenios.ipynb)

## Exploração de dados e sub-problemas solucionados
Encontrar textos nos documentos em que vermelho e verde são adjetivos de algum termo específico.
  - Requer NLP básico.

### Resultados 
As palavras vermelho e verde não foram citadas nos documentos dos Convênios ICMS de 2019.

[Documento .txt](https://github.com/pedroafleite/convenios/blob/main/output.txt) que dispõe:
1. o texto contendo as palavras buscadas, e 
2. qual documento em que o texto foi encontrado.
