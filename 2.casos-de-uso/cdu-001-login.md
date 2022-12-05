# CDU001. Login

- **Ator principal**: Aluno/Responsável, Professor, Proprietário, Secretaria/Diretor acadêmico.
- **Atores secundários**: Não há atores secundários.	 
- **Resumo**: No sistema, os usuários recebem uma interface para realizar um login e fazer as demais atividades ou operações associadas com cada usuário.
- **Pré-condição**: Possuir cadastro.
- **Pós-Condição**: Será redirecionado para uma interface com operações disponíveis para o usuário.

## Fluxo Principal
| Ações do ator | Ações do sistema |
| :----------------- | :----------------- | 
| 1 -  Acessar sistema | Sistema é inicialzado.|  
| 2 -  Acessar interface de login | Sistema exibe interface para realizar login.|  
| 3 - Inserir matrícula/e-mail e senha | Sistema recebe dados de usuário inseridos. A autenticação é feita e o sistema redireciona para próxima interface.| 



## Fluxo Alternativo exceção - Senha inválida
| Ações do ator | Ações do sistema |
| :----------------- |:----------------- | 
| 1.1 - Acessar o sistema | Sistema é inicialzado.|  
| 1.2 - Usuário Acessa interface de login | Sistema exibe interface para realizar login. |
| 1.3 - Usuário recupera senha | Sistema envia um e-mail para poder recuperar uma senha |
| 1.4 - Usuário Insere matrícula/e-mail e senha | Sistema recebe dados de usuário inseridos. A autenticação é feita e o sistema redireciona para próxima interface. |

