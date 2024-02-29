# Proyecto web 01
Sitio web que muestra y describe la información de los servicios que ofrece una iglesia

Sitio web creado con las siguientes herramientas a nivel de front-end y back-end:

- **HTML:**	Permite crear la estructura del sitio web mediante etiquetas
- **CSS:**	Para definir y crear la presentación o estética del sitio web
- **JavaScript:**	Añade características que permite agregar e implementar acciones interactivas al sitio web
- **PHP:**	Favorece la conexión entre los servidores y la interfaz de usuario

Este sitio web fue creado y desarrollado usando la plataforma **NetBeans 12.0.** Además está adaptado para ejecutarse en dispositivos móviles.

El archivo **index.php** es el que contiene la página de inicio o página principal del sitio web.

La página de inicio o principal consta de tres secciones: 
- **Un encabezado:**	donde se muestra el logotipo de la organización
- **Una sección principal:**	integra los contenidos más relevantes de presentación de la organización 
- **Un pie de página:** 	muestra la información de contacto de la organización

El menú principal consta de cuatro opciones: 
- **Quienes somos:**	muestra la información que define la identidad de la organización. Integra un submenú con seis opciones adicionales, las cuales describen aspectos tales como la visión, la misión, los valores, entre otros, de la organización
- **Reflexiones:**	página dedicada a publicar artículos, noticias, mensajes y/o reflexiones con contenido bíblico
- **Actividades:**	muestra las actividades que va a realizar la organización durante el mes en curso; así como las actividades que se van a realizar en fechas posteriores 
- **Contáctenos:**	consta de dos secciones: un formulario de contacto para que la persona pueda ponerse en contacto con la organización y un mapa que muestra la ubicación junto con datos adicionales de contacto

En cada archivo de estilos CSS se utiliza la técnica de rejilla **CSS Grid Layout** para organizar de manera más eficiente cada elemento de la interfaz del sitio web, el cual los acomoda tanto a lo largo como a lo ancho de la ventana del navegador. Además, es complementado con **Flexbox**, el cual ayuda a distribuir el espacio entre los ítems de la interfaz y mejora las capacidades de alineación de cada elemento en filas o columnas.

Para el formulario de contacto se programaron validaciones tanto del lado del cliente utilizando JavaScript; así como del lado del servidor programado con PHP.

Para enviar la información del usuario a través del formulario de contacto se utiliza una herramienta  llamada **PHPMailer.** Esta es una clase escrita con php para enviar emails basada en el componente active server ASPMail. Permite de una forma sencilla tareas complejas como por ejemplo:
- Enviar mensajes de correo con ficheros adjuntos (attachments) 
- Enviar mensajes de correo en formato HTML 
- Enviar emails via sendmail, PHP mail(), o con SMTP.

Finalmente, se utiliza una librería JavaScript llamada **SweetAlert2** para mostrar al usuario mensajes personalizados que le van a indicar si los datos digitados por el cliente fueron enviados al buzón de correo del restaurante de  correcta o incorrecta.

A continuación se presentan algunas imágenes del sitio web brevemente descrito anteriormente:

