## Sobre o sistema
O sistema deve ser pensado para gerenciar os funcionários de uma empresa pequena. 
Deve permitir cadastrar, buscar, atualizar e deletar um funcionário, tudo utilizando padrão REST.
Todas as APIs devem receber e responder no formato JSON. 

## 1ª Etapa
Criar um projeto java utilizando Spring Boot.
Adicionar dependência do Spring Data, recomendado usar o H2 para esse desafio.
O projeto deve conter uma separação de três camadas.

## 2ª Etapa
Modelar o funcionário, ele deve conter os seguintes atributos: 

- id
- nome
- idade
- cep
- endereço
- bairro
- cidade
- estado

## 3ª Etapa
Criar os seguintes endpoints.

- POST - cadastrar um usuário
- GET - Buscar um usuário específico pelo id dele
- GET - Buscar todos os usuários cadastrados
- GET - Buscar todos os usuários que tenham o cpf informado no parâmetro de busca
- PUT - Atualizar a entidade funcionário 
- DELETE - Excluir funcionário

Extras:
1. Criar uma API utilizando o método PATCH para atualizar apenas os atributos informados do funcionário.
