# Seleção Dev Java
Se você chegou ate aqui é porque se interessou em ser um softplayer. 
Como temos muitas oportunidades para você colocar a mão na massa, queremos ver como você se sai com o cenário abaixo, por meio do qual conseguiremos avaliar várias de suas competências.

## A demanda
Deverá ser criada uma aplicação de cadastro de pessoas:

###  1) Back-end
A aplicação, a ser desenvolvida em Java, deverá expor uma API de cadastro, alteração, remoção e consulta de pessoas com as seguintes informações: 
 - Nome - obrigatório
 - Sexo
 - E-mail - não obrigatório, deve ser validado caso preenchido
 - Data de Nascimento - obrigatório, deve ser validada
 - Naturalidade
 - Nacionalidade
 - CPF - obrigatório, deve ser validado (formato e não pode haver dois cadastros com mesmo cpf)

Obs: a data de cadastro e atualização dos dados devem ser armazenados.

### 2) Front-end
A aplicação deverá ser acessível via navegador e possuir uma tela com formulário.
Não há restrição em relação à tecnologia para o desenvolvimento do frontend.

### 3) Segurança
O acesso à aplicação só poderá ser realizado por um usuário pré-existente via autenticação **basic**.

### 4) Instalação
A aplicação deverá estar disponível em uma imagem docker a partir do **docker-hub** e não deve exigir configurações/parâmetros. Ou seja, ao rodar a imagem, deve levantar a aplicação e funcionar.

### 5) Código fonte
A aplicação deverá possuir um endpoint **/source** acessível sem autenticação via **HTTP GET** que deverá retornar o link do projeto no github com o código fonte do projeto desenvolvido.

## Extras
1) A aplicação rodando em algum ambiente em nuvem.
2) Teste de integração da API em linguagem de sua preferência (Damos importância para pirâmide de testes)
3) A API desenvolvida em REST, seguindo o modelo de maturidade de Richardson ou utilizando GraphQL.
4) A API deverá conter documentação executável que poderá ser utilizada durante seu desenvolvimento. (Utilizar swagger)
5) Integração com OAuth 2 Google (https://developers.google.com/identity/protocols/OAuth2)
6) Implementar Chat entre as pessoas que estão na aplicação
7) Versão 2 da API que deve incluir endereço da pessoa como dado obrigatório. Versão 1 deve continuar funcionando. 

## Prazo e retorno
Isso será combinado com quem você fez a entrevista. Você terá tempo para entender o cenário e nos retornar um prazo.
Lembre-se: Prazo dado é prazo cumprido.

Boa sorte!
