<h1 align="center">Modelagem de um Sistema</h1>

### Cenário

Em uma faculdade as notas das disciplinas são divididas em dois bimestres N1 e N2.

Ao final do semestre é calculada a nota semestral usando a seguinte fórmula:

```
S = (N1 * 2 + N2 *3)/5
```

O aluno é aprovado caso a NS seja igual ou superior a 70 pontos, caso seja inferior a 35 é
reprovado. Caso contrário ele terá que fazer o exame final. Sendo assim, a nota final é
calculada:
```
Nota Final = (NS *3 + EF *2)/5
```
O aluno é aprovado caso a nota final seja igual ou superior a 50 pontos.

### Problema

* Sempre quando as notas do 1º bimestre são divulgadas, os alunos querem calcular a nota mínima necessária para ser aprovado.
* Sempre quando os alunos já sabem as notas do 1º e 2º bimestres, eles querem calcular a nota final e saber se foram aprovados ou ficaram de exames.
* Sempre quando as notas finais são divulgadas:
  * Os alunos que ficaram de exame de final querem calcular a nota mínima
necessária para tirar no exame final e ser aprovado.


Sendo assim, a universidade identificou que os alunos precisam de um software para auxiliá-los a resolver esses problemas e contratou uma equipe de desenvolvimento de software criar um aplicativo.

Além disso, a universidade pediu para criar uma forma do aluno conseguir salvar as notas de cada disciplina (N1, N2, Exame Final) a medida que elas são divulgadas.

* Os alunos podem salvar as notas de cada disciplina assim que elas são divulgadas
	* O aluno pode salvar notas das disciplinas e ver status (cursando, aprovado, reprovado, ficou exame final)
	* O aluno pode ver as notas das disciplinas já cadastradas
	* O aluno pode alterar as notas já cadastradas
	* O aluno pode excluir uma disciplina cadastrada

### Proposta

Sua equipe irá participar do desenvolvimento do aplicativo que vai oferecer as funcionalidades que os alunos precisam. Com base nas informações apresentadas anteriormente sua equipe será responsável por:

1. Identificar os requisitos funcionais e não funcionais (e priorizá-los). (5 pontos)
2. Modelar o diagrama de casos de uso (5 pontos)
3. Especificar os casos de uso. (5 pontos)
4. Criar wireframes ou protótipos das telas do aplicativo (com Figma ou outro software) (5 pontos)
5. Documentar usando o MkDocs

Use a criatividade para resolver o problema criando o projeto de software desse aplicativo