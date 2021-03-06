
## Ej1. FLEX (**2 pts**)

Realizar los cambios necesarios en el código fuente en la carpeta [ej01_flex](ej01_flex) para crear un componente de barra lateral reutilizable con un menú de navegación por los datos de un perfil de redes sociales como el siguiente:

![sidebar](../imgs/sidebar.png)

Aspectos a tener en cuenta:
  - El maquetado del componente barra lateral contiene 3 elementos principales:
      - marcador de posición para el logo SIDEBAR
      - bloque de navegación (Home, About me…) con iconos de Fontawesome
      - bloque de perfil de usuario, que contiene la imagen del perfil
  - La barra lateral ocupará el 100% de la altura disponible hasta un máximo de 500px.
  - Utilizar flexbox para alinear los 3 elementos de la barra lateral como se ve en la imagen 1
  - El bloque de navegación ocupará todo el espacio disponible de la barra lateral, de manera que la imagen de perfil se ubicará al final de la barra.
  - El logo y el bloque de perfil de usuario estarán centrados.
  - Redondear la imagen de perfil


## Ej2. GRID y MQ (**2 pts**)

Partiendo del código fuente en la carpeta [ej02_gridMQ](ej02_gridMQ)podemos redefinir con grid la posición de los elementos usando también Media Queries.
Definir las siguientes áreas de cuadrícula por defecto (aplicando el principio Mobile First) 

![ej02_MF](../imgs/ej02_MF.png)

A continuación, redefine las áreas de cuadrícula y la posición de los elementos en esa cuadrícula con consultas de medios según las siguientes especificaciones:

Para anchura entre 500 y 600px: (la barra lateral ocupa un 20% anchura disponible)


![ej02_inter](../imgs/ej02_inter.png)

Para anchura superior a 600px: (anchura de barras laterales 120px cada una, separación entre celdas 20px

![ej02_DF](../imgs/ej02_DF.png)


## Ej3. DE FLEX A GRID (**2 pts**)

En la carpeta [ej03_flexbox_grid](ej03_flexbox_grid) tienes el layout de una página implementado con FlexBox.
Consiste básicamente en un header con varios links, una sección principal, un sidebar y un footer, todos dentro de un contenedor.
El ejercicio consiste en usar Grid en lugar de Flex para conseguir el mismo layout.
Tened en cuenta lo siguiente:
  - Usar grid-areas
  - Mantener la misma alineación para los elementos del header:
     - lista de navegación justificada al principio
	 - botón justificado al final
	 - para alinear los items de la lista tendrás que crear otro grid
  - Mantener el comportamiento "responsive" de la web:
     - con una mediaquery con un breakpoint en 660px
	 

	 
## Ej4. DISEÑO LÍQUIDO (**2 pt**)

A partir de la página web que se te proporciona en [ej04_Diseño_liquido](ej04_Diseño_liquido), debes escribir las reglas CSS necesarias para lograr una página web que tenga el mismo aspecto que la siguiente imagen:

![ejerc3](../imgs/ejerc3.png)

Las características del diseño de esta página son:
  - Un diseño centrado con un ancho del 80%.
  - El encabezado de nivel 1 centrado.
  - El contenido principal de la página se organiza en dos columnas, una de 25% de ancho y la otra el espacio restante de 75%.
  - La lista que explica el contenido del libro se muestra como un texto a tres columnas del mismo ancho.
  Puedes modificar el código HTML proporcionado para añadir los identificadores y clases que necesites.
  También puedes añadir etiquetas <div> para definir elementos contenedores en la página.




## Ej5. DISEÑO ELÁSTICO (**2 pts**)


A partir de la página web que se te proporciona en [ej05_Diseño_elastico](ej05_Diseño_elastico), debes escribir las reglas CSS necesarias para lograr una página web que tenga el mismo aspecto que la siguiente imagen:

![ejerc4](../imgs/ejerc4.png)

Las características del diseño de esta página son:

  - Un diseño elástico centrado con un ancho de 60 em.
  - El encabezado de nivel 1 centrado.
  - El contenido principal de la página se organiza en dos columnas, una de 16 em de ancho y la otra el espacio restante de 44 em.
  - La lista que explica el contenido del libro se muestra como un texto a tres columnas del mismo ancho.
	

Puedes modificar el código HTML proporcionado para añadir los identificadores y clases que necesites. También puedes añadir etiquetas ``<div>`` para definir elementos contenedores en la página.
