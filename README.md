# Teste Técnico para Backend

**Vaga**: Developer Backend (Júnior III a Pleno I)  
**Tecnologias**: PHP, Laravel, PostgreSQL ou Oracle, API, Jobs, Validações  
**Prazo para Entrega**: 3 dias

## Descrição do Projeto

Desenvolver uma API RESTful com Laravel para um sistema de gerenciamento de livros e usuários. O sistema deve permitir que os usuários se cadastrem, façam login e gerenciem seus livros, além de marcar livros como favoritos.

## Requisitos

1. **Cadastro de Usuário**
   - O usuário deve fornecer: nome, e-mail (único) e senha (deve ser armazenada de forma segura - hash).

2. **Login de Usuário**
   - O usuário deve conseguir logar com e-mail e senha.
   - Um token JWT deve ser gerado e retornado ao usuário autenticado.

3. **CRUD de Livros**
   - Criar, ler, atualizar e deletar livros.
   - Cada livro deve pertencer a um usuário.

4. **Relacionamento de Favoritos**
   - Um usuário pode adicionar livros aos seus favoritos.
   - Um livro pode ser favorito de vários usuários.
   - Criar uma maneira de gerenciar o relacionamento entre usuários e livros.

5. **Validações**
   - O sistema deve validar dados de entrada (ex: campos não vazios, formato de e-mail válido).

6. **Jobs (Opcional)**
   - Após a criação de um livro, uma tarefa em segundo plano (job) deve ser enviada para processar uma ação (ex: envio de um e-mail de confirmação ou registro em log).

7. **Descrição de testes**
    - Importante conter uma descrição de como testar a aplicação.

## Documentação

O candidato deve incluir uma documentação clara e concisa, incluindo:

1. **README.md**:
   - Descrição do projeto e sua finalidade.
   - Instruções para instalação e execução.
   - Informações sobre configuração do banco de dados.
   - Exemplos de requisições HTTP e payloads utilizados nas rotas.
   - Descrição das rotas disponíveis e exemplos de resposta.

2. **Documentação da API**:
   - Utilizar ferramentas como Swagger ou Postman para gerar uma documentação interativa da API com informações de métodos HTTP, parâmetros de entrada e estrutura de resposta.

3. **Comentários no Código**:
   - Código comentado para explicar a lógica e pontos importantes.

## Requisitos Obrigatórios

O candidato deve seguir as diretrizes abaixo para garantir a qualidade do código:

- **Nomeclaturas**:
  - Nomeclatura clara e padrão para classes, métodos e rotas (ex: usar o padrão RESTful para rotas).

- **Organização de Diretórios**:
  - Manter uma estrutura de diretórios organizada, seguindo as convenções do Laravel.

- **Uso de Services e Repositories**:
  - Implementar a lógica de negócio em serviços e a comunicação com o banco de dados em repositórios, seguindo o padrão de arquitetura.

- **Commits**:
  - Realizar commits frequentes com mensagens claras e descritivas, que expliquem as mudanças realizadas.

## Critérios de Avaliação

- Funcionalidade: Todas as funcionalidades funcionando conforme o solicitado.
- Código Limpo e Organizado: Adequação às boas práticas de programação.
- Documentação: Clareza e concisão das instruções e rotas.
- Validações e Tratamento de Erros: Lidar adequadamente com entradas inválidas.
- Uso de Jobs: Implementação eficiente e clara, se utilizado.
