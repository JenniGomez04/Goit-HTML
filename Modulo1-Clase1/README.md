
 La etiqueta (tag) - Es un elemento del lenguaje de marcado de hipertexto
Estos son los bloques básicos más pequeños de los que se compone cualquier página web.
Cada etiqueta representa una entidad: título, lista, párrafo de texto, imagen. 
Para resaltar las etiquetas entre el texto del documento,
se utiliza corchetes angulares que especifican el nombre de la etiqueta y sus atributos.

<nombre_de_etiqueta>...</nombre de_etiqueta>

Documentación de
https://developer.mozilla.org/es/docs/Web/HTML/Element/input    


La etiqueta a funciona para links: 

    Los atributos de a:

    href - es para el link de destino
    class - referencia al css


<a href="https://www.linkedin.com/in/backmota/" id="1" class="web" target="_blank">José Juan Mota</a>


Link de imagen de perfile desde el servidor de linkedIn
<!-- Forma de poner imagen de un servidor de la web en nuestra web
<img src="https://media-exp1.licdn.com/dms/image/C4E03AQFVPw5-f9LtXg/profile-displayphoto-shrink_200_200/0/1565480390245?e=1666224000&v=beta&t=TOTSiEu90FuLfEJiabFvNIjTCAQgpgYJZufs5BkqXWg"/>
-->
<!--Forma de poner una imagen con archivos locales -->
<img src="img/1565480390245.jpg" alt="Imagen de perfil de José Juan Mota"/>


<!--Etiqueta que sirve para interacción con el usuario (Formulario por ejm)
hay dentro de los input tipos como date, email, file etc-->
Nombre de Usuario 
<input type="password" name="password"/>


<div id="2">Nivel 1<div id="3">Nivel 2<div id="5">Nivel 3</div></div><div id="4">Nivel 2</div></div>
