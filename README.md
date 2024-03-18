Univesidade Lusófona
**Programação Web**

# Ficha 4: Modelação em Django

### Objetivo:
* familiarizar-se com a modelação em Django.
* Criar projeto django no pc
* Criar um projeto django diretamente no PythonAnywhere seguindo os passos apresentados na aula teória. Use como username o seu número.
* Criar várias aplicações, centrando-se apenas na modelação e criação de alguns conteúdos usando a aplicação admin do Django, interface de administração da base de dados.

### 1. Aplicação Pessoas no PythonAnyWhere

* siga os passos do [tutorial](pw-24-04-criacao-de-app-em-pythonanywhere.pdf) para criar uma primeira aplicação em Django diretamente no PythonAnyWhere

### 2. Aplicação bandas

* seguindo os passos dos slides anteriores, a partir da parte 3 (slide 19), crie uma nova aplicação **bandas**:
   1. `python manage.py startapp bandas`
   1. em `project\settings.py`, adicione à lista `INSTALLED_APPS` a aplicação `bandas`. 
* em models.py, crie um conjunto de classes que permitam definir bandas, seus álbuns e músicas. No final, não se esqueça de:
   * registar cada uma das classes em admin.py
   * migrar as alterações com makemigrations e migrate
   * relançar a aplicação
* Em relação a cada classe, crie um conjunto de atributos. Sugestões:
   * guarde para cada álbum uma capa
   * para algumas músicas guarde o link da música no spotify
   * guarde uma foto da banda, e informações variadas
* faça os passos makemigrations e migrate para migrar o models para a base de dados 
* crie conteúdos de um par de bandas e seus discos e músicas através da aplicação admin.
* configure a aplicação admin de modo a listar informação util e permitir pesquisas adequadas.

Nota: daqui a algumas semanas irá construir a parte de front-end desta aplicação.

### 3. Aplicação artigos

Crie uma aplicação que permita armazenar artigos de vários autores. Inspire-se em blogs que conheça de modo a fazer uma modelação rica. deverá permitir, além dos posts, inserir comentários, e ratings. Insira 2 artigos, por exemplo, do blog medium ou Quora. 

Esta aplicação será integrada no seu projeto final, o seu protfolio. vAqui incluirá artigos que considera interessantes ligados com a Programação Web.

# Submissão

submeta o link da sua aplicação, assim como as credenciais de um superuser para aceder ao admin (username e password). Pode criar vários superusers


