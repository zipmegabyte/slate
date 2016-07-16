# Erros

A API do Roadtrack utiliza os seguintes códigos de erro:


Código | Significado
---------- | -------
400 | Bad Request -- Há algo errado com sua requisição
401 | Unauthorized -- Seu token de autenticação é inválido
403 | Forbidden -- A requisição é proibida para o nível de acesso do usuário
404 | Not Found -- O endpoint não foi encontrado
405 | Method Not Allowed -- Você tentou acessar o endpoint com um método inválido
406 | Not Acceptable -- Você requisitou um formato diferente de JSON
410 | Gone -- A entidade requisitada não existe mais
429 | Too Many Requests -- Você fez muitas requisições ao mesmo tempo.
500 | Internal Server Error -- Problemas no servidor. Tente novamente mais tarde.
503 | Service Unavailable -- Nós estamos temporariamente offline para manutenção. Tente novamente mais tarde.
