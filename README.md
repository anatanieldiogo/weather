# Documentação do Aplicativo de Monitoramento Climático

Visão Geral

Nota: Tanto o aplicativo quanto a API ainda estão em construção e podem sofrer alterações durante o desenvolvimento.

O aplicativo de monitoramento climático é uma solução desenvolvida para meteorologistas e entusiastas do clima que desejam acompanhar e analisar condições climáticas em diferentes dias e locais. Utilizando a Weather API e Retrofit para consumo de dados, a aplicação permite a coleta, armazenamento e manipulação dessas informações para futuras análises.

## Tecnologias Utilizadas

Android Studio – Ambiente de desenvolvimento

Kotlin – Linguagem de programação

Retrofit – Biblioteca para consumo de APIs REST

Laravel – Backend para armazenamento dos dados coletados

Weather API – API externa utilizada para obter informações climáticas

## Funcionalidades

Consulta Climática

Permite pesquisar condições climáticas de diferentes localizações.

Exibe informações como temperatura, umidade, pressão atmosférica, velocidade do vento, entre outras.

Histórico de Pesquisas

Salva automaticamente as pesquisas feitas pelo usuário.

Permite revisitar dados anteriores.

## Favoritos

Usuário pode marcar determinadas localizações como favoritas para acesso rápido.

Integração com API Laravel

Os dados coletados podem ser armazenados no backend Laravel para análises futuras.

O backend permite a realização de CRUD (Criar, Ler, Atualizar e Excluir) das informações climáticas.


## API Laravel

A API Laravel permite o armazenamento e gerenciamento dos dados meteorológicos coletados pelo aplicativo. Os principais endpoints são:

GET /weather – Retorna todos os registros armazenados

POST /weather – Adiciona um novo registro

PUT /weather/{id} – Atualiza um registro existente

DELETE /weather/{id} – Remove um registro

## Considerações Finais

Este aplicativo oferece um sistema eficiente para monitoramento climático e análise de tendências meteorológicas, combinando a facilidade de uso com a robustez de uma API backend para armazenamento e manipulação de dados.

