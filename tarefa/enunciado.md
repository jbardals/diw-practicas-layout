
## Ej1. FLEX (**xxx pts**)

Realizar los cambios necesarios en el código fuente en la carpeta ![ej01_flex](ej01_flex) para crear un componente de barra lateral reutilizable con un menú de navegación por los datos de un perfil de redes sociales como el siguiente:

![sidebar](../imgs/sidebar.png)

Aspectos a tener en cuenta:
    • El maquetado del componente barra lateral contiene 3 elementos principales:
        ◦ marcador de posición para el logo SIDEBAR
        ◦ bloque de navegación (Home, About me…) con iconos de Fontawesome
        ◦ bloque de perfil de usuario, que contiene la imagen del perfil
    • La barra lateral ocupará el 100% de la altura disponible hasta un máximo de 500px.
    • Utilizar flexbox para alinear los 3 elementos de la barra lateral como se ve en la imagen 1
    • El bloque de navegación ocupará todo el espacio disponible de la barra lateral, de manera que la imagen de perfil se ubicará al final de la barra.
    • El logo y el bloque de perfil de usuario estarán centrados.
    • Redondear la imagen de perfil


## Ej2. GRID y MQ (**xxx pts**)

Partiendo del código fuente en la carpeta ![ej02_gridMQ](ej02_gridMQ)
Podemos redefinir con grid la posición de los elementos usando también Media Queries. Definir las siguientes áreas de cuadrícula por defecto (aplicando el principio Mobile First) 

![ej02_MF](../imgs/ej02_MF.png)

A continuación, redefine las áreas de cuadrícula y la posición de los elementos en esa cuadrícula con consultas de medios según las siguientes especificaciones:
Para anchura entre 500 y 600px: (la barra lateral ocupa un 20% anchura disponible)


![ej02_inter](../imgs/ej02_inter.png)

Para anchura superior a 600px: (anchura de barras laterales 120px cada una, separación entre celdas 20px

![ej02_DF](../imgs/ej02_DF.png)



## Ej3. MEDIA QUERIES (**1 pt**)

Dados el siguiente código HTML y CSS en el directorio *media queries*, aplicar los Media Query necesarios para obtener el comportamiento mostrado en las imágenes. 

1) Aspecto de la web a pantalla completa:

![img_pantalla_completa](../imgs/completa.png)

2) Aspecto de la web en una pantalla de 960px:

![img_960](../imgs/960.png)

3) Aspecto de la web en una pantalla de 480px:

![img_480](../imgs/480.png)



## Ej4. ANIMACIONES Y TRANSICIONES (**3 pts**)

Dados el siguiente código HTML y CSS base, aplicar las animaciones y transformaciones necesarias para conseguir el siguiente efecto:   

- Al cargarse la página, inicialmente sólo se mostrarán los recuadros con las imágenes, ocultando el título, texto, enlace a "Leer más" y el fondo naranja.
- A continuación: 
  - La imagen de fondo aumentará su tamaño, dando la impresión de que se acerca. 
  - Se mostrará el fondo naranja, de manera progresiva. 
  - El título aparecerá por la parte superior de la imagen, hasta colocarse en su lugar. 
  - El párrafo aparecerá por la parte inferior de la imagen, hasta colocarse en su lugar. 
  - Se mostrará el enlace "Leer más", de manera progresiva. 
  
Comprueba que el resultado sea el [siguiente](https://drive.google.com/file/d/13j_ma6TLnBFAG3wDHtXFC7JAYxR1yfR9/view?usp=sharing)

