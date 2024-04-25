# Casos de uso 


![App FEPI](https://github.com/lucagx/App-FEPI-documentacao/assets/138620602/3cf5049c-992e-4eae-8448-0d0cbdb3814f)

#### Atores:
- Aluno
#### Casos de Uso:
- **Gerenciar Disciplinas:**
	- Descrição: Permite ao aluno adicionar, visualizar, alterar e excluir disciplinas.
        - Subcasos de Uso:
            - Adicionar Disciplina
            - Visualizar Disciplinas
            - Alterar Disciplina
            - Excluir Disciplina
- **Gerenciar Notas:**
	- Descrição: Permite ao aluno inserir e visualizar notas de cada disciplina.
	- Subcasos de Uso:
		- Salvar Notas
		- Ver Notas Cadastradas
		- Alterar Notas Cadastradas
- **Verificar Status:**
	- Descrição: Permite ao aluno visualizar o status de cada disciplina (cursando, aprovado, reprovado, exame final).
- **Calcular Notas:**
	- Descrição: Realiza cálculos de notas com base nas notas inseridas.
	- Subcasos de Uso:
		- Calcular Nota Mínima para Aprovação
		- Calcular Nota Final
		- Calcular Nota Mínima no Exame Final
- **Autenticação:**
	- Descrição: Permite ao aluno autenticar-se no sistema.
- **Validar Notas:**
	- Descrição: Verifica se as notas inseridas pelo aluno estão dentro dos limites aceitáveis.
#### Relacionamentos:
- O caso de uso "Gerenciar Disciplinas" está relacionado com os casos de uso "Gerenciar Notas" e "Verificar Status", pois as disciplinas são a base para inserção de notas e status.
- O caso de uso "Gerenciar Notas" está relacionado com o caso de uso "Calcular Notas", pois as notas inseridas são utilizadas nos cálculos.
- O caso de uso "Calcular Notas" está relacionado com o caso de uso "Verificar Status", pois os resultados dos cálculos influenciam no status das disciplinas.

#### Descrições:
##### Gerenciar Disciplinas:
Descrição: Este caso de uso permite ao aluno realizar operações relacionadas à gestão das disciplinas em que está matriculado. Ele pode adicionar novas disciplinas, visualizar as disciplinas cadastradas, alterar informações das disciplinas existentes e excluir disciplinas que não deseja mais acompanhar.
###### Adicionar Disciplina:
Descrição: Permite ao aluno adicionar uma nova disciplina ao seu perfil no sistema, inserindo informações como nome da disciplina, código, horário, professor, entre outros.
###### Visualizar Disciplinas:
Descrição: Permite ao aluno visualizar a lista de disciplinas cadastradas em seu perfil, incluindo informações como nome da disciplina, código, horário, professor, status, entre outros.
###### Alterar Disciplina:
Descrição: Permite ao aluno alterar as informações de uma disciplina já cadastrada, como horário, professor, entre outros dados.
Excluir Disciplina:
Descrição: Permite ao aluno excluir uma disciplina que já foi cadastrada em seu perfil no sistema.
##### Gerenciar Notas:
Descrição: Este caso de uso permite ao aluno inserir e gerenciar as notas referentes às disciplinas em que está matriculado. Ele pode salvar as notas recém-divulgadas, visualizar as notas cadastradas anteriormente e, se necessário, alterar essas notas.
###### Salvar Notas:
Descrição: Permite ao aluno salvar as notas de uma disciplina assim que elas são divulgadas, inserindo as notas dos respectivos bimestres.
###### Ver Notas Cadastradas:
Descrição: Permite ao aluno visualizar as notas das disciplinas que já foram cadastradas, incluindo as notas do primeiro e segundo bimestres, bem como a nota final, se disponível.
###### Alterar Notas Cadastradas:
Descrição: Permite ao aluno alterar as notas das disciplinas que já foram cadastradas, caso haja algum erro ou atualização nas notas divulgadas.
##### Verificar Status:
Descrição: Este caso de uso permite ao aluno visualizar o status atual de cada disciplina em que está matriculado. O status inclui informações como se está cursando a disciplina, se já foi aprovado, se foi reprovado ou se precisa fazer o exame final.
##### Calcular Notas:
Descrição: Este caso de uso realiza cálculos de notas com base nas notas inseridas pelo aluno. Ele calcula a nota mínima necessária para aprovação, a nota final com base nas notas do primeiro e segundo bimestres, além de calcular a nota mínima necessária no exame final.
###### Calcular Nota Mínima para Aprovação:
Descrição: Calcula a nota mínima necessária para que o aluno seja aprovado em uma disciplina com base nas notas do primeiro e segundo bimestres, de acordo com os critérios de aprovação definidos.
###### Calcular Nota Final:
Descrição: Calcula a nota final do aluno em uma disciplina com base nas notas do primeiro e segundo bimestres, levando em consideração os critérios de aprovação e a necessidade de exame final, se aplicável.
###### Calcular Nota Mínima no Exame Final:
Descrição: Calcula a nota mínima necessária no exame final para que o aluno seja aprovado em uma disciplina, caso tenha ficado de exame final, conforme os critérios estabelecidos.
##### Autenticação:
Descrição: Este caso de uso permite ao aluno autenticar-se no sistema fornecendo suas credenciais de login. A autenticação é necessária para acessar as funcionalidades do sistema e garantir a segurança dos dados do aluno.
##### Validar Notas:
Descrição: Este caso de uso verifica se as notas inseridas pelo aluno estão dentro dos limites aceitáveis (0 a 100 pontos). Se alguma nota estiver fora desses limites, o sistema apresenta uma mensagem de erro e solicita que as notas sejam corrigidas.
