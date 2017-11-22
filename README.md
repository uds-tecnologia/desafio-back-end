# Teste para candidatos à vaga de backend

> [![Logo UDS](https://raw.githubusercontent.com/uds-tecnologia/teste-programador-back-end/master/logo%20uds%20azul%20escuro.png)](https://www.uds.com.br)
>
> Esse teste é público. Candidatos para o teste devem implementar a aplicação solicitada e criar uma issue com um link para um repositório com a solução do mesmo.

## Objetivo do desafio
Criar uma aplicação web que implemente um CRUD de pessoa. Uma pessoa é um fornecedor ou cliente com as seguintes características:

### Fornecedor:
- Nome (Rafael, Carlos, Jeferson, ...)
- Sobrenome (Silva, Santos, Oliveria, ...)
- Sexo (Masculino, Feminino)
- Data de Nascimento (23/12/1990, ...)
- Email (email@servidor.com.br, ...)
- Empresa (Google, GitHub, ...)

### Cliente:
- Nome (Rafael, Carlos, Jeferson, ...)
- Sobrenome (Silva, Santos, Oliveria, ...)
- Sexo (Masculino, Feminino)
- Data de Nascimento (23/12/1990, ...)
- Email (email@servidor.com.br, ...)
- Senha (*****, ...)

### Endereços
- CEP
- Logradouro
- Número
- Complemento
- Referência
- Bairro
- Cidade
- UF

A aplicação é apenas um CRUD sem usuários (não existe autenticação). Deve ser possível:
- Listar, inserir, editar e deletar um fornecedor e um cliente;
- Associar n endereços aos mesmos;
- Pesquisar os clientes e fornecedores disponíveis com a possibilidade de filtrar por quaisquer características ou combinação de características disponíveis.

A interface de uso fica a critério do desenvolvedor. Será um grande diferencial se for desenvolvido em Angular 4, ou VueJS com o framework Vuetify.

## Requisitos:
- A aplicação deve comportar-se como uma REST FULL Api ou GraphQL. É um diferencial positivo se a aplicação for uma SPA (single-page application). Outro diferencial bastante positivo é o frontend ser desenvolvido em Angular 4 ou VueJS.
- Backend desenvolvido em qualquer linguagem dinâmica. É um diferencial positivo se for desenvolvido em PHP. É mais positivo ainda se utilizar o framework Laravel.
- Processo de desenvolvimento versionado via Git em algum repositório público, de preferência no github.
- Relatório de cobertura dos testes unitários de backend.
- Readme que explique como rodar o projeto, como gerar o relatório de cobertura e como executar quaisquer scripts necessários.
- A aplicação deve possuir um script que popula o banco inicialmente com algumas pessoas para demonstração.

## Critérios de avaliação:
- Modelagem do banco de dados. Você tem toda a liberdade de criar quantas tabelas ou campos achar necessários.
- Organização do código: desacoplamento e legibilidade contam.
- Automatização de tarefas.
- Flexibilidade do sistema para adição/remoção de funcionalidades.
- O front só será avaliado segundo o código Javascript. Não se preocupe com o HTML/CSS.

## Como vamos avaliar:
- Vamos subir a aplicação e acessar via localhost:<alguma-porta>. Vamos listar/cadastrar/editar/deletar algumas entidades. Vamos listar os veículos segundo diferentes combinações de filtros. Vamos analisar as chamadas da api feitas durante essa utilização.
- Vamos ler o código, e validar todos os conceitos de Clean Code, e Object Calisthenics.
- Vamos analisar os testes e o relatório de cobertura da aplicação.
- Vamos validar todas as classes de acordo com SOLID e KISS.

## O que nós gostamos:
- Hierarquia clara entre componentes.
- Arquitetura que favorece a escalabilidade do sistema.

## Diferenciais:
- Criar ambiente de desenvolvimento em Docker, utilizando compose.
- Testes claros e objetivos construidos sobre Baby Steps.
- Códigos escritos para compreeção de humanos.

