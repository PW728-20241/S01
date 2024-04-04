# Semana 01: Ejercicio práctico
#### Comandos Git 
---

### Indicaciones:

Para poder realizar esta actividad deben primero clonar el repositorio:
`git clone https://github.com/PW728-20241/S01.git`
Es importante recordar que únicamente podrán clonar el repositorio si son parte de la organización `PW728-20241`.

El repositorio es una web estática (HTML + JS + CSS). Para poder ejecutarlo de forma local se puede hacer de muchas formas. La opción más rápida y sencilla es a través de una extensión de Visual Studio Code llamada **Live Server**  

Paso 1: **Búsqueda de la extensión** En el bloque de extensiones de Visual Studio Code usamos la barra de búsqueda y escribimos **_live server_** como se muestra en la siguiente imagen.
![](/liveserver-search.png).

Paso 2: **Instalación de la extensión** Luego de hacer click en la extensión se nos presentará la siguiente pantalla y le damos click al botón instalar.
![](/live-server.png).

Paso 3: **Ejecución** Cuando la extensión esté instalada, en la barra inferior de Visual Studio Code tendremos un nuevo botón con el texto "Go Live". Cuando se le hace click, se inicia un servidor local y se abrirá nuestro navegador por defecto en la dirección `127.0.0.1:5000`
![](/live-server-ex.png).

Se puede detener el **live server** de forma similar haciendo click en el mismo botón inferior de hace un rato.

#### ¡Importante!
Cada archivo HTML se podrá visualizar una vez ejecutado en el live server dependiendo de su nombre. Por ejemplo:
* `index.html` --> `127.0.0.0:5500/index.html` ***este es un caso especial porque también se puede ver por defecto desde `127.0.0.0:5500/`***
* `edgar.html` --> `127.0.0.0:5500/edgar.html`
* `alumno.html` --> `127.0.0.0:5500/alumno.html`

y así también con archivos HTML dentro de carpetas.

## Ejercicios:
#### Nivel 1
* Añadir un archivo nuevo al repositorio. Debe ser un archivo html con el nombre que corresponde a su código de alumno. Por ejemplo, si tu código de alumno es 20203452, entonces debes crear un archivo `20203452.html`.
* Al hacer la publicación en el repositorio (_push_). El commit debe tener un mensaje con el nombre completo del alumno.
* El archivo debe ser una copia del `template_alumno.html` haciendo una modificación del tag `<title>` por la cadena de texto `Programación Web 728 | [nombre completo]`.

#### Nivel 2
* Modificar el archivo que has copiado de `template_alumno.html` con información relevante tuya (en el template está un ejemplo con mis datos). En la primera columna incluye tu nombre y alguna descripción pero no incluyas datos personales ni sensibles. En la segunda columna, puedes añadir frases o información que quieras compartir. Pueden ser sobre películas, libros, frases de futbolistas, estrellas de cine, música, etc. Tú decides. 

#### Nivel 3
* Modifica el archivo `index.html` de tal manera que la sección de **Recent Post** te direccione a lo que has escrito en el paso anterior. Debes cambiar la sección con un título y nombre que consideres pertinente. Debes modificar esta sección del HTML o agregarla si ya no quedan espacios disponibles.

  ``` html
    <div class="fh5co-blog animate-box"><a href="/design" class="blog-bg"
        style="background-image:url(assets/images/blog-1.jpg)"></a>
        <div class="blog-text"><span class="posted_on">Feb. 15th 2045</span>
            <h3><a href="/design">Photoshoot On The Street</a></h3>
            <p>Far far away, behind the word mountains, far from the countries Vokalia and Consonantia, there live
                the blind texts.</p>
            <ul class="stuff">
                  <li><i class="icon-heart2"></i>249</li>
                  <li><i class="icon-eye2"></i>1,308</li>
                  <li><a href="/design">Read More<i
                        class="icon-arrow-right22"></i></a></li>
            </ul>
            </div>
        </div>
    </div>
  ``` 
* Al hacer el commit añade un mensaje significativo al momento de hacer `git commit`.  