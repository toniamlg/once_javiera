#  Decisiones semánticas

Para mi tarjeta de presentación digital utilicé estas etiquetas semánticas:

**header**
Este lo utilicé para el encabezado, es la presentación principal del sitio. Dentro de esta se puede notar un **strong** del cual hice uso para resaltar y darle una importancia a unas palabras.

**main**
La utilicé para demostrar que era el contenido central. Se puede ver que tengo dos etiquetas más: **section**, que me ayuda agrupando contenido relacionado y también **time**, buena para las fechas.

**ul** 
La usé para una lista desordenada para mis habilidades.

**ol**
La usé para una lista ordenada, como en una secuencia.

**li**
Se encuentra en las dos anteriores, ésta define cada punto en una lista. 

**footer**
Ya este es el final de la página, se puede notar una etiqueta **address** que la usé para dar información sobre el autor (o sea, yo).

**h1**
El tema central.

**h2** y **h3**
Estos organizan la información por niveles.


# Árbol DOM 

html 
 head 
    —title
    —/title
 /head 
 
body
  header
        h1 
        h/ 
        p
        /p
  /header 

   main
       section 
                h2
                /h2
                 p
                 /p

                 time
                 /time 
         /section

     section 
             h2 
             /h2
          
              h3
              /h3 
                 ul 
                     li
                    /li
                 /ul 
              h3 
              /h3 
                   ol
                       li
                       /li 
                   /ol 
      /section 

 /main 
      footer 
           address 
                  p
                 /p
       /footer 
           body 
    /html

