Trinity - Teste para desenvolvimento frontend
======================

## Proposta

Implementar uma aplicação client-side, que consulte a API. Esta aplicação deve funcionar nos navegadores mais recentes do mercado.

## API

Implementar uma aplicação server-side, que atenda os seguintes requisitos:

- Implementação de um CRUD de criacao de usuários
- Utilização de uma Ferramenta de Validação de dados (YUP)
- Utilização de um ORM para conexão com um banco de dados relacional (MySql, Postgres)
- Implementação de Criptografia Hash no cadastro de usuario
- Integracão com um servico de cep
- Autenticacao JWT

## Endpoints

- Listagem de um usuário
- Detalhes de um usuário
- Atualização de um usuário
- Autenticação JWT

## Navegação
- Ao buscar um usuário pelo email e senha,devo autenticar o usuário e direcionar para pagina de Detalhes do usuário.
- Se o usuário for encontrado apresentar pagina de detalhes do usuário, caso contrario exibir mensagem amigável Notfound

## Requisitos
- Eu, como usuário, desejo buscar por um usuário por email e senha;
- Eu, como usuário, desejo ver os detalhes desse usuário que foi buscado (Nome, Email, Endereco, Telefone);
- Eu, como usuário, posso atualizar as informacoes desse usuario;
- Eu, como usuário, posso cadastrar um novo usuário(Nome, Email, Endereco, Telefone) 


## Definição de pronto
- Não é obrigatório o uso de um framework, mas recomendamos React.js ou Angular.
- É obrigatório o uso de rotas.

## Critérios de avaliação
- Organização do projeto: Avalia a estrutura do projeto, documentação e uso de controle de versão;
- Inovação tecnológica: Avalia o uso de tecnologias mais recentes, desde que estáveis;
- Coerência: Avalia se os requisitos foram atendidos;
- Boas práticas: Avalia se o projeto segue boas práticas de desenvolvimento, incluindo segurança e otimização;
- Controle de Qualidade: Avalia se o projeto possui qualidade assegurada por testes automatizados (por exemplo Jest).

## Submissão
- O desafio deve ser entregue pelo GitHub. A aplicação deve estar hospedada (Heroku, Netlify, Firebase ou Plunker) As URLs deve ser enviada por email.
- O desafio deve ter um README.md com contendo o tutorial de instalação.

## Prazo
- O prazo de entrega é de 3 dias
 
Boa Sorte!
