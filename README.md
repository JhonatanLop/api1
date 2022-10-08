# API 1º Semestre - Tecnologia em Banco de Dados 2022
##
## Sumário
  * [Projeto API](#projeto-API)
    * [Integrantes da Equipe Khali](#integrantes-da-equipe-khali) 
    * [Objetivo](#objetivo)
    * [Tríade da API](#tríade-da-api)
    * [Prazos](#prazos)
   
  
     
  * [Produto Khali](#descrição-do-produto)
    * [Tema](#tema)
    * [Tecnologias Utilizadas](#tecnologias-utilizadas)
    * [Wireframe do Produto](#wireframe-do-produto)
    * [Fluxograma do produto](#fluxograma-do-produto)
    * [Requisitos Funcionais](#requisitos-funcionais)
    * [Requisitos Não Funcionais](#requisitos-não-funcionais)
    * [Backlog do Produto](#backlog-do-produto)
      * [Backlog da Sprint 1](#backlog-detalhado-da-sprint-1)
    
    
##
## *Projeto API*

### Integrantes da Equipe Khali
* Danielle Tiemi Iwamoto [GitHub](https://github.com/daniiwamoto)
* Jhonatan Oliveira Lopes [GitHub](https://github.com/JhonatanLop)
* Marcos Vinicius Malaquias [GitHub](https://github.com/Incivius)
* Naira Giulia Pereira Maximo dos Santos [GitHub](http://github.com/naira-maximo)
* Paulo Granthon [GitHub](https://github.com/paulo-granthon)
* Tânia de Oliveira Cruz [GitHub](https://github.com/taniacruzz)

### Objetivo
* Atender à necessidade da instituição fictícia e desenvolver uma solução computacional que exercite a capacidade de pesquisa e autodidaxia dos integrantes dos grupos, no que tange:
* A aplicação de técnicas de programação para a construção de algoritmos
* O uso de uma ferramenta que possibilite um Ambiente de Desenvolvimento Integrado (IDE) para o desenvolvimento da solução computacional
* O aprendizado e aplicação de uma ou mais linguagens de programação para concepção do projeto
* O exercício do compromisso, responsabilidade e trabalho em equipe dos membros do Time

### Tríade da API
* Algoritmos - *Prof. Lucas Gonçalves Nadalete*
* Laboratório de Desenvolvimento em Banco de Dados - *Prof. Lucas Gonçalves Nadalete*
* Arquitetura e Organização de Computadores - *Prof. Fabiano Sabha Walczak*

### Prazos
> - [x] 09/08 a 13/08 - *Dinamica Disruptiva*
> - [x] 15/08 a 19/08 - *Kick-off*
> - [x] 29/08 a 18/09 - *Primeira Sprint*
> - [ ] 19/09 a 09/10 - *Segunda Sprint*
> - [ ] 09/10 a 15/10 - *Recesso Escolar*
> - [ ] 17/10 a 06/11 - *Terceira Sprint*
> - [ ] 07/11 a 27/11 - *Quarta Sprint*
> - [ ] 08/12 - *Feira de Soluções e Apresentação Final API*


##
## *Produto*

### Tema 
* Desenvolvimento de uma solução computacional que viabilize a aplicação da técnica de **Avaliação 360°** e a análise dos dados obtidos pelos alunos e instrutores da instituição de ensino PBLTeX, especializada em cursos e práticas de ensino aplicando PBL (*Problem Based Learning*)

### Tecnologias Utilizadas
* Linguagens: Python e HTML
* Base de Dados: CSV
* Plataformas: Figma, Asana, Youtube, Google drive e documento google. 

### Wireframe do Produto
* Wireframe disponível pelo [Figma](https://www.figma.com/file/U1apWrrVuZHbtNIumUgUoo/Api?node-id=56%3A3)

### Fluxograma do Produto
* Fluxograma disponível pelo [Figma](https://www.figma.com/file/Zbj4rKK3oPqUJxCyPc2eLo/Fluxograma-Khali?node-id=0%3A1)

### Requisitos Funcionais
* Possibilitar autoavaliação e avaliação dos demais integrantes do Time de forma individualizada;
* Possibilitar que o Líder do Grupo avalie o Líder Técnico do Time e o *Fake Client* avalie o aluno PO do Time;
* Prover um ou mais Dashboards de acompanhamento.

### Requisitos Não Funcionais
* Linguagem de programação Python;
* Uso de base de dados simples, como Text, CSV e ZODB;
* Uso de sistema de controle de versão de código (Git)
* Documentações


## Backlog do Produto

<details>
 <summary> SPRINT 1- CRIAÇÃO DO SISTEMA DE CADASTRO DO USUÁRIO E AUTENTICAÇÃO </summary>
 <br>
 
  | USER STORY | PRIORIDADE |
  |------------|------------|
  | Como Administrador da instituição, preciso cadastrar os Líderes dos Grupos para que façam login |Essencial|
  | Como Administrador da instituição, preciso cadastrar os Fake Clients para que façam login |Essencial|
  | Como Líder do Grupo, preciso criar Times para realizar o cadastro de usuários |Essencial|
  | Como Líder do Grupo, preciso cadastrar usuários dentro de um Time para que façam login |Essencial
  | Como Líder do Grupo, preciso definir a função dos usuário dentro de um Time, que será utilizada como base para suas respectivas permissões |Essencial|
  | Como Líder do Grupo, preciso criar um cronograma de Sprints dentro do meu grupo, que será a base para os prazos das avaliações |Essencial|
  | Como Líder do Grupo, terei a funcionalidade de desativar usuários e times para possíveis desligamentos ou finalização do projeto |Desejável|
 
</details>

<details>
<summary>SPRINT 2 - CRIAÇÃO DO SISTEMA DE AVALIAÇÃO</summary>
 
 
  | USER STORY | PRIORIDADE |
  |------------|------------|
  | Como Líder do Grupo, avaliarei os Líderes Técnicos do meu grupo conforme requisito funcional | Essencial |
  | Como Fake Client, avaliarei os POs do meu grupo conforme requisito funcional | Essencial |
  | Como PO, avaliarei o Líder Técnico, estudantes do meu time e a mim mesmo como requisito funcional | Essencial|
  | Como estudante avaliarei todos os outros itegrantes do meu time,e a mim mesmo como requisito funcional | Essencial |

 </details>

<details>
<summary>SPRINT 3 - CRIAÇÃO DO SISTEMA DE DASHBOARD </summary>

 
  | USER STORY | PRIORIDADE |
  |------------|------------|
  | Como estudante terei acesso a um dashboard dos meus resultados individuais nas avaliações para que eu possa acompanhar e analisar o meu desempenho | Importante|
	 | Como PO terei acesso a um dashboard com resultado do meu time nas avaliações para que eu possa acompanhar e analisar o desempenho do meu time | Importante |
	 | Como Líder técnico terei acesso a um dashboard com resultado do meu time nas avaliações para que eu possa acompanhar e analisar o desempenho do meu time | Importante | <br/>
	
 </details>
 
<details>
<summary>SPRINT 4 - "NÃO VALIDADO AINDA" </summary>
 
  | USER STORY | PRIORIDADE |
  |------------|------------|
  | Como PO, terei acesso ao meu Dashboard individual e os Dashboards do meu time, para acompanhamento de desempenho |Importante|
  | Como Líder Técnico, terei acesso ao meu Dashboard individual e aos Dashboards do meu time, para acompanhamento de desempenho |Importante|
  | Como estudante, terei acesso ao meu Dashboard individual e ao Dashboard geral do time, para acompanhar o meu desempenho |Importante|

 </details>



### Backlog detalhado da Sprint 1
#### *Criação do sistema de usuário*
* Criação do usuario *Administrador*
* Sistema de cadastramento de grupos e usuários (Líder do Grupo e Fake Client) por parte do *Administrador* 
* Sistema de cadastramento e configuração de Sprints pelo *Líder do Grupo*
* Sistema de cadastramento e configuração de Times pelo *Líder do Grupo*
* Sistema de cadastramento de usuários pelo *Líder do Grupo*
* Criação da funcionalidade de Login
* Retorno para os usuários das Sprints e usuários que ele deve avaliar

*Documento com a descrição completa dos Épicos, storys e tarefas da [1ª srint](https://docs.google.com/document/d/e/2PACX-1vQ7dtt7AMiOUWYHD1UkAYsZ2ibkR9KMMcrm4DGZL1xgrUUiRh0o9ROnhx6awl8EsjuklAxMRILXGxCi/pub)*

*Fluxograma do sistema de cadastramento disponível pelo [Drive](https://drive.google.com/file/d/11j_OIrMpIdoHqzDNnrGinr8TQ7IvanjP/view?usp=sharing)*
