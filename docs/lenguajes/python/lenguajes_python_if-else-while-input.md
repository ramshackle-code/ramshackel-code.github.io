---
title: "Comentar, If, Else e input"
date: "2021-07-07"
---

Hola, Bienvenidos de nuevo. Hoy vamos a hablas de las variables y de input.

Como ya hicimos la ultima vez, yo te ire guiando paso a paso.

1.Abrir un nuevo programa/archivo de Phyton, en nuestro IDE. Hoy se llamara "Test"

2.A continuación escribiremos esto:

`pregunta1 = input ("¿Cuándo colgó piscina de Entropia su primera entrada?")`

Explicación: En realidad se podría poner solo la primera parte, pero entonces el usuario no se enteraría de qué le están haciendo una pregunta. El texto es personalizadle eres libre de cambiarlo... pero recuerda no borrar los paréntesis ni las comillas.

3.Lo que haremos ahora es bajar lo que hemos escrito en el paso dos, una linea. Lo haremos para poder escribir las respuestas entre las que elegirá él usuario.

4\. En el hueco que nos a quedado escribiremos esto:

`#Esta es la respuesta`

Explicación: Tranquilos, esto no lo vera el usuario. Solo lo podrán ver las personas que vean el código, lo que hemos hecho es dejar un comentario. Cosa  que se hace muy a menudo para facilitar la compresión de nuestro código a otros  programadores.

5\. Lógicamente debajo de este comentario escribiremos la respuesta buena y lo haremos así:

`print ("A. 29/05/21")`

6\. Después escribiremos otro comentario en el que ponga...

`#Esta es la Respuesta Mala`

7\. Y ahora procederemos a escribir la respuesta no correcta como...

`print ("B. 5/06/2022")`

\-------PARADA PARA REVISAR EL CODIGO-------

Revisamos que nuestro código este así:

 

```
#Esta es la Respuesta
print ("A. 29/05/21")
#Esta es la Respuesta Mala
print ("B. 5/06/2022")
```

\-------CONTINUAMOS-------

8\. Ahora haremos una breve prueba de nuestro programa, veremos que en el shell se ve cómo ve el texto.(Ya sé que aparece todo de golpe, pero eso lo veremos en otra entrada"). Como veréis, después de la pregunta el programa os dejara escribir pero al darle a intro, no para nada.

9\. Para solucionar eso haremos lo siguiente, debajo de todo lo que habíamos escrito (debajo de input) escribiremos esto:

`if pregunta1 == ("a"): print ("Muy bien eso es correcto")`

Explicación: Lo que hacemos es poner el mensaje que se le dará al usuario cuando acierte.

10\. Aquí haremos lo mismo que antes pero en vez de decirle que es correcto, le diremos lo contrario:

```
if pregunta1 == ("b"):
print ("Eso no es correcto")
```

\-------PARADA PARA REVISAR EL CODIGO-------

Revisamos que nuestro código este así:

```
#Esta es la Respuesta
print ("A. 29/05/21")
```

\-------CONTINUAMOS-------

Ahora al probar el programa, funciona de forma correcta, pero haremos algo mas...

11.Ahora borraremos todo menos esto:

`pregunta1 = input ("¿Cuándo colgó piscina de Entropia su primera entrada?")` 12\. He incluiremos esto debajo de la parte de input:

```
if pregunta1 == ("29/05/21"):
print ("Eso es correcto")
```

\-------PARADA PARA REVISAR EL CODIGO-------

Revisamos que nuestro código este así:

`pregunta1 = input ("¿Cuándo colgó piscina de Entropia su primera entrada?") if pregunta1 == ("29/05/21"): print ("Eso es correcto") else: print ("Eso es incorrecto")`

\-------CONTINUAMOS-------

Al probar el programa veremos que sí le damos la fecha: 29/05/21, pero si le decimos cualquier otra cosa nos dirá que es incorrecto.

**Isaaker.**
