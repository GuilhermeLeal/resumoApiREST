# API REST e Restful

## O que é uma API?
Uma API (Interface de Programação de Aplicação) é um conjunto de regras que permite que diferentes programas se comuniquem entre si. Uma API REST é um tipo de API que segue os princípios da arquitetura Representational State Transfer (REST), que fornece uma maneira padrão para aplicativos da Web se comunicarem pela Internet usando o protocolo HTTP.

## DIferenças entre Rest e RESTful
A API REST (representational state transfer) é um modelo de arquitetura de software que define uma série de requisitos para que as APIs sejam desenvolvidas. É como um guia de boas práticas que conecta os usuários com as aplicações em nuvem. Já a API RESTful é a manipulação dos princípios da REST para o desenvolvimento de soluções ou serviços. Em outras palavras, a API RESTful é uma implementação mais completa e estrita dos princípios básicos da REST, como a interface uniforme, clientes sem estado e operações baseadas em recursos. 

## HTTP Verbs
Os métodos HTTP são os verbos que indicam a ação desejada a ser realizada no recurso identificado pela URI. Os principais métodos HTTP usados em APIs RESTful são:

* GET: usado para solicitar a representação de um recurso, sem alterá-lo.
* POST: usado para criar um novo recurso, ou realizar uma ação que não se encaixa nos outros métodos.
* PUT: usado para atualizar ou substituir um recurso existente.
* PATCH: usado para modificar parcialmente um recurso existente.
* DELETE: usado para remover um recurso existente.
* HEAD: usado para solicitar informações sobre um recurso, sem retornar o seu conteúdo.
* OPTIONS: usado para solicitar os métodos HTTP permitidos para um recurso.
  
## HTTP Status Code
Os códigos de status HTTP são números de três dígitos que indicam o resultado de uma requisição HTTP. Eles são divididos em cinco classes, de acordo com o primeiro dígito:

* 1xx: códigos de informação, que indicam que a requisição foi recebida e está sendo processada.
* 2xx: códigos de sucesso, que indicam que a requisição foi completada com êxito.
* 3xx: códigos de redirecionamento, que indicam que o cliente deve fazer uma nova requisição para outro recurso.
* 4xx: códigos de erro do cliente, que indicam que a requisição foi malformada ou não pode ser atendida.
* 5xx: códigos de erro do servidor, que indicam que o servidor encontrou um problema ao processar a requisição.

## Exemplos de códigos de status code HTTP: 
Alguns exemplos de códigos de status HTTP comuns são:

* 200 OK: indica que a requisição foi bem sucedida e o recurso solicitado foi retornado.
* 201 Created: indica que a requisição foi bem sucedida e um novo recurso foi criado.
* 301 Moved Permanently: indica que o recurso solicitado foi movido permanentemente para outra URI, e o cliente deve usar essa nova URI nas próximas requisições.
* 400 Bad Request: indica que a requisição foi malformada ou inválida, e não pode ser atendida pelo servidor.
* 401 Unauthorized: indica que a requisição requer autenticação, e o cliente não forneceu as credenciais necessárias.
* 403 Forbidden: indica que o servidor entendeu a requisição, mas se recusou a atendê-la por questões de autorização.
* 404 Not Found: indica que o recurso solicitado não foi encontrado no servidor.
* 500 Internal Server Error: indica que o servidor encontrou um erro interno ao processar a requisição, e não pode retornar uma resposta.
* 503 Service Unavailable: indica que o servidor está temporariamente indisponível, e não pode atender a requisição no momento.

-----------------------

Autor do resumo: Guilherme Leal - 01459560
