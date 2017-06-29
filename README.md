# Locadora
## Projeto Web com aplicação Angular JS

Este projeto simula o cadastro de filmes que são adicionados dinamicamente em uma tabela através do angularJs. Além disso, foram implementados "filters", um recurso do framework que transforma o resultado de uma expressão, como por exemplo, a formatação de datas, ordenação de valores ou arrays, pesquisas inteligentes, entre outros. O angularJs permite a manipulação dos dados de forma simples facilitando e até mesmo enriquecendo o desenvolvimento.

![Home](https://github.com/Diego008/Locadora/blob/master/images/lista_filmes.jpg)

<sub>**Figura 1** - Lista de filmes</sub>

Devido a não existência de um parâmetro do angularJs para a paginação, foi utilizado uma biblioteca chamada dirPaginate e adicionada como referência ao angular.

angular.module("index", [<strong>'angularUtils.directives.dirPagination'</strong>]);
