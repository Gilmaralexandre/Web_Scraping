# Introdução a Web Scrapy

     _Este projeto foi criado com conteudo do canal hashtag-programação video Introdução a Web Scraping com Python, 
     e serve como primeiro passo para o desenvolvimento em resquisições web, e raspagem de dados com Python.
     
     _Comandos realizados no terminal
     * conda create -n nome_ambiente python=3.6 - python 3.6 já instala o pip para posteriormente baixar o pip
     * conda activate nome_ambiente
     * pip install scrapy


_O projeto em si trata-se de uma raspagem de dados no site do imdb, o objetivo é listar os 250
melhores filmes do site, utilizando o framework Scrapy, que já retorna a aplicação com a função pré estabelecida. 

_No projeto é desenvolvido abordando temas como criação de ambiente virtual, utilizando o Anaconda Navigator, 
que possibilita ativar e configurar o projeto conforme desejado.

_Utilizei o Vscode para criar os codigos, e utilizei o shell do Scrapy para testar as resquisições web.
tags
_Os objetivos do projeto é testar se a resquisição feita pelo metodo get, retorna uma boa conexão(200), a partir daí,
é necessário olhar o codigo html e verificar o objeto desejado e a classe de cada um deles.
Comandos realizados no terminal

* scrapy startproject file file.py - Iniciando projeto
* scrapy genspider imdb imdb.py
* scrapy crawl imdb -o arquivo.json - Executando Framework e gerando arquivo json/csv
* Shell - ativando ambiente para testes

_Próximo passo é realizar testes, utilizei o selector gadget que identifica o objeto html.

_Depois de mapeado os objetivos, criei a estrutura com o yield como dicionario, em que as chaves é o cabeçalho do documento e 
os valores, são as tags que armazena o valor, tudo isso dentro de um loop de repetição.
