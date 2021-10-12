# projeto-final-pensamento-computacional
Este repositório contém os arquivos utilizados no projeto final da disciplina de Pensamento Computacional do Master em Jornalismo de Dados, Automação e Data Storytelling do Insper.

O projeto final foi um programa para pegar os links e datas dos Diários Oficiais do Estado do Tocantins e salvá-los em um arquivo ".csv".
Os dados foram raspados da seguinte url:https://diariooficial.to.gov.br/busca?por=edicao&edicao=

## Linguagem utilizada
Os códigos foram escritos em linguagem python.

Para atingir este resultado foram utilizadas as bibiliotecas "CSV", "Requests" e "LXML". Está última foi necessária para realizar as consusltas no html utilizando a linguagem XPATH, um tipo de linguagem específica para a realização deste tipo de consulta.

## Arquivos
Os arquivos que podem ser encontrados neste repositório são: o arquivo ".ipynb", notebook onde estão os códigos do programa e o arquivo ".csv" criado e que contém os dados extraídos do site do Diário Oficial do Tocantins.

### Arquivo ".csv"
O arquivo ".csv" possui duas colunas: a coluna "data" contendo as datas de publicação dos diários e a coluna "link" com os links para download dos diários.