![01  Inicio_1](https://github.com/misproyectosweb/proyecto-web-01/assets/98922137/8e00f6ee-9593-4ab2-8872-681fc7fffba2)
**==========================================================================**
**==========================================================================**
![01  Inicio_2](https://github.com/misproyectosweb/proyecto-web-01/assets/98922137/8131ebf5-92c1-45fc-93a8-90d5022f3f6b)
**==========================================================================**
**==========================================================================**
![01  Inicio_3](https://github.com/misproyectosweb/proyecto-web-01/assets/98922137/b87a3ef3-4873-46d3-a3d9-47e1e3df967f)
**==========================================================================**
**==========================================================================**
![02  quienessomos_1](https://github.com/misproyectosweb/proyecto-web-01/assets/98922137/01a4d711-7fb6-48ac-ae2d-68f6675a1b96)
**==========================================================================**
![02  quienessomos_2](https://github.com/misproyectosweb/proyecto-web-01/assets/98922137/f5edc11d-34e2-49b5-a95e-30861f4a2129)
**==========================================================================**
![02  quienessomos_3](https://github.com/misproyectosweb/proyecto-web-01/assets/98922137/19fbf68b-f9fa-4b2d-9f2b-da92c47e7c3f)
**==========================================================================**
![02  quienessomos_4](https://github.com/misproyectosweb/proyecto-web-01/assets/98922137/f740842e-eb51-4054-8ccf-549e8fbbb025)
**==========================================================================**
![02  quienessomos_5](https://github.com/misproyectosweb/proyecto-web-01/assets/98922137/4fb7e605-4acc-444a-8f8d-553a07ee6f56)
**==========================================================================**
![02  quienessomos_6](https://github.com/misproyectosweb/proyecto-web-01/assets/98922137/e46f62ba-a82d-440e-92f2-fcd0bdedf7e1)
**==========================================================================**
![02  quienessomos_7](https://github.com/misproyectosweb/proyecto-web-01/assets/98922137/962077ae-b600-4f5b-a278-4e1269d35387)
**==========================================================================**
![02  quienessomos_8](https://github.com/misproyectosweb/proyecto-web-01/assets/98922137/94d4e7c5-d87e-40b0-b341-1883991c163f)
**==========================================================================**
![02  quienessomos_9](https://github.com/misproyectosweb/proyecto-web-01/assets/98922137/670423e9-4d62-4f4b-ac33-fd25de27d9ec)
**==========================================================================**
![02  quienessomos_10](https://github.com/misproyectosweb/proyecto-web-01/assets/98922137/e372f2bc-7811-4f0f-8de1-7c78b261e5e1)
**==========================================================================**
![02  quienessomos_11](https://github.com/misproyectosweb/proyecto-web-01/assets/98922137/79f642bf-4808-4d36-b150-4820259772a7)
**==========================================================================**
![02  quienessomos_12](https://github.com/misproyectosweb/proyecto-web-01/assets/98922137/2534c5a5-f88c-4293-bb57-c0c064b5a872)
**==========================================================================**
![03  Reflexión_1](https://github.com/misproyectosweb/proyecto-web-01/assets/98922137/64c6240d-e972-4f41-863f-11b81ac877b9)
**==========================================================================**
![03  Reflexión_2](https://github.com/misproyectosweb/proyecto-web-01/assets/98922137/b4c6cc39-4762-4a51-a8f3-b3e63c457083)
**==========================================================================**
![03  Reflexión_3](https://github.com/misproyectosweb/proyecto-web-01/assets/98922137/95b10a53-deab-435d-9b7e-888341ed21e4)
**==========================================================================**
![04  Actividades_1](https://github.com/misproyectosweb/proyecto-web-01/assets/98922137/e070bf70-cfbf-4d8a-9dba-252b67bad29a)
**==========================================================================**
![04  Actividades_2](https://github.com/misproyectosweb/proyecto-web-01/assets/98922137/d4ab791d-60cf-45fd-8c2f-7394388e38a8)
**==========================================================================**
![04  Actividades_3](https://github.com/misproyectosweb/proyecto-web-01/assets/98922137/9d40294d-b001-4d98-991e-b20a872a3e0b)
**==========================================================================**
![04  Actividades_4](https://github.com/misproyectosweb/proyecto-web-01/assets/98922137/5e877dcb-7de3-4894-9f1c-5287e8ad4f00)
**==========================================================================**
![05  Contacto_1](https://github.com/misproyectosweb/proyecto-web-01/assets/98922137/3317b804-b379-48de-9cd0-4bacf2af128e)
**==========================================================================**
![05  Contacto_2](https://github.com/misproyectosweb/proyecto-web-01/assets/98922137/a51c35a7-66a8-40b7-99a7-022871aeba3b)
**==========================================================================**
![05  Contacto_3](https://github.com/misproyectosweb/proyecto-web-01/assets/98922137/e6ad1da4-8cfd-4f94-960c-eb1b122008cd)
**==========================================================================**
![05  Contacto_4](https://github.com/misproyectosweb/proyecto-web-01/assets/98922137/3910ea59-7b7c-43dc-9e5a-f226e82eeb6a)
**==========================================================================**
![05  Contacto_5](https://github.com/misproyectosweb/proyecto-web-01/assets/98922137/9287bae9-1831-4092-b5d0-fc5e2e71e3a0)
**==========================================================================**
![05  Contacto_6](https://github.com/misproyectosweb/proyecto-web-01/assets/98922137/c9f2cda5-0262-4055-aaca-73ee91e512de)
**==========================================================================**
![05  Contacto_7](https://github.com/misproyectosweb/proyecto-web-01/assets/98922137/65bf947d-19be-464e-b347-0eb39ea9f2e4)





























