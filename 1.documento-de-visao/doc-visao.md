# Documento de Visão

## Histórico de Revisões

| Data                |  Versão             |          Descrição  |  Autores            |
| :-----------------: | :-----------------: | :-----------------: | :-----------------: |
| 22/11/2022 | 01 | Versão inicial |  Mayra, Luiz Felipe, Lívia, Valtércio e Renato |


## 1. Objetivo do projeto

O projeto Educa Web tem como objetivo ser uma solução em software para auxiliar a gestão das atividades administrativas e acompanhamento do alunado de determinada escola. 

## 2. Descrição do problema

|     |      |
| --- | --- |
| **Problema**            | Ausência de informatização e acesso a documentos de escolas, gestão de avaliações, alunos e turmas. |
| **Afeta**               | Professores, alunado, secretaria acadêmica. |  
| **Impacta**             | Dificuldade de manter gerenciamento dos dados dos alunos, escola, professores, avaliações, turmas. |
| **Solução**             | Um sistema digital que atenda as necessidades administrativas da escola, acompanhamento dos alunos e atividades dos professores. | 

## 3. Descrição dos usuários 

| Nome                |  Descrição          |   Responsabilidade  |
| -----------------   | -----------------   | -----------------   |
| Aluno | Indivíduo que atende atividades escolares. | Tem acesso a atividades postadas, realiza avaliações; têm acesso resultados de avaliações.  |
| Professor | Indivíduo que leciona disciplinas e avalia alunos. | Registra e mantém frequência de alunos; aplica avaliações; registra e mantém notas avaliativas de alunos; gerencia e avalia os alunos. |
| Responsável | Indivíduos que possuem acesso aos dados e informações de alunos,  professores, escolas. | Acesso à informações dos alunos e professores no sistema; entra em contato com professores e secretaria acadêmica. |
| Secretaria acadêmica | Grupo de indivíduos que mantém a gestão e acesso a dados de uma escola e seus indivíduos. | Acesso completo a dados de funcionários, alunos/responsáveis; registro de funcionários, alunos/responsáveis; registro de matriz de escolas e filiais, matrículas de alunos, diretor acadêmico; emitir relatórios e históricos, atestados de matrícula, declaração de vínculos.|
| Diretor acadêmico | Principal responsável pelo funcionamento de uma escola. | Realiza as mesmas funções e atribuições da secretaria acadêmica, além de gerenciar as pessoas da secretaria acadêmica. |
| Proprietário | Dono da escola. | Administrador. |

## 4. Descrição do ambiente dos usuários

- Ambiente escolar possui secretaria acadêmica, sala de professores, turmas, salas de laboratório, sala de aula e dentre outros.
- As tarefas realizadas vão desde reuniões, aulas e outras práticas acadêmicas.
- A quantidade de alunos varia de acordo com o preenchimento de vagas da escola.

## 5. Principais necessidades dos usuários

- Dificuldade de acessar o conteúdo de avaliações anteriores. A solução é implementada por meio de um sistema digital. O aluno deseja acessar tal conteúdo.
- Manter organização das vagas cedidas para os alunos das devidas turmas. A solução é a implementação de um sistema que facilite o acesso dessas vagas. A secretaria acadêmica deseja que haja uma forma de acessar e manter as vagas.
- Dificuldade em registrar e acessar as notas das avaliações realizadas. A solução é a implementação de um sistema que possui a função de facilitar o acesso e inserção das notas avaliativas. Os professores são quem necessita a solução do problema 
- Problema de um responsável acompanhar o desempenho de um aluno. A implementação de uma função no sistema que permita que um responsável possa acessar as informações de um aluno.
- O diretor acadêmico frequentemente possui o problema de gerenciar os funcionários, manter as matrículas, inserir novas vagas, cadastrar turmas e disciplinas. A solução é implementar um sistema que satisfaça as necessidades do diretor acadêmico.

## 6. Alternativas concorrentes

Sistema Unificado de Administração Pública(SUAP), Q-Acadêmico, SIGEDUC.

## 7. Visão geral do produto

