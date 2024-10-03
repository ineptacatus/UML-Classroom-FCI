


<h2><a href= "https://www.mackenzie.br">Universidade Presbiteriana Mackenzie</a></h2>
<h3><a href= "https://www.mackenzie.br/graduacao/sao-paulo-higienopolis/ciencia-da-computacao">Ciência da Computação</a></h3>


<font size="+12"><center>
*&lt;Sistema de presenças Escola INFINITO&gt;*
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

O projeto Sistema de presenças Escola INFINITO busca facilitar o processo de registro e controle de presenças dos alunos da Escola Infinito.


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
- O sistema deve permitir que um professor envie notificações por email para os pais ou responsáveis em casos de faltas excessivas.
- O sistema deve ter recursos de acessibilidade para garantir a inclusão de todos os usuários.   

### Requisitos não funcionais
- O sistema deve ser capaz de ser atualizado por múltiplas contas simultaneamente, considerando que existem aulas de salas diferentes que ocorrem ao mesmo tempo.
- O banco de dados deve ser grande o suficiente para integrar dados de todos os alunos, professores, e informações de aulas.
- Os dados pessoais dos usuários deverão ser armazenados com criptografia.
- O tempo de resposta do sistema deve ser inferior a 3 segundos.
- O sistema deve seguir as normas da legislação LGPD.
- O sistema deve estar disponível 99,9% do tempo.

# Diagrama de Atividades

*&lt;Diagrama para visualizer as pessoas das áreas de negócios e de desenvolvimento de uma organização para entender o processo e comportamento.&gt;*

