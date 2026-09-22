# Exercícios de SELECT - Modelo de Dados de Curso

Utilizando o modelo de dados de Curso (`TB_ALUNO`, `TB_DISCIPLINA`, `TB_PROFESSOR`, `TB_CLASSE`, `TB_ESTADO`, `TB_ALUNO_DISCIPLINA`).

Script completo de criação do banco, tabelas e dados: [exercicios_select.sql](exercicios_select.sql)

---

## A - Exercícios de SELECT básico

**A1) Queremos selecionar todos os alunos cadastrados.**

<img src="A1) Todos os alunos cadastrados.PNG" width="400"/>

**A2) Queremos selecionar todos os nomes de disciplina, cujo a nota mínima seja maior que 5 (cinco).**

<img src="A2) Nomes de disciplina com nota mínima maior que 5.PNG" width="400"/>

**A3) Queremos selecionar todas disciplinas que tenham nota mínima entre 3 (três) e 5 (cinco).**

<img src="A3) Disciplinas com nota mínima entre 3 e 5.PNG" width="400"/>

---

## B - Exercícios de SELECT (Ordenando e agrupando dados)

**B1) Queremos selecionar todos os alunos em ordem alfabética de nome de aluno, e também o número da classe que estuda.**

<img src="B1) Alunos em ordem alfabética, com número da classe.PNG" width="400"/>

**B2) Selecionaremos o item anterior, porém ordenado alfabeticamente pelo identificador do aluno de forma descendente (ascendente é "default").**

<img src="B2) Mesmo item, ordenado por código do aluno de forma descendente.PNG" width="400"/>

**B3) Selecionaremos todos os alunos que cursam as disciplinas de matemática E de português agrupados por aluno e disciplina.**

<img src="B3) Alunos que cursam Matemática E Português, agrupados por aluno e disciplina.PNG" width="400"/>

---

## C - Exercícios de SELECT (Junção de Tabelas)

**C1) Queremos selecionar todos os nomes de alunos que cursam Português ou Matemática.**

<img src="C1) Nomes de alunos que cursam Português ou Matemática.PNG" width="400"/>

**C2) Queremos selecionar todos os nomes de alunos cadastrados que cursam a disciplina FÍSICA e seus respectivos endereços.**

<img src="C2) Nomes e endereços de alunos que cursam Física.PNG" width="400"/>

**C3) Queremos selecionar todos os nomes de alunos cadastrados que cursam física e o andar que se encontra a classe dos mesmos.**

<img src="C3) Nomes de alunos que cursam Física e o andar da classe.PNG" width="400"/>

---

## D - Exercícios de SELECT (OUTER JOIN)

**D1) Selecionar todos os Professores com suas respectivas disciplinas e os demais Professores que não lecionam disciplina alguma.**

<img src="D1) Professores com suas disciplinas, incluindo os que não lecionam nenhuma.PNG" width="400"/>

---

## E - Exercícios de SELECT (Cláusula IN e/ou SUBSelect, sem junção)

**E1) Selecionar todos os nomes de professores que tenham ministrado disciplina para alunos que sejam do Estado do Piauí, cujo a classe tenha sido no terceiro andar.**

<img src="E1) Professores que lecionaram para alunos do Piauí, classe no 3º andar.PNG" width="400"/>
