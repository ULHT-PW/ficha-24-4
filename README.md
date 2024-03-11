# ficha-24-4

# 1. Projeto no PythonAnyWhere

* Crie um projeto django no PythonAnywhere seguindo os passos apresentados na aula teória. Use o seu numero como username.

# 2. Exercícios de modelação

### Aplicação Música

* crie uma aplicação que tenha em models.py um conjunto de classes que permitam definir bandas, seus álbuns e músicas. Considere que alguns álbuns são colectâneas best-of, podendo haver músicas repetidas.
* Em relação a cada classe, crie um conjunto de atributos. Em especial guarde para cada álbum uma capa, e para algumas músicas guarde o link da música no spotify.
* guarde informação para cada uma das tabelas através da aplicação admin.

Nota: posteriormente, daqui a algumas semanas, fará a parte de front-end desta aplicação.
  
# Exemplos para exercícios de modelacao

### classes que explorem todos os campos de tipo

### classes que explorem todos os campos de relação
* user - role (n:n)
* cidadão - cartão de identificação (1:1)
* linguagem programaçao - disciplina (1:n)
    * disciplinas que usam determinada linguagem
    * linguagem usada numa disciplina 
* disciplina - aluno (n:n)
    * listar as disciplinas
    * listar disciplinas do 2º ano
    * listar discilpinas do 1º e 2º anos
    * listar nomes dos alunos da disciplina de nome PW
    * alunos de PW com mais de 18 e menos de 25 anos 
* disciplina - professor (n:n) e disciplina - aluno (n:n)
* livro - autor (n:1)

### operações CRUD com ORM Django
métodos:
* create
* save
* all
* filter
* exclude
* add 
* get
* exists
* delete
* remove
* order_by
* count
* values_list
