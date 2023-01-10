## Projeto iDEA App
### DESCRIÇÃO:
  O iDEA App se trata de uma TODO List, onde irá facilitar o gerênciamento de projetos e tarefas envolvidas nesses projetos.
  
### OBJETIVO: 
  Ajudar na organização de tarefas de um ou mais projetos e, até mesmo, para simplificar e listar tarefas diárias.
  
### ENTIDADES:

#### 01 - Projeto:
  - Nome;
  - Descrição;
  - Data de Criação;
  - Data de Atualização;

#### 02 - Tarefa:
  - Nome;
  - Descrição;
  - Status;
  - Observações;
  - Prazos;
  - Data de Criação;
  - Data de Atualização;

### REQUISITOS:

 - RF01: Permitir criar o Projeto;
 - RF02: Permitir alterar o Projeto;
 - RF03: Permitir deletar o Projeto;
 
 - RF04: Permitir criar a Tarefa;
 - RF05: Permitir alterar a Tarefa;
 - RF06: Permitir deletar a Tarefa;
 
### REGRAS DE NEGÓCIO:

- O sistema não irá conter um sistema de login;
	- Não haverá o conceito de usuário;
	- Toda tarefa deve pertencer a um projeto;
	- Deve ser possivel filtrar as tarefas por tag; 

### Técnologias utilizadas:

- Java;
- MySql;
 
