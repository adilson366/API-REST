# API-REST
Está é uma API REST com spring boot usando o maven como gerenciador de dependências.

Dependencias: spring web, H2 e JPA.

É uma API Rest bem simplificada que possui um User associado a um Department.

Oque pode ser feito com esta API Rest.

É possivel buscar por todos usuarios no banco de dados com o endpoint "/users" com o verbo http GET ou buscar um User especifico por ID com endpoint "/users/ID".
É possivel salvar um novo User com o verbo http POST e enviando o body da requisição, o ID não é para ser passado, pois ele é gerado automaticamente.
É possivel deletar um usuario com o verbo http DELETE pelo endpoint "/user/ID".

Para fazer as requisições foi usado o Postman.
