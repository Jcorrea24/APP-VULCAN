Proyecto-Vulcan

En codigo que estamos construyendo en esta repositorio, vamos a tener desarrollado nuestro proyecto integreador. Inicialmente vamos a estar desarrolando unicamente con HTML y CCS.

Características:

Desarrollado inicialmente solo con HTML y CSS Se aplican estructuras semanticas utilizando correctamente las etiquetas HTML5 Se destaca el uso de la metologia BEM para nombrar clases en CCS. Organizacion de arhivos y carpetas modulares para llevar buenas practicas.

Estructura del Proyecto Version 1.0

Páginas Desarrolladas en la version 1.0

Inicio (index.html): Página principal con secciones de hero, características y llamada a la acción. Acerca de (about.html): Información sobre la empresa, historia, misión, valores y equipo. Servicios (services.html): Descripción de servicios ofrecidos, proceso de trabajo y planes de precios. Contacto (contact.html): Formulario de contacto, información de contacto, mapa y preguntas frecuentes.

Personalización y tipografia:

Tipo de letra: Arial

Paleta de Colores:

:root { 

--color-primary: #F2637E; 
--color-secondary: #41E1F2; 
--color-accent: #F2CB07; 
--color-dark: #D9593D ; 
--color-light: #808C20

 /* ... más variables ... */ }

Link Adobe Color: https://color.adobe.com/es/trends/Game-design

Metodología BEM

Este proyecto utiliza la metodología BEM (Block, Element, Modifier) para nombrar las clases CSS, lo que facilita la comprensión y el mantenimiento del código. Ejemplos:

.header (bloque)

.header__logo (elemento)

.nav__link--active (modificador)
