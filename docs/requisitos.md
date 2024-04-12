 <h1> Requisito de Software </h1>


#### Requisitos funcionais

**ID**      | **Nome RF**  | **Descrição RFs**
:-----------|:-------------|:-------------
**RF01**    | Calcular nota mínima para aprovação | O sistema deve calcular a nota mínima necessária para ser aprovado com base na nota do 1º bimestre fórmula.     
**RF01.1**  | Calcular nota final e verificar status de aprovação | O sistema deve calcular a nota final com base nas notas do 1º e 2º bimestres e verificar se o aluno foi aprovado, reprovado ou precisa fazer o exame final.         
**RF01.2**  | Calcular nota mínima necessária no exame final | O sistema deve calcular a nota mínima necessária no exame final para que o aluno seja aprovado, caso tenha ficado de exame final.
**RF02**    | Salvar notas | Os alunos podem salvar as notas de cada disciplina assim que elas são divulgadas.
**RF03**    | Ver status | Ver o status de cada disciplina (cursando, aprovado, reprovado, ficou de exame final)
**RF04**    | Ver notas cadastradas | Os alunos podem visualizar as notas das disciplinas que já foram cadastradas.
**RF04.1**  | Alterar as notas cadastradas | Os alunos podem alterar as notas das disciplinas que já foram cadastradas.
**RF05**    | Excluir disciplina cadastrada | Os alunos podem excluir uma disciplina que já foi cadastrada.



#### Requisitos não funcionais

**ID**      | **Nome RNF** | **Descrição RNFs**
:-----------|:-------------|:-------------
**RNF01**   | Desempenho | O sistema deve realizar cálculos de notas de forma eficiente, sem demoras significativas.
**RNF02**   | Usabilidade | A interface do sistema deve ser intuitiva e fácil de usar.
**RNF03**   | Segurança | As informações das notas dos alunos devem ser armazenadas de forma segura e protegidas contra acesso não autorizado.


#### Regras de negócio

**ID**      | **Nome RN** | **Descrição RNs**
:-----------|:-------------|:-------------
**RN01**    | Critérios de Aprovação e Reprovação | Para ser aprovado, a nota semestral (NS) deve ser igual ou superior a 70 pontos. Reprovado ser inferior a 35 pontos. Caso a (NS) esteja entre 35 e 70 pontos, o aluno precisará fazer o exame final.
**RN01.2** | Critérios de Aprovação com Exame Final | Para ser aprovado após o exame final, a nota final (Nota Final) deve ser igual ou superior a 50 pontos.
**RN02** | Fórmulas de Cálculo | A nota semestral (NS) é calculada pela média ponderada das notas do 1º e 2º bimestres. A nota final (Nota Final) é calculada pela média ponderada da nota semestral (NS) e da nota do exame final (EF).
**RN03** | Validação das Notas | O sistema deve validar as notas fornecidas pelo aluno para garantir que estejam dentro dos limites aceitáveis (0 a 100 pontos). Se for fora dos limites o sistema deve apresentar uma mensagem de erro e solicitar que as notas sejam corrigidas.
**RN04** | Perfil de Usuário e Autenticação | Os alunos podem criar um perfil no sistema, tendo seu login usando suas credenciais. O sistema deve garantir a autenticação segura dos alunos no momento do login.
**RN05** | Gerenciamento de Disciplinas e Notas | O sistema deve permitir que o aluno forneça as notas de cada disciplina e ter permissão para visualizar, alterar e excluir as notas e disciplinas cadastradas.
**RN06** | Segurança e Privacidade | As informações do perfil do aluno, bem como as notas das disciplinas, devem ser mantidas em sigilo e acessíveis apenas pelo próprio aluno. O sistema deve implementar medidas de segurança adequadas para proteger os dados.



