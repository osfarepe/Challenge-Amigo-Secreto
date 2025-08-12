Juego del Amigo Secreto

Este es un juego sencillo en JavaScript, HTML y CSS que permite a los usuarios ingresar nombres de amigos y luego realizar un sorteo aleatorio para determinar quién es el amigo secreto.  


Características
- Añadir nombres a la lista mediante un campo de texto y un botón.
- Validación de datos para evitar ingresar nombres vacíos.
- Visualización dinámica de la lista de amigos agregados.
- Sorteo aleatorio que selecciona un amigo de la lista.

Estructura del proyecto

index.html # Estructura principal del juego
app.js # Lógica del juego
styles.css # Estilos (opcional, también puede ir en HTML)


Tecnologías utilizadas
HTML5  Estructura de la interfaz.
CSS3  Estilos y diseño.
JavaScript Lógica de programación (variables, condicionales, funciones y arrays).

---

Cómo usarlo
1. Clona este repositorio:
   ```bash
   git clone https://github.com/usuario/amigo-secreto.git

2. Abre el archivo index.html en tu navegador.

3. Escribe un nombre en el campo de texto y haz clic en "Añadir".

4. Repite hasta tener la lista de amigos completa.

5.Haz clic en "Sortear Amigo" para elegir un amigo al azar.

6. El nombre sorteado se mostrará en pantalla.
(Los nombres pueden repetirse en sorteos posteriores)

Lógica principal
- Los nombres se almacenan en un array (amigos).

- Math.random() se utiliza para generar un índice aleatorio.

- Math.floor() redondea ese índice al número entero más cercano.

- El DOM se actualiza para mostrar la lista y el resultado.