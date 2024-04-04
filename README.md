# pass.in

O pass.in é uma aplicação de **gestão de participantes em eventos presenciais**.

## Anotações

Métodos HTTP: GET, POST, PUT, DELETE, PATCH, OPTIONS, HEAD, ...

Corpo da requisição (Request Body): Dados para criação ou atualização de um registro
Parâmetros de busca (Search Params / Query Params): Filtros/busca e paginação '<http://localhost:3333/users?search=Diego&limit=5&page=2>'
Parâmetros de rota (Route Params): Identificar um recurso na rota 'DELETE <http://localhost:3333/users/1>'
Cabeçalho da requisição (Request Header): Informações sobre a requisição

20x => Sucesso
30x => Redirecionamento
40x => Erro do cliente (Erro em alguma informação enviada por QUEM está fazendo a chamada p/ API)
50x => Erro do servidor (Um erro que está acontecendo INDEPENDENTE do que está sendo enviado p/ o servidor)

JSON - JavaScript Object Notation
# NLW-Unite-Rocketseat
