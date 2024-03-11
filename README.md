Univesidade Lusófona
**Programação Web**

# Ficha 4: Modelação em Django

### Objetivo:
* familiarizar-se com a modelação em Django.
* Crie um projeto django diretamente no PythonAnywhere seguindo os passos apresentados na aula teória. Use como username o seu número.
* Irá criar várias aplicações, centrando-se apenas na modelação e criação de alguns conteúdos usando o admin.
* explore a aplicação

  
### 1. Aplicação Música

* seguindo os passos dos slides da aula teórica, crie a aplicação bandas:
   1. `python manage-py startapp bandas`
   1. em `project\settings.py`, adicione à lista `INSTALLED_APPS` a aplicação `bandas`. 
* em models.py, crie um conjunto de classes que permitam definir bandas, seus álbuns e músicas. 
* Em relação a cada classe, crie um conjunto de atributos. Sugestões:
   * guarde para cada álbum uma capa
   * para algumas músicas guarde o link da música no spotify
   * guarde uma foto da banda, e informações variadas
* guarde informação para cada uma das tabelas através da aplicação admin.
* configure a aplicação admin de modo a listar informação util e permitir pesquisas adequadas.

Nota: daqui a algumas semanas irá construir a parte de front-end desta aplicação.

### 2. Aplicação Curso

crie uma aplicação que permita definir um curso, suas disciplinas, seus docentes e projetos. Inspire-se nesta [página](https://informatica.ulusofona.pt/projetos-de-unidades-curriculares) e [nesta](https://informatica.ulusofona.pt/ensino/licenciaturas/engenharia-informatica/)

Algumas ideias:
* uma disciplina tem um conjunto de docentes
* um docente pode lecionar várias disciplinas
* uma disciplina tem um conjunto de informações tais como ano, semestre, programa.
* uma disciplina pode ter um ou mais projetos
* configure a aplicação admin de modo a listar informação util de cada classe e permitir pesquisas adequadas.

### 3. Aplicação Mentoria

O Programa de Mentoría é um programa do DEISI de alunos para alunos, suportado por uma [aplicação](https://horarios.pythonanywhere.com/) em desenvolvimento no âmbito dum TFC. Explore a aplicação, fazendo login e pedindo recuperação da sua password com o email que está no Moodle. 

Crie uma aplicação que modele o programa de mentorias. Algumas ideias:
* um aluno pode ser mentor/mentorando de uma ou mais disciplinas
* uma díade é um par (mentor,mentorando), que realiza sessões de mentoria em dias específicos
* configure a aplicação admin de modo a listar informação util de cada classe e permitir pesquisas adequadas.
