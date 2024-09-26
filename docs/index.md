
<h2><a href= "https://www.mackenzie.br">Universidade Presbiteriana Mackenzie</a></h2>
<h3><a href= "https://www.mackenzie.br/graduacao/sao-paulo-higienopolis/ciencia-da-computacao">Ciência da Computação</a></h3>


<font size="+12"><center>
*&lt;Nome do Projeto&gt;*
</center></font>

**Conteúdo**

- [Autores](#autores)
- [Descrição do Projeto](#descrição-do-projeto)
    - [Problema](#problema)
    - [Solução](#solução)
    - [Funcionalidades](#funcionalidades)
- [Análise de Requisitos Funcionais e Não-Funcionais](#análise-de-requisitos-funcionais-e-não-funcionais)
    - [Requisitos funcionais](#requisitos-funcionais)
    - [Requisitos não funcionais](#requisitos-não-funcionais)
- [Diagrama de Atividades](#diagrama-de-atividades)
- [Diagrama de Casos de Uso](#diagrama-de-casos-de-uso)
- [Descrição dos Casos de Uso](#descrição-dos-casos-de-uso)
- [Diagrama de Sequência](#diagrama-de-sequência)
- [Diagrama de Classes](#diagrama-de-classes)
- [Diagrama de Estados](#diagrama-de-estados)
- [Diagrama de Implantação](#diagrama-de-implantação)
- [Referências](#referências)


# Autores

* Marco Antonio de Camargo
* Natan Moreira Passos 
* Nícolas Henriques de Almeida



# Descrição do Projeto

O projeto \<nome do projeto> busca facilitar o processo de registro e controle de presenças dos alunos da Escola Infinito.


### Problema
A escola conta com cinco turmas, do 1º ao 5º ano do Ensino Fundamental I. Cada turma possui entre 20 e 30 alunos, um professor principal e alguns outros para matérias específicas. Atualmente, o controle de presenças é feito manualmente no papel, duas vezes por dia em todas as turmas, o que gera problemas como a demora para o registro, a recorrência de erros e a dificuldade de validar informações anteriores.

### Solução
Como solução ao problema, a equipe IneptaCatus terá o compromisso de planejar e desenvolver um sistema web para o registro e controle de faltas para Escola Infinito. O projeto visa sanar os problemas presentes no método atual e implementar ferramentas e funções com o intuito de torná-lo mais fácil de utilizar e mais eficiente.

### Funcionalidades
O sistema contará com recursos que buscam facilitar sua utilização, estes são:
- Sistema de registro de faltas que permitem aos professores registrarem as faltas de modo fácil e intuitivo.
- Geração de relatório de faltas para eventuais análises.
	- Agrupado por data, ano do ensino, turma, professor, disciplina ou aluno.
- Envio de notificações para pais ou responsáveis em caso de faltas excessivas (abaixo de 80% de presenças).
- Recursos de acessibilidade para garantir a inclusão para todos os usuários.
	- Fonte ajustável.
	- Regulagem de contraste.
- Website responsivo para garantir o acesso tanto em computadores quanto em dispositivos móveis.


# Análise de Requisitos Funcionais e Não-Funcionais
### Requisitos funcionais
- O sistema deve permitir que usuários (professor e administração) façam login com seus usernames e senhas.
- O sistema deve permitir que o usuário administração atribua turmas para um professor.
- O sistema deve permitir que o usuário professor registre presenças para os alunos de suas respectivas turmas.
- O sistema deve permitir que o usuário administração inclua e modifique dados no sistema de forma irrestrita.
- O sistema deve permitir que o usuário professor gere relatórios com a opção de serem agrupados por filtros de data, ano de ensino, turma, disciplina ou aluno.
- O sistema deve permitir que um professor envie notificações por email para os pais ou responsaveis em casos de faltas excessivas.
- O sistema deve ter recursos de acessibilidade para garantir a inclusão de todos os usuários.   

### Requisitos não funcionais
- O sistema deve ser capaz de ser atualizado por multiplas contas simultaneamente, considerando que existem aulas de salas diferentes que ocorrem ao mesmo tempo.
- O banco de dados deve ser grande o suficiente para integrar dados de todos os alunos, professores, e informações de aulas.
- Os dados pessoais dos usuarios deverão ser armazenados com criptografia.
- O tempo de resposta do sistema deve ser inferior a 3 segundos.
- O sistema deve seguir as normas da legislação LGPD.
- O sistema deve estar disponivel 99,9% do tempo.

# Diagrama de Atividades

*&lt;Diagrama para visualizer as pessoas das áreas de negócios e de desenvolvimento de uma organização para entender o processo e comportamento.&gt;*

# Diagrama de Casos de Uso
![Casos_de_uso_IneptaCatus drawio](https://github.com/user-attachments/assets/f7a3be75-3b8b-4ecd-963a-2ad6e662b6a9)

# Descrição dos Casos de Uso

| **Nome do caso de uso** | Fazer login |
| --- | --- |
| **Atores principais** | Professor, Administrador |
| **Atores secundários** | |
| **Resumo** | Este caso de uso descreve as etapas <br> percorridas por um usuário para fazer <br> login no sistema|
| **Pré-condições** | |
| **Pós-condições** | |
| **FLUXO PRINCIPAL** | |
| **Ações do ator** | **Ações do sistema** |
| 1. Usuário insere seu usuário e senha |  |
| | 2. Sistema verifica que o usuário e senha <br> inseridos correspondem a um usuário no <br> banco de dados|
| 3. Usuário recebe acesso ao sistema <br> utilizando sua conta | |
| **FLUXOS ALTERNATIVOS** | |
| | 2. Sistema verifica que o usuário e senha <br> inseridos não correspondem a um usuário <br> no banco de dados e redireciona o usuário <br> para a tela de login novamente |
| <br> | |
| **FLUXOS DE EXCEÇÃO** | |
| <br> | |
| <br> | |
| **Restrições e validações** | 1. É necessário ter uma conta cadastrada <br> no sistema |


# Diagrama de Sequência

*&lt;Diagrama de ordem e interação dos objetos&gt;*

# Diagrama de Classes

*&lt;Diagrama de relacionamento entre classes para os seus atributos e operações&gt;*

# Diagrama de Estados

*&lt;Diagrama para permite modelar o comportamento interno de um determinado objeto, subsistema ou sistema global&gt;*

# Diagrama de Implantação

*&lt;Diagrama para exibir o relacionamento de hardware e software no projeto&gt;*

# Referências

*&lt;Lista de referências&gt;*
