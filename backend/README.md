## Test Técnico -- Backend Mercafácil

Fluxo de Ações

- A API receberá um JSON via POST contendo o nome e celular;
- O cliente deverá estar autenticado para inserir o contato na base
- O contato deverá ser inserido no banco de dados do cliente seguindo as regras
  de cada cliente

Especificações da API:

- A autenticação será através de um token JWT no Authorization Header
- Cada cliente tem 1 uma chave única
- A lista de contatos que será inserido em cada cliente está no arquivo
  contato.json

[] Deve ser possível Adicionar clientes
[] Deve ser possível Autenticar em um cliente especifico utilizando JWT
[] Deve ser possível Adicionar um ou mais contatos via JSON à um Cliente
[] Deve ser criado dois Clientes Macapá, VareJão;

- Especificações do Cliente Macapá:

  - Banco de dados Mysql
  - Formato do Nome é somente maiúsculas
  - O formato de telefone segue o padrão +55 (41) 93030-6905
  - Em anexo está o sql de criação da tabela

- Especificações do Cliente VareJão:
  - Banco de dados Postgresql
  - Formato do Nome é livre
  - O formato de telefone segue o padrão 554130306905
  - Em anexo está o sql de criação da tabela
