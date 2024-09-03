# Capítulo IV: Product Design
## 4.1. Style Guidelines
### 4.1.1. General Style Guidelines

<b>Misión</b>  
Proporcionar a nuestros clientes una plataforma donde puedan alquilar de manera rápida, sencilla y segura scooters eléctricos que se adecúen a sus necesidades.

<b>Visión</b>  
Ser la aplicación web líder en el alquiler de scooters eléctricos, promoción del transporte ecoamigable y reconocidos por grupos y asociaciones de emprendimiento y medio ambiente.

<b>Brand Name</b>  
El nombre del producto es MoviRent, el cual cuenta con un logo representado por el icono de un scooter y un rayo que simboliza que el vehículo funciona electricamente con el color verde como el más predominante simbolizando el medio ambiente.  
![Logo](https://github.com/user-attachments/assets/4117bfeb-a0f2-4a3c-9a45-13fb105fb737)

<b>Colores</b>  
Decidimos elegir los colores verde claro, lila y azul al ser una combinación ligera y agradable a la vista de usuarios de diversad edades.  
![Paleta de colores](https://github.com/user-attachments/assets/4725a7ff-e7ac-4bf4-b1fd-a60d3bc9c98f)

<b>Tipografía</b>
Elegimos la fuente Open Sans porque es legible y popular en el diseño de aplicaciones web, por lo que nos aseguramos de que nuestros clientes con toda clase de necesidades visuales logren leer facilmente el contenido de nuestra web.  
![Fuentes](https://github.com/user-attachments/assets/75992501-cdf2-4a55-bc42-dd726bab6adc)

<b>Espaciado</b>  
Para nuestra aplicación usaremos el espaciado x1.5, el cual es un poco mas amplio que el usual, lo que evitará que el texto se sienta pesado o genere complicaciones de legibilidad

Tamaño de letra: 42px-20px

Interlineado: 1.5px

<b>Tono de comunicación y lenguaje aplicado</b>  
Usaremos un tono  de comunicación entusiasta y amigable en toda la web, puesto que consideramos que sería adecuado para nuestro tipo de aplicación al buscar incentivar el uso concurrido de esta. Además haremos uso de un lenguaje popular para ser inclusivos con todo tipo de nivel de lenguaje entre nuestros usuarios.

### 4.1.2. Web Style Guidelines 

Paleta de colores: Asignamos al color verde y lila como los colores más representativos de la web a demás del color blanco para mostrar una disminución en la recarga de colores para que la atención de los usuarios vaya hacia los servicios y no se desvíe a otra parte menos relevante.

Diseño Responsivo: La aplicación debe ser compatible con diferentes dispositivos y tamaños de pantalla para una experiencia de usuario consistente en todos los dispositivos.

Navegación Intuitiva: Estructura de navegación clara y fácil de usar que permita a los usuarios encontrar rápidamente la información que están buscando, se prioriza la simplicidad.

Carga Rápida: Optimización del rendimiento de la aplicación para tiempos de carga rápidos, lo que incluye la optimización de imágenes y el uso de técnicas de almacenamiento en caché así como los scripts cargados al inicio de la página.

Diseño de Tarjetas: Diseños de tarjetas para mostrar la información de manera visualmente atractiva y organizada, especialmente para la presentación de destinos y detalles de viajes.

Botones de la web: Los botones utilizados para la web serán botones rectangulares con esquinas circulares, ademas de tener botones en forma de texto en la navbar para una mejor navegación en la aplicación.

![Botones](https://github.com/user-attachments/assets/be33d4a1-f502-4f78-84c1-11eae1f82dee)

## 4.2. Information Architecture
### 4.2.1. Organization Systems

- **Jerarquía Visual:**

Con el propósito de mantener la estética de nuestra plataforma interactiva y a la vanguardia de
la competencia actual, hemos decidido priorizar la interfaz según importancia para facilitar la
interacción con el usuario.

- **Jerarquía de Tipografía:**

Nuestra plataforma difunde información que es recibida por nuestros usuarios con un orden
específico según la demanda. Por lo tanto, es importante tener en cuenta las características
con las que se generan nuestros títulos, subtítulos, párrafos, entre otros.

- **Alineación:**

En nuestra plataforma, nuestras imágenes y botones se encuentran alineados siempre de
manera vertical y horizontal. Permitiendo así agrupar varios objetos de diversos tipos con la
misma información.

- **Color y Contraste:**
A la vista de nuestros segmentos objetivos, el color cumple un rol muy importante en nuestra aplicación, promueve
las correctas composiciones del color, para dirigir diversas emociones y del contraste para
enfatizar aquellos objetos de mayor importancia.

- **Organización Secuencial:**

Además, los métodos de almacenamiento sobre los registros que el usuario final emplea
siguen una organización secuencial, esto con el objetivo de mejorar la simplicidad y la
rapidez con la que se almacenan y acceden a ellos. En el caso de nuestro proyecto
organizaremos se visualizarán la lista de Scooter para los User mientras.


- **Esquemas de categorización de contenido de nuestra web:**

Para el caso de organización visual utilizaremos el sistema jerárquico, lo que nos permitirá resaltar los componentes 
a los que deseamos que el usuario preste mayor atención. Esto dirigirá la atención del usuario a componentes de 
suma importancia.
Para el proceso de reservas de scooters haremos uso de la organización secuencial:
- Solicitud de reserva (clientes):
  - Búsqueda de scooter.
  - Elección del scooter.
  - Solicitud de reserva.
  - Entrega del scooter.
  - Devolución del scooter.

- Solicitud de la inscripción de scooters (owner):
  - Inscripción de scooter a la plataforma.
  - Establecer tarifa y disponibilidad del scooter.
  - Publicar disponibilidad del scooter.

Para los esquemas de organización utilizaremos los siguientes tipos:
- Organización por orden cronológico para el historial de reservas de los clientes.
- Organización por orden alfabético para la sección “Mis scooters” del Owner.

### 4.2.2. Labeling Systems
Para el uso de etiquetas de nuestro landing page, se ha elegido un lenguaje sencillo lo que permite a los usuarios 
familiarizarse con facilidad a las opciones proporcionadas. Esto logrará que los usuarios puedan navegar de manera 
intuitiva.

En el Landing Page visualizará los siguientes botones de navegación:

<table style="text-align: center; width: 100%; border:1px">
	<tbody>
		<tr>
			<td>Etiqueta</td>
			<td>Descripción</td>
		</tr>
		<tr>
			<td>Inicio</td>
			<td>Apartado donde se muestra la información de la aplicación explicando sus características.</td>
		</tr>
		<tr>
			<td>Sobre Nosotros</td>
			<td>Apartado donde se informa al usuario sobre el equipo y el propósito.</td>
		</tr>
		<tr>
			<td>Servicios</td>
			<td>Apartado donde se muestra el tipo de usuario que puede ser y sus ventajas.</td>
		</tr>
		<tr>
			<td>Planes</td>
			<td>Apartado donde se muestran todos los planes de suscripción.</td>
		</tr>
		<tr>
			<td>Team</td>
			<td>Apartado donde el usuario puede comunicarse con nosotros.</td>
		</tr>
		<tr>
			<td>Empieza Ya!</td>
			<td>Apartado redirigir ir a la aplicación web.</td>
		</tr>
	</tbody>
</table>

Para la página es importante, un sistema de etiquetado efectivo para permitir que los usuarios encuentren fácilmente la 
información y los servicios que necesitan. Nuestro sistema de etiquetado considera cuidadosamente cómo presentar la 
información en el sitio web. Después de establecer la organización visual y los esquemas de categorización del contenido, 
se elegirá etiquetas claras y concisas que reflejan el lenguaje común y la comprensión del usuario con palabras comunes 
no pasan de tres palabras. Nos aseguraremos de utilizar etiquetas intuitivas y fáciles de recordar para representar los 
diferentes conjuntos de información y asociaciones entre ellos. También se utilizarán diferentes colores y diseños para 
resaltar y diferenciar las etiquetas y conjuntos de información en mi sitio web. Para evitar confusiones y asegurar la 
coherencia visual en todo el sitio web, se mantendrá un sistema de etiquetado consistente y se evitará el uso de términos 
técnicos o jerga que podría ser confuso para los usuarios.

En el parte superior derecho del home page de la aplicación web contando con tres botones: 
- Mi perfil: Muestrael perfil del usuario.
- Suscripción: Muestra las suscripciones disponibles o la suscripción que el usuario ha comprado.
- Scooters: Muestra tanto los scooters en alquiler como los scooters que el usuario ha puesto en alquiler.

### 4.2.3. SEO Tags and Meta Tags
### 4.2.4. Searching Systems
En esta sección, implementaremos dos métodos para mejorar la experiencia de búsqueda de nuestros usuarios. Se utilizará un sistema de búsqueda por filtros para refinar las búsquedas de la siguiente manera:

**Filtros Disponibles:**  
- Disponibilidad de Ubicación: Este filtro permitirá a los usuarios buscar vehículos disponibles en ubicaciones específicas, lo que será útil para aquellos que deseen encontrar opciones cercanas a ellos.

Con la implementación de estos sistemas de búsqueda y filtros, esperamos mejorar significativamente la experiencia de nuestros usuarios al encontrar el vehículo perfecto para sus necesidades.  
![Filtro](https://github.com/user-attachments/assets/3b1cbc6a-b1ec-435a-b59d-c7eb5d019cab)

### 4.2.5. Navigation Systems
Como sistema de navegación en pantallas desktop optamos emplear una barra de menú horizontal que guiará al usuario por las diferentes secciones con títulos claves y estáticos, esto facilitará al usuario a tener todas las herramientas a la mano y así disfrutar de una mejor navegación. Mientras que en dispositivos móviles se optó por emplear una barra de navegación desplegable.
![Navbar web](https://github.com/user-attachments/assets/fda3de2b-4cc6-47a6-a8d1-b18697d6ea73)

![Navbar movil](https://github.com/user-attachments/assets/ad1b8a37-5013-4e80-8c20-b695133028ae)
  
## 4.3. Landing Page UI Design
### 4.3.1. Landing Page Wireframe
### 4.3.2. Landing Page Mock-up
## 4.4. Web Applications UX/UI Design
### 4.4.1. Web Applications Wireframes  
<b>Wireframes Web versión desktop</b>  
![Wireframe web 1](https://github.com/user-attachments/assets/8498438b-4835-46e7-9ea3-677c93550d90)
![Wireframe web 2](https://github.com/user-attachments/assets/4118ff06-bef6-42d0-a961-2226aa89093c)

 <b>Wireframes Web versión móvil</b>  
![Wireframes movil 1](https://github.com/user-attachments/assets/1e9155a4-ebd7-4c85-bc18-7c2dac62fb00)
![Wireframes movil 2](https://github.com/user-attachments/assets/eb0ddf92-2991-422f-90d1-f5e5c3a0a217)
![Wireframes movil 3](https://github.com/user-attachments/assets/060ac813-5bd7-4f44-82e2-3d79cab09f9e)

### 4.4.2. Web Applications Wireflow Diagrams  
<b>User Goal 01:</b> El usuario quiere Registrarse, iniciar sesión, ver, editar y eliminar su cuenta.  
![WF_UserGoal1](https://github.com/user-attachments/assets/b33c90dc-bce2-4c2f-80d5-80fd10b455b8)

<b>User Goal 02:</b> El usuario quiere ver, crear, editar y eliminar sus scooters.  
![WF_UserGoal2](https://github.com/user-attachments/assets/632e6147-82d9-4bf7-a53f-bdd31e9e659a)

<b>User Goal 03:</b> EL usuario quiere buscar y alquilar un scooter.  
![WF_UserGoal3](https://github.com/user-attachments/assets/e4324249-8197-403b-aebf-07c7aefb6a36)

<b>User Goal 04:</b> El usuario quiere ver reseñas y dejar una reseña.  
![WF_UserGoal4](https://github.com/user-attachments/assets/7d33036d-9b78-469d-8d56-bc4be96ebccc)  

<b>User Goal 05:</b> El usuario quiere ver su historial y volver a alquilar un scooter.  
![WF_UserGoal5](https://github.com/user-attachments/assets/e444ce03-d704-4366-b7cb-505f9e2dd8c1)

<b>User Goal 06:</b> El usuario quiere eliminar su historial.  
![WF_UserGoal6](https://github.com/user-attachments/assets/ea3181fd-bd68-4268-baa5-ef2e4de78866)

<b>User Goal 07:</b> El usuario quiere compar, ver, cambiar y cancelar suscripción.  
![WF_UserGoal7](https://github.com/user-attachments/assets/5b6346c1-d349-49bf-bd8a-599be88fbbb6)

### 4.4.3. Web Applications Mock-ups  
<b>Mockups Web versión desktop</b>  
![Mockups web 1](https://github.com/user-attachments/assets/0073e3c0-435b-483b-9e7a-03f4d31bf51a)
![Mockups web 2](https://github.com/user-attachments/assets/3f28e05a-693f-4e48-a867-aab717aa4a52)

<b>Mockups Web versión móvil</b>  
![Mockups movil 1](https://github.com/user-attachments/assets/a9378be2-1e44-4f0e-96bb-d530f7573c4b)
![Mockups movil 2](https://github.com/user-attachments/assets/262d6134-47b2-4870-847a-61ded8d4abae)
![Mockups movil 3](https://github.com/user-attachments/assets/bc0d70dc-636e-4256-9f67-c8f62f9459c4)

### 4.4.4. Web Applications User Flow Diagrams  

<b>User Goal 01:</b> El usuario quiere Registrarse, iniciar sesión, ver, editar y eliminar su cuenta.  
Cuando el usuario quiera registrarse ingresa sus datos y se registra, cuando quiera iniciar sesión, ingresa su correo y contraseña y se lo redirigirá a su perfil, el cual tendra las opciones de editar sus datos y eliminar su cuenta con un previa confirmación. Cuenta con la opción de cancelar las operaciones.  
![UF_UserGoal1](https://github.com/user-attachments/assets/7065a576-560c-4ee5-b2a7-f7fbc3d923b9)


<b>User Goal 02:</b> El Owner quiere ver, crear, editar y eliminar sus scooters.  
Cuando el Owner se encuentre en la sección de sus scooters podrá verlos, publicar uno nuevo, editarlos y eliminarlos.  Cuenta con la opción de cancelar las operaciones.  
![UF_UserGoal2](https://github.com/user-attachments/assets/fe80df66-b6a5-4dda-99c7-08cc2c5a69b7)


<b>User Goal 03:</b> El Cliente quiere buscar y alquilar un scooter.  
Cuando el Cliente quiera alquilar un scooter, puede buscarlo con el filtro por distrito, ver una lista de todos los scooters disponibles, seleccionar el de su preferencia, alquilarlo y pagarlo. Cuenta con la opción de cancelar las operaciones.  
![UF_UserGoal3](https://github.com/user-attachments/assets/57b44f93-04dd-4a4f-825f-78cff41bb273)


<b>User Goal 04:</b> El Cliente quiere ver reseñas y dejar una reseña.  
Cuando el Cliente quiera ver reseñas de un scooter puede ingresar a ellas entrando a detalles del scooter, tambien puede dejar su reseña luego de alquilar un scooter. Cuenta con la opción de cancelarla.  
![UF_UserGoal4](https://github.com/user-attachments/assets/f194398a-95ce-4e75-ba52-4bc1cc90868c)


<b>User Goal 05:</b> El Cliente quiere ver su historial y volver a alquilar un scooter.  
Cuando el Cliente quiera ver su historial, puede acceder a esta opción desde su perfil y ver la lista de todos los scooters que fueron alquilados por uno mismo, también puede volver a alquilar un scooter. Cuenta con la opción de cancelar las operaciones.  
![UF_UserGoal5](https://github.com/user-attachments/assets/4c0efcd2-a931-446f-bae8-bb882ef445db)


<b>User Goal 06:</b> El Cliente quiere eliminar su historial.  
Cuando el Cliente quiera eliminar su historial puede hacerlo dando click a eliminar historial. Cuenta con la opción de cancelar la operación.  
![UF_UserGoal6](https://github.com/user-attachments/assets/dcc7533c-ab7a-4883-9534-7d5ca947be7e)


<b>User Goal 07:</b> El usuario quiere compar, ver, cambiar y cancelar suscripción.  
Cuando el usuario quiere ver su suscripción, se dirigirá a Mi Sucripción y podrá verla, cambiarla y cancelarla. Cuenta con la opción de cancelar las operaciones.  
![UF_UserGoal7](https://github.com/user-attachments/assets/35282287-cdcb-4d62-a3b3-ee9abf45e71e)

## 4.5. Web Applications Prototyping  

Link del prototipo: https://www.figma.com/proto/cQuS3bFffjnBjo9RGwcl2D/Web-Application---MoviRent?node-id=30-7401&node-type=CANVAS&t=Lxw2yVCYl0Cy3vm2-1&scaling=min-zoom&content-scaling=fixed&page-id=0%3A1&starting-point-node-id=30%3A7401&show-proto-sidebar=1 
## 4.6. Domain-Driven Software Architecture
### 4.6.1. Software Architecture Context Diagram

<img src="/assets/chapter-04/DataBase/DiagramaC4-Context.png"/>

### 4.6.2. Software Architecture Container Diagrams.

<img src="/assets/chapter-04/DataBase/C4-DiagramContainer..png"/>

### 4.6.3. Software Architecture Components Diagrams
## 4.7. Software Object-Oriented Design
### 4.7.1. Class Diagrams

<img src="/assets/chapter-04/Diagram/Diagram.png"/>

### 4.7.2. Class Dictionary

<table>
	<tbody>
		<tr>
			<td>Clase</td>
			<td>Descripción</td>
			<td>Tipo de dato</td>
		</tr>
		<tr>
			<td rowspan="3">Owner</td>
			<td>publicarScooter(): Permitirá al Owner publicar su vehiculo en el sistema</td>
			<td>Void</td>
		</tr>
		<tr>
			<td>editarScooter(): Permitirá poder editar el vehículo agregado</td>
			<td>Void</td>
		</tr>
		<tr>
			<td>eliminarScooter(): Le permitirá al Owner eliminar su vehículo del sistema</td>
			<td>Void</td>
		</tr>
		<tr>
			<td rowspan="3">Historial</td>
			<td>id: Es la identificación personal del historial para cada usuario</td>
			<td>Int</td>
		</tr>
		<tr>
			<td>visualizarHistorial(): Permitirá a los usuarios poder visualizar su historial</td>
			<td>Void</td>
		</tr>
		<tr>
			<td>fecha: Mostrará a los usuarios las fechas de cada interacción que tuvieron en el sistema</td>
			<td>Date</td>
		</tr>
		<tr>
			<td rowspan="3">Calificacion</td>
			<td>id: Es el identificador de cada calificación brindada por los usuarios</td>
			<td>Int</td>
		</tr>
		<tr>
			<td>calificar(): Mostrará a los usuarios las calificaciones que tiene cada vehículo que haya sido utilizado por otros usuarios</td>
			<td>Void</td>
		</tr>
		<tr>
			<td>comentario: Permitirá a los usuarios dejar sus comentarios de satisfacción al haber utilizado algún vehículo</td>
			<td>String</td>
		</tr>
		<tr>
			<td rowspan="4">Plan</td>
			<td>id: Es el identificador de cada plan de suscripción</td>
			<td>Int</td>
		</tr>
		<tr>
			<td>precio: Muestra los precios de cada plan de suscripción</td>
			<td>Double</td>
		</tr>
		<tr>
			<td>beneficios: Brinda la información de los beneficios que contiene cada plan</td>
			<td>String</td>
		</tr>
		<tr>
			<td>cancelarSuscripcion(): Permitirá a los usuarios cancelar el plan de suscripción cuando lo deseen</td>
			<td>Void</td>
		</tr>
		<tr>
			<td rowspan="4">Reserva</td>
			<td>id: Identificador de cada reserva realizada por el usuario</td>
			<td>Int</td>
		</tr>
		<tr>
			<td>solicitarReserva(): Permitirá a los usuarios el poder realizar una reserva por un vehículo</td>
			<td>Void</td>
		</tr>
		<tr>
			<td>estado: Mostrará al usuario si la reserva fue realizada exitosamente</td>
			<td>String</td>
		</tr>
		<tr>
			<td>devolverScooter(): Permitirá al usuario poder devolver un vehículo al finalizar un alquiler</td>
			<td>Void</td>
		</tr>
		<tr>
			<td rowspan="4">Cliente</td>
			<td>buscarScooters(): Mostrará a los usuarios una lista de vehículos con detalles técnicos específicos y precios de alquiler</td>
			<td>Lista</td>
		</tr>
		<tr>
			<td>alquilarScooter: Permitirá a los usuarios el poder alquilar un vehículo brindando algunos datos</td>
			<td>Void</td>
		</tr>
		<tr>
			<td>calificarScooter(): El usuario podrá dejar calificaciones para cada vehículo que haya utilizado</td>
			<td>Void</td>
		</tr>
		<tr>
			<td>visualizarHistorial(): El usuario podrá visualizar su historial de alquiler</td>
			<td>Void</td>
		</tr>
		<tr>
			<td rowspan="5">Usuario</td>
			<td>id: Es el indentificador único del usuario</td>
			<td>Int</td>
		</tr>
		<tr>
			<td>nombre: Es el nombre del usuario</td>
			<td>String</td>
		</tr>
		<tr>
			<td>correo: Dirección de correo electrónico del usuario</td>
			<td>String</td>
		</tr>
		<tr>
			<td>contraseña: Es la contraseña del usuario para acceder al sistema</td>
			<td>String</td>
		</tr>
		<tr>
			<td>tipo: Se encarga de identificar al tipo de usuario</td>
			<td>String</td>
		</tr>
		<tr>
			<td rowspan="7">Vehiculo</td>
			<td>id: Identificador para cada vehículo añadido al sistema</td>
			<td>Int</td>
		</tr>
		<tr>
			<td>tipoVehiculo: Menciona el tipo de vehículo añadido al sistema</td>
			<td>String</td>
		</tr>
		<tr>
			<td>marca: Es la marca de fabricante que tendrá cada tipo de vehículo</td>
			<td>String</td>
		</tr>
		<tr>
			<td>modelo: Es el modelo que tendra cada tipo de vehiculo</td>
			<td>String</td>
		</tr>
		<tr>
			<td>año: Menciona el año de fabricación de cada modelo de vehículo</td>
			<td>Int</td>
		</tr>
		<tr>
			<td>estado: Menciona el estado de disponibilidad del vehículo</td>
			<td>String</td>
		</tr>
		<tr>
			<td>tarifa: Mostrará el precio de alquiler de cada vehículo</td>
			<td>Double</td>
		</tr>
	</tbody>
</table>

## 4.8. Database Design
### 4.8.1. Database Diagram
Para desarrollar la estructura de diagrama de base de datos usamos la herramienta de Vertabelo. A continuación, muestra las tabla de diseño de base de datos.

![DatabaseDiagram](https://github.com/user-attachments/assets/b8f690f2-babf-4e25-ab85-86626d7d8dfb)


---