- O sistema de gestão educacional é importante ser implementado porque tem como objetivo facilitar o trabalho da secretaria acadêmica, do professor, o envolvimento de responsáveis e também, melhorar a experiência e desenvolvimento dos alunos que estão associados com a instituição. 
- Por meio de interfaces intuitiva e objetivas, professores poderão realizar o controle de fluxo de frequência mais eficiente, o registro de alunos e outros envolvidos com a instituição será mais rápido e eficiente.
- O resultado das avaliações será mais fácil de se adquirir e analisar, o contato entre responsáveis e professores sobre o desenvolvimento dos alunos será simplificado.
- O sistema ainda terá uma curva simples de aprendizado.


## 8. Requisitos funcionais

| Código              |  Nome               |          Descrição  |  Prioridade         |
| :-----------------: | :----------------- | :----------------- | :-----------------: |
| F001 | Efetuar login usuário | Todos os usuários do sistema podem acessar e efetuar login. | Máxima |
| F002 | Cadastro de funcionário | Cadastro de matrícula de professor, diretor acadêmico e demais funcionários. | Máxima |
| F003 | Cadastro de alunos | Secretaria cadastra alunos. | Máxima |
| F004 | Cadastro de turmas | A secretaria realiza o cadastro de turmas especificando a quantidade de vagas, disciplinas e seus respectivos professores. | Máxima |
| F005 | Cadastrar escola | A Secretaria Acadêmica cadastra escola matriz, filiais e seus respectivos diretores acadêmicos. | Máxima |
| F006 | Emitir atestado de matrícula e histórico de aluno | Tanto aluno quanto Secretaria ou responsável podem emitir esses relatórios. | Moderada |
| F007 | Registrar frequência | O professor registra o fluxo de frequência dos alunos durante as aulas. | Moderada |
| F008 | Desligamento de um aluno em uma modalidade | Um professor, opcionalmente, possui a opção de remover um aluno de uma devida modalidade. | Moderada |
| F009 | Cadastrar resultados de avaliações | O professor realiza atividades avaliativas e em seguida, insere os resultados no sistema. | Moderada |
| F010 | Calcular nota de avaliação |Cálculo de aprovação. | Moderada |
| F011 | Gerenciar disciplinas e turmas | O professor gerencia suas turmas e disciplinas associadas. | Moderada |
| F012 | Acessar turmas, frequência, disciplina e notas (Ver boletim). | O aluno e a secretaria possuem acesso às suas turmas, sua frequência, disciplinas e resultados de suas notas. | Máxima |
| F013 | Acessar conteúdo avaliativo | O aluno pode acessar o conteúdo avaliativo previamente realizado. | Moderada |
| F014 | Matricular-se em disciplina | AAluno é capaz de se matricular em tal disciplina necessária. | Máxima |
| F015 | Associar disciplina | A secretaria aloca uma ou mais de uma disciplina para um professor. | Máxima |

## 9. Requisitos não-funcionais

| Código              |  Nome               |          Descrição  |  Categoria          |  Classificação      |
| :-----------------: | :----------------- | :----------------- | :----------------- | :----------------- |
| NF01 | Senhas mais segura | Só usuários matriculados possuem acesso ao sistema | Segurança | Obrigatório |
| NF02 | Tempo de resposta | A comunicação entre o servidor e o cliente não pode ultrapassar o tempo limite para a jogada. | Performance | Desejável |
| NF03 | Cálculo de aprovação | Sistema possui função que calcula | Avaliação | Obrigatório |
| NF04 | Usabilidade | O sistema é intuitivo o suficiente durante o seu uso. | Interface | Desejável |
| NF05 | Controle de uso | O sistema encerra a sessão após determinado tempo de inatividade. | Segurança | Desejável |
| NF06 | Curva de aprendizado | A curva de aprendizado é simples o suficiente para qualquer um aprender. | Peformance | Desejável |
| NF07 | Uso simultâneo | Muitas pessoas podem acessar o sistema ao mesmo tempo. | Peformance | Desejável |
| NF08 | Acessibilidade | Pessoas que possuem impedimento fisicamente e psicologicamente poderão usar com mais facilidade o sistema. | Usabilidade | Desejável | 