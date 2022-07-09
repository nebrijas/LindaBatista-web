# Repositorio de trabajo del módulo de Periodismo de Datos II #
A continuación las actividades del módulo de Periodismo de Datos II: Herramientas digitales para la visualización y presentación de datos (2021-2022).
- [Actividad dirigida 1](https://github.com/nebrijas/LindaBatista-web/blob/main/ad1.md)
- [Actividad dirigida 2](https://github.com/nebrijas/LindaBatista-web/blob/main/ad2.md)
- [Actividad dirigida 3](https://github.com/nebrijas/LindaBatista-web/blob/main/ad3.ipynb)
- [Actividad dirigida 4](https://github.com/nebrijas/LindaBatista-web/blob/main/ad4.ipynb)
# Actividad Final: ¿Qué aprendí de la asignatura?
A lo largo de la materia aprendí aspectos básicos relevantes sobre Markdown, GitHub y GitBash, para la visualización de datos.
##Sobre Markdown
En la primera actividad dirigida aprendí sobre el uso de código de *Markdown*, que es de hecho muy sencillo, y a pesar de no conocerlo en primer lugar, es fácil de recordar.
**Aprendí que**:
-	Las almohadillas (#) nos ayudan a titular. El énfasis puede variar según la importancia que queramos darle. Por ejemplo: Si empleo una sola almohadilla delante del texto en *Markdown*, el título es el más destacado y será h1, si utilizo dos será h2 y reduce el tamaño de este, y así sucesivamente. 
-	Los asteriscos ayudan a enfatizar frases o palabras poniéndolas en cursiva o negrita. En este caso, si utilizo dos asteriscos (**), al inicio y al final del texto, **puedo poner un texto en negrita**, mientras que si uso uno (*) solo *puedo hacer que el texto sea cursivo*.
-	Por otro lado, si utilizo tres asteriscos (***) antes y después del texto, este me quedará en ***negrita y cursiva***.
-	Para hacer listas, como esta, coloco un guion delante del texto, y si quiero enumerar textos, utilizo cifras seguidas de un punto. Por ejemplo: 
1.	Texto 1
2.	Texto 2
3.	Texto 3
-	Si deseo colocar un enlace debo encerrar la palabra que destacará entre corchetes ([]) y seguido poner entre paréntesis el enlace. Por ejemplo: Soy Linda Batista y este es [mi repositorio]( https://github.com/nebrijas/LindaBatista-web).
-	Para añadir imágenes, la función es similar a la de enlaces. Debo colocar el nombre de la foto dentro de un signo de admiración, corchetes y seguida del enlace de la imagen entre paréntesis. Por ejemplo: ![IMAGEN RELACIONADA](https://avatars.githubusercontent.com/u/107362070?s=400&u=cd8f2a43667c36755213a864f28124a5f1027ab4&v=4)

## Sobre GitHub
GitHub es un portal creado para alojar el código de las aplicaciones de cualquier desarrollador. Todas las actividades fueron colgadas en el repositorio que creamos en esta plataforma. 
-	Primero cree una cuenta en [https://github.com/]( https://github.com/)
-	En GitHub puedo hacer que mi repositorio, con texto en código *Markdown* pueda verse como una página web, sin la necesidad de recurrir a programación compleja.
Para crear el repositorio:
1.	Me voy a la esquina superior derecha de la página, selecciono en el “menú hamburguesa” crear nuevo repositorio.
2.	Posteriormente describo un nombre sencillo.
3.	Puedo o no agregarle una descripción sobre lo que será el repositorio.
4.	Determino si será visible o no para todo público.
5.	Inicio con README y creo el nuevo repositorio.

## Sobre Git, GitBash y la programación literaria
**Mediante la actividad dirigida 2 aprendí**:
### Con el GitBash aprendí que: 
- Con **cd** puedo moverme de una carpeta a otra dentro de la terminal y con pwd identifico en qué carpeta estoy.
- Con **ls** puedo ver el contenido que hay dentro de una determinada carpeta, y con **ls -a** veo los archivos ocultos.
- Con **git clone** y mi enlace de GitHub puedo clonar mi repositorio dentro del archivo en mi computadora; mientras que con **git config** configuro el repositorio. 
- Para esto debo colocar user.name y el user.email, detallando mi nombre de usuario y el correo con el que creé la cuenta.
- Por otro lado aprendí que con **rm** puedo eliminar archivos; y que **nano** sirve para editar archivos directamente a través de Git Bash.
- **Git status** por su parte, se utiliza para saber el estado o los archivos de la carpeta local y de GitHub.
- Con **git add** añado modificaciones al repositorio de GitHub; con **git restore** restauro la versión previa; y con**git commit -m** + "texto" añado comentarios sobre los cambios que hice.
- Y finalmente **git push** que guarda los cambios en el repositorio y **git pull** funciona en el sentido contrario para guardar los cambios del repositorio en el archivo local.
### Programación Literaria
Este es un tipo de programación que me permite desarrollar con los diferentes lenguajes una programación, a medida que voy explicando lo que estoy haciendo.
Con estos ejercicios me ayudo a recordar y le enseño a otros a cómo hacer programaciones determinadas.
## Sobre Jupyter
Utilizamos la plataforma Jupyter con documentos de Python para posteriormente visualizarlos en GitHub. 
**En Jupyter**:
Se utiliza el texto en Markdown para explicar el ejercicio, y se deja el texto en *code* cuando se trata de un código. 
También, aprendí a cómo convertir datos de tablas, a gráficas.
-	Con la función *Type* verifica qué tipo de código era
-	Con *df* aprendí el uso de creación de variables dataframe.
-	A la variable Json hay que llamarla: *pd.read_json()*.
-	Para *plotear* algo, debo detallar el nombre de la variable seguido de .plot() .
