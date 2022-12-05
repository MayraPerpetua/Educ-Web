# CDU001. Lançar Notas

- **Ator principal**: Professor.
- **Atores secundários**: Aluno.	 
- **Resumo**: O professor insere as notas obtidas pelos alunos.
- **Pré-condição**: Estar logado, estar alocado em turma, possuir turma com alunos matriculados.
- **Pós-Condição**: As notas iseridas estão salvas em uma determinada avaliação que foi inserida no sistema.

## Fluxo Principal
| Ações do ator | Ações do sistema |
| :----------------- | :----------------- | 
| 1 -  Fazer login no sistema | Sistema é inicialzado.|  
| 2 -  Acessar as avaliações cadastradas | Sistema exibe as avaliações disponíveis |  
| 3 - Executar a opção de inserir notas avaliativas | Sistema registra as notas dos alunos.| 


## Fluxo Alternativo exceção - Correção de nota
| Ações do ator | Ações do sistema |
| :----------------- |:----------------- | 
| 1.1 - Acessar o sistema | Sistema é inicialzado.|  
| 1.2 - Acessar as avaliações cadastradas | Sistema exibe as avaliações disponíveis. |
| 1.3 - Executar a opção de editar nota | Sistema registra as alterações realizadas. |