# Diagrama de Casos de Uso
![Casos_de_uso_IneptaCatus drawio](https://github.com/user-attachments/assets/f7a3be75-3b8b-4ecd-963a-2ad6e662b6a9)

# Descrição dos Casos de Uso

### Caso de uso #1 - Fazer login
<table>
    <tr>
        <th>Nome do caso de uso</th>
        <th>Fazer Login</th>
    </tr>
    <tr>
        <th>Atores principais</th>
        <td>Professor, Administrador</td>
    </tr>
    <tr>
        <th>Resumo</th>
        <td>Este caso de uso descreve as etapas percorridas por um usuário para efetuar login no sistema</td>
    </tr>
    <tr>
        <th>Pré-condições</th>
        <td>Ter uma conta cadastrada no sistema</td>
    </tr>
    <tr>
        <th>Pós-condições</th>
        <td></td>
    </tr>
    <tr>
        <th colspan="2">FLUXO PRINCIPAL</th>
    </tr>
    <tr>
        <th>Ações do Ator</th>
        <th>Ações do Sistema</th>
    </tr>
    <tr>
        <td>1. Usuário insere seu usuário e senha</td>
        <td></td>
    </tr>
    <tr>
        <td></td>
        <td>2. Sistema verifica que o usuário e senha inseridos correspondem a um usuário no banco de dados</td>
    </tr>
    <tr>
        <td>3. Usuário recebe acesso ao sistema utilizando sua conta</td>
        <td></td>
    </tr>
    <tr>
        <th colspan="2">FLUXOS ALTERNATIVOS</th>
    </tr>
    <tr>
        <td><br></td>
        <td></td>
    </tr>
    <tr>
        <td><br></td>
        <td></td>
    </tr>
    <tr>
        <th colspan="2">FLUXOS DE EXCEÇÃO</th>
    </tr>
    <tr>
        <td></td>
        <td>2. Sistema verifica que o usuário e senha inseridos não correspondem a um usuário no banco de dados e redireciona o usuário para a tela de login novamente</td>
    </tr>
    <tr>
        <td><br></td>
        <td></td>
    </tr>
    <tr>
        <th>Restrições e validações</th>
        <td>1. É necessário ter uma conta cadastrada no sistema</td>
    </tr>
</table>

### Caso de uso #2 - Atribuir turmas

<table>
    <tr>
        <th>Nome do caso de uso</th>
        <th>Atribuir Turmas</th>
    </tr>
    <tr>
        <th>Atores principais</th>
        <td>Professor, Administrador</td>
    </tr>
    <tr>
        <th>Resumo</th>
        <td>Este caso de uso descreve as etapas percorridas por um usuário para atribuir turmas no sistema</td>
    </tr>
    <tr>
        <th>Pré-condições</th>
        <td>Efetuar login no sistema</td>
    </tr>
    <tr>
        <th>Pós-condições</th>
        <td></td>
    </tr>
    <tr>
        <th colspan="2">FLUXO PRINCIPAL</th>
    </tr>
    <tr>
        <th>Ações do Ator</th>
        <th>Ações do Sistema</th>
    </tr>
    <tr>
        <td>1. Usuário insere a turma e seus alunos</td>
        <td></td>
    </tr>
    <tr>
        <td></td>
        <td>2. Sistema verifica que a turma e alunos inseridos não correspondem a outras turmas e alunos no banco de dados</td>
    </tr>
    <tr>
        <td>3. Usuário cria a turma com sucesso</td>
        <td></td>
    </tr>
    <tr>
        <th colspan="2">FLUXOS ALTERNATIVOS</th>
    </tr>
    <tr>
        <td><br></td>
        <td></td>
    </tr>
    <tr>
        <td><br></td>
        <td></td>
    </tr>
    <tr>
        <th colspan="2">FLUXOS DE EXCEÇÃO</th>
    </tr>
    <tr>
        <td></td>
        <td>2. Sistema verifica que a turma e alunos inseridos correspondem a uma turma e alunos no banco de dados e redireciona o usuário para a tela de atribuição novamente, indicando os elementos conflitantes</td>
    </tr>
    <tr>
        <td><br></td>
        <td></td>
    </tr>
    <tr>
        <th>Restrições e validações</th>
        <td></td>
    </tr>
</table>

### Caso de uso #3 - Gerar relatórios

<table>
    <tr>
        <th>Nome do caso de uso</th>
        <th>Gerar relatórios</th>
    </tr>
    <tr>
        <th>Atores principais</th>
        <td>Professor, Administrador</td>
    </tr>
    <tr>
        <th>Resumo</th>
        <td>Este caso de uso descreve as etapas percorridas por um usuário para gerar relatórios de faltas</td>
    </tr>
    <tr>
        <th>Pré-condições</th>
        <td>Efetuar login no sistema</td>
    </tr>
    <tr>
        <th>Pós-condições</th>
        <td></td>
    </tr>
    <tr>
        <th colspan="2">FLUXO PRINCIPAL</th>
    </tr>
    <tr>
        <th>Ações do Ator</th>
        <th>Ações do Sistema</th>
    </tr>
    <tr>
        <td>1. Usuário define os elementos que deseja informações sobre, podendo filtrar por turma, aluno ou todos</td>
        <td></td>
    </tr>
    <tr>
        <td></td>
        <td>2. Sistema verifica que o elemento desejado existe no banco de dados</td>
    </tr>
    <tr>
        <td></td>
        <td>3. Sistema gera o relatório com sucesso</td>
    </tr>
    <tr>
        <th colspan="2">FLUXOS ALTERNATIVOS</th>
    </tr>
    <tr>
        <td><br></td>
        <td></td>
    </tr>
    <tr>
        <td><br></td>
        <td></td>
    </tr>
    <tr>
        <th colspan="2">FLUXOS DE EXCEÇÃO</th>
    </tr>
    <tr>
        <td><br></td>
        <td></td>
    </tr>
    <tr>
        <td><br></td>
        <td></td>
    </tr>
    <tr>
        <th>Restrições e validações</th>
        <td></td>
    </tr>
</table>

### Caso de uso #4 - Gerar PDF

<table>
    <tr>
        <th>Nome do caso de uso</th>
        <th>Gerar PDF</th>
    </tr>
    <tr>
        <th>Atores principais</th>
        <td>Professor</td>
    </tr>
    <tr>
        <th>Resumo</th>
        <td>Este caso de uso descreve as etapas percorridas por um usuário para gerar arquivos PDF a partir de relatórios de falta</td>
    </tr>
    <tr>
        <th>Pré-condições</th>
        <td>Gerar relatório</td>
    </tr>
    <tr>
        <th>Pós-condições</th>
        <td></td>
    </tr>
    <tr>
        <th colspan="2">FLUXO PRINCIPAL</th>
    </tr>
    <tr>
        <th>Ações do Ator</th>
        <th>Ações do Sistema</th>
    </tr>
    <tr>
        <td>1. Usuário indica que deseja gerar um arquivo PDF do relatório</td>
        <td></td>
    </tr>
    <tr>
        <td></td>
        <td>2. Sistema verifica que o relatório foi gerado</td>
    </tr>
    <tr>
        <td></td>
        <td>3. Sistema gera o arquivo PDF com sucesso</td>
    </tr>
    <tr>
        <th colspan="2">FLUXOS ALTERNATIVOS</th>
    </tr>
    <tr>
        <td><br></td>
        <td></td>
    </tr>
    <tr>
        <td><br></td>
        <td></td>
    </tr>
    <tr>
        <th colspan="2">FLUXOS DE EXCEÇÃO</th>
    </tr>
    <tr>
        <td><br></td>
        <td></td>
    </tr>
    <tr>
        <td><br></td>
        <td></td>
    </tr>
    <tr>
        <th>Restrições e validações</th>
        <td></td>
    </tr>
</table>

### Caso de uso #5 - Acessar turma

<table>
    <tr>
        <th>Nome do caso de uso</th>
        <th>Acessar turma</th>
    </tr>
    <tr>
        <th>Atores principais</th>
        <td>Professor, Administrador</td>
    </tr>
    <tr>
        <th>Resumo</th>
        <td>Este caso de uso descreve as etapas percorridas por um usuário para acessar uma turma</td>
    </tr>
    <tr>
        <th>Pré-condições</th>
        <td>Efetuar login no sistema</td>
    </tr>
    <tr>
        <th>Pós-condições</th>
        <td></td>
    </tr>
    <tr>
        <th colspan="2">FLUXO PRINCIPAL</th>
    </tr>
    <tr>
        <th>Ações do Ator</th>
        <th>Ações do Sistema</th>
    </tr>
    <tr>
        <td>1. Usuário indica a turma que deseja acessar</td>
        <td></td>
    </tr>
    <tr>
        <td></td>
        <td>2. Sistema verifica que a turma existe e o usuário tem permissão para acessá-la</td>
    </tr>
    <tr>
        <td>3. Usuário é concedido acesso à turma</td>
        <td></td>
    </tr>
    <tr>
        <th colspan="2">FLUXOS ALTERNATIVOS</th>
    </tr>
    <tr>
        <td><br></td>
        <td></td>
    </tr>
    <tr>
        <td><br></td>
        <td></td>
    </tr>
    <tr>
        <th colspan="2">FLUXOS DE EXCEÇÃO</th>
    </tr>
    <tr>
        <td></td>
        <td>2. Sistema verifica que a turma inserida não corresponde a uma turmano banco de dados e redireciona o usuário para a tela de acessar turma novamente</td>
    </tr>
    <tr>
        <td><br></td>
        <td></td>
    </tr>
    <tr>
        <th>Restrições e validações</th>
        <td></td>
    </tr>
</table>

### Caso de uso #6 - Registrar presenças

<table>
    <tr>
        <th>Nome do caso de uso</th>
        <th>Registrar presenças</th>
    </tr>
    <tr>
        <th>Atores principais</th>
        <td>Professor</td>
    </tr>
    <tr>
        <th>Resumo</th>
        <td>Este caso de uso descreve as etapas percorridas por um usuário para registrar presenças para os alunos de uma turma</td>
    </tr>
    <tr>
        <th>Pré-condições</th>
        <td>Acessar turma</td>
    </tr>
    <tr>
        <th>Pós-condições</th>
        <td></td>
    </tr>
    <tr>
        <th colspan="2">FLUXO PRINCIPAL</th>
    </tr>
    <tr>
        <th>Ações do Ator</th>
        <th>Ações do Sistema</th>
    </tr>
    <tr>
        <td>1. Usuário indica os alunos da turma presentes</td>
        <td></td>
    </tr>
    <tr>
        <td></td>
        <td>2. Sistema recebe as informações </td>
    </tr>
    <tr>
        <td>3. Usuário confirma os alunos que receberão falta</td>
        <td></td>
    </tr>
    <tr>
        <th colspan="2">FLUXOS ALTERNATIVOS</th>
    </tr>
    <tr>
        <td><br></td>
        <td></td>
    </tr>
    <tr>
        <td><br></td>
        <td></td>
    </tr>
    <tr>
        <th colspan="2">FLUXOS DE EXCEÇÃO</th>
    </tr>
    <tr>
        <td>3. Usuário não confirma os alunos que receberão falta e o sistema redireciona para a tela de atribuição de presença novamente</td>
        <td></td>
    </tr>
    <tr>
        <td><br></td>
        <td></td>
    </tr>
    <tr>
        <th>Restrições e validações</th>
        <td></td>
    </tr>
</table>

### Caso de uso #7 - Enviar notificação por e-mail

<table>
    <tr>
        <th>Nome do caso de uso</th>
        <th>Enviar notificação por e-mail</th>
    </tr>
    <tr>
        <th>Atores principais</th>
        <td>Professor, Pais</td>
    </tr>
    <tr>
        <th>Resumo</th>
        <td>Este caso de uso descreve as etapas percorridas por um usuário para enviar um e-mail relacionado às faltas de um aluno para seus pais</td>
    </tr>
    <tr>
        <th>Pré-condições</th>
        <td>Registrar presenças, aluno ter menos de 80% de presença</td>
    </tr>
    <tr>
        <th>Pós-condições</th>
        <td></td>
    </tr>
    <tr>
        <th colspan="2">FLUXO PRINCIPAL</th>
    </tr>
    <tr>
        <th>Ações do Ator</th>
        <th>Ações do Sistema</th>
    </tr>
    <tr>
        <td>1. Usuário indica o aluno que terá os pais notificados</td>
        <td></td>
    </tr>
    <tr>
        <td></td>
        <td>2. Sistema envia um e-mail padronizado para os pais atribuidos ao aluno</td>
    </tr>
    <tr>
        <td>3. Usuário recebe confirmação do envio do e-mail</td>
        <td></td>
    </tr>
    <tr>
        <th colspan="2">FLUXOS ALTERNATIVOS</th>
    </tr>
    <tr>
        <td><br></td>
        <td></td>
    </tr>
    <tr>
        <td><br></td>
        <td></td>
    </tr>
    <tr>
        <th colspan="2">FLUXOS DE EXCEÇÃO</th>
    </tr>
    <tr>
        <td></td>
        <td><br></td>
    </tr>
    <tr>
        <td><br></td>
        <td></td>
    </tr>
    <tr>
        <th>Restrições e validações</th>
        <td></td>
    </tr>
</table>

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
