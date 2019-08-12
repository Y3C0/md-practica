# MarkDown

## Encabezados o Títulos

Mediante el carácter almohadilla # podemos crear encabezados
de forma extremadamente sencilla.

Markdown permite crear títulos o encabezados de nivel uno, dos, tres, cuatro,
cinco y seis de forma extremadamente sencilla.

Para crear un encabezado de nivel 1 escribimos una almohadilla # seguido de un
espacio y el nombre que queremos para el encabezado:

###### *Ejemplo:*

```MarkDown
# Titulo 1
## Titulo 2
### Titulo 3
#### Titulo 4
##### Titulo 5
###### Titulo 6
```
###### *Resultado:*

# Titulo 1
## Titulo 2
### Titulo 3
#### Titulo 4
##### Titulo 5
###### Titulo 6

---

## Citar

Para incluir una cita tenemos que usar el símbolo > seguido de un espacio antes
del texto que queremos citar. Por lo tanto, si quiero citar
un comentario y replicarlo deberíamos usar el siguiente código:

###### *Ejemplo:*

```MarkDown
> Linux es el sistema operativo mas chingon!!

Total mente de acuerdo!!
```

###### *Resultado:*

> Linux es el sistema operativo mas chingon!!

Total mente de acuerdo!!

---

## Listas

### Listas desordenadas

Mediante el símbolo * o – podemos crear listas.

###### *Ejemplo:*

```MarkDown
* Lunes
- Martes
* Miércoles
- Jueves
* Viernes
```
###### *Resultado:*

* Lunes
- Martes
* Miércoles
- Jueves
* Viernes

---

### Listas Ordenadas

Para obtener listados ordenados numéricamente tenemos que escribir un
número seguido de un punto y un espacio antes de comenzar a escribir


###### *Ejemplo:*

```MarkDown
1. Positivo
2. Negativo
3. Neutro
```

###### *Resultado:*

1. Positivo
2. Negativo
3. Neutro

---

## Anidar Listas

Para anidar una lista tan solo tenemos que incluir un espacio presionando la
tecla Tab (Tabulador).

###### *Ejemplo:*

```MarkDown
- Lunes
  1. Mañana
  2. Tarde
  3. Noche

- Martes
  1. Mañana
  2. Tarde
  3. Noche
```
###### *Resultado:*

- lunes
   1. Mañana
   2. Tarde
   3. Noche
- Martes
   1. Mañana
   2. Tarde
   3. Noche

---

## Separaciones Físicas entre secciones de texto

Entre dos secciones de texto podemos incluir una separación física. Para ello
tenemos que escribir 3 guiones bajos seguidos ___

###### *Ejemplo:*

```MarkDown
Este parrafo es de prueba para mostrar la separación de texto por medio de ___ tres guiones
---
Este es otro párrafo agregado para el ejemplo de Separaciones físicas entre secciones de texto
```

###### *Resultado:*

>Este parrafo es de prueba para mostrar la separación de texto por medio de ___ tres guiones
>
>---
>
> Este es otro párrafo agregado para el ejemplo de Separaciones físicas entre secciones de texto

---

## Estilos al texto

Podemos definir que un texto esté en negrita, cursiva o tachado. Para ello tendremos que utilizar el siguiente código:

| Formato | Código | Resultado |
| --- | --- | --- |
| Negrita | ```**Negrita**``` | **Negrita** |
| Cursiva | ```*Cursiva*``` | *Cursiva* |
| Tachado | ```~~Tachado~~``` | ~~Tachado~~ |
| Negrita + Cursiva | ```***Palabra``` | ***Palabra*** |
| Tachado + Negrita + Cursiva | ```~~**palabra**~~``` | ~~**Palabra**~~ |

---

## Insertar enlaces de texto o descarga

Para incluir enlaces en un texto tenemos que utilizar el siguiente tipo de sintaxis:

```MarkDown
[texto_de_ancla](URL_que_queremos_enlazar_o_enlace_de_descarga)
```
###### *Ejemplo:*

```MarkDown
[Sigueme!!](https://www.facebook.com/yeco13)
```
###### *Resultado:*

[Sigueme!!](https://www.facebook.com/yeco13)

También se puede añadir un título al enlace con la
siguiente sintaxis:

```MarkDown
[texto_de_ancla](URL_que_queremos_enlazar) titulo_del_enlace
```

###### *Resultado:*

[Sigueme!!](https://www.facebook.com/yeco13) Sergio

Ademas puedes agregan tooltype

```MarkDown
[texto_de_ancla](URL_que_queremos_enlazar ”Contenido tooltype”) titulo_del_enlace
```

###### *Resultado:*

[Sigueme!!](https://www.facebook.com/yeco13/”Y3C0”) Sergio Diaz

---

## Insertar Imágenes

El método para insertar imágenes es similar al método para insertar enlaces. La sintaxis es la misma y lo único que tenemos que modificar es:

1. Reemplazar el texto de ancla por el texto alternativo de la imagen.
2. Añadir el símbolo ! al principio de la sintaxis.

###### *Ejemplo:*

```MarkDown
![texto_alternativo_imagen](URL_imagen)
```

###### *Resultado:*

![Yo amo MarkDown](http://mikemclin.net/mmwp/wp-content/uploads/2013/03/markdown-syntax-language.png)

>Nota: La url puede ser una dirección local o una dirección que apunte a una imagen alojada en un servidor web.

### Insertar Imágenes con tooltype

```MarkDown
![texto_alternativo_imagen](URL_imagen "Texto tooltype")
```

###### *Resultado:*

![Yo amo MarkDown](http://mikemclin.net/mmwp/wp-content/uploads/2013/03/markdown-syntax-language.png "MarkDown es lo mejor!!")

La imagen siempre se insertará en tamaño real. Si la queremos redimensionar lo deberemos hacer en función del editor de markdown que usemos. Muchos editores de Markdown permitirán redimensionar las imágenes mediante código html.

### Simplificar la creación de enlaces e inserción de imágenes

Escribiremos un texto y cada vez que aparezca una palabra que queramos enlazar la pondremos entre corchetes:

```MarkDown
[Enlace] Espacio para comentarios sobre el enlace
```

Una vez finalizado el texto, al final del documento definiremos los enlaces del siguiente modo:

```MarkDown
[Enlace]: http://www.my-enlace.com
```

###### *Ejemplo:*

[Zaid Oigres] Pagina Personal de Sergio Diaz

[Zaid Oigres]: https://www.facebook.com/yeco13/

### Insertar imágenes de forma simple y ordenada

Si tenemos que insertar una imagen en varias partes del documento podemos escribir simplemente el texto alternativo de la imagen del siguiente modo:

```MarkDown
![insertando imágenes]
```
###### *Resultado:*

![insertando imágenes]

Al final del documento definiremos la URL de la imagen del siguiente modo:

```MarkDown
[insertando imágenes]: https://upload.wikimedia.org/wikipedia/commons/thumb/5/51/Octicons-markdown.svg/1024px-Octicons-markdown.svg.png
```

[insertando imágenes]: https://upload.wikimedia.org/wikipedia/commons/thumb/5/51/Octicons-markdown.svg/1024px-Octicons-markdown.svg.png

---

## Insertar cajas de código

Markdown permite incluir cajetines de código en cualquier lenguaje de programación. Para ello tan solo tenemos que seguir el siguiente procedimiento:

1. Antes de iniciar el código escribimos tres acentos abiertos  ``` ` ` ` ``` seguido del nombre del lenguaje que queremos insertar en el cajetín.

2. Presionamos enter y escribimos el código.

3. Para cerrar el cajetín volveremos a escribir tres acentos abiertos ``` ` ` ` ``` .

###### *Ejemplo:*

```html
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>Hola Mundo</title>
  </head>
  <body>
    <h1>Hola Mundo!!</h1>
  </body>
</html>
```

### Resaltar código dentro de un texto párrafo

Para resaltar código dentro de una frase tenemos que usar el símbolo de acento grave o abierto `. Por lo tanto, para resaltar código tan solo tengo que poner entre acentos graves

###### *Ejemplo:*

El comando para buscar actualizaciones para distribuciones basadas en debian es: `apt update`,

Comando para listar las actualizaciones disponibles: `apt list --upgradable`

Comando para actualizar las aplicaciones: `apt upgrade`

 ---

## Listas de Tareas o CheckList

Markdown nos permite crear listas de tareas de forma extremadamente sencilla.
Para ello tan solo tenemos que abrir corchete, dejar un espacio y cerrar el
corchete:

> [ ]

En el caso que queramos marcar la tarea como realizada tenemos que
reemplazar el espacio por una X del siguiente modo:

> [X]

###### *Ejemplo:*

**Lista de super**

- [ ] 1 lt Leche
- [ ] 5 pz Pagina
- [X] 2 kg Tortillas
- [X] 3 kg Naranja
- [ ] 1 Lechuga

---

## Tablas

Para generar tablas en Markdown usaremos los siguientes símbolos:

1. |
2. :
3. -

El primer paso para crear una tabla consiste en definir los títulos de las
columnas. Para ello escribiremos los títulos de las Política columnas
separados por tuberías | tal y como se muestra en el siguiente ejemplo:

> | Dia | Mes | Ano |

Acto seguido repetiremos la línea que acabamos de escribir sustituyendo los
títulos de las columnas por —

> | --- | --- | --- |

En estos momentos hemos generado una tabla que tiene 3 columnas y una fila
que con los títulos de las columnas. Finalmente añadiremos el resto de filas de la
misma forma que añadimos las columnas:

> | 15 | Abril | 1990 |
>
> | 20 | Mayo | 2018 |
>
> | 31 | Diciembre | 1980 |

###### *Resultado:*

| Día | Mes | Ano |
| --- | --- | --- |
| 15 | Abril | 1990 |
| 20 | Mayo | 2018 |
| 31 | Diciembre | 1980 |

Con este simple código habremos generado una tabla. Si además queremos
justificar a la derecha el contenido de la columna 2 y centrar todo el texto de la columna 3, lo haremos usando el símbolo : en la segunda fila del código Markdown:

| Día | Mes | Ano |
| --- | ---: | :---: |
| 15 | Abril | 1990 |
| 20 | Mayo | 2018 |
| 31 | Diciembre | 1980 |

---

## Insertar comentarios o notas al pie de la pagina

Para insertar una nota al pie de página lo haremos del siguiente modo.:
1. Justo después de la palabra que queremos añadir una nota al pie de página
escribiremos un corchete [
2. Acto seguido escribimos un acento circunflejo ^
3. A continuación escribimos una palabra sin espacios que describa el tipo de
comentario que pondremos al pie de página
4. El siguiente paso consistirá en cerrar el corchete ].
5. Seguidamente, en cualquier parte del documento reproducimos los mismos
caracteres realizados en las pasos 1,2.3 y 4. A continuación escribimos el
carácter : y finalmente escribimos la nota que queremos poner al pie de
página.

###### *Ejemplo:*

```
El inventor que cambio el mundo como lo conocemos fue Tesla[^1]. El y sus investos hicieron que el mundo prosperara.

---

[^1]: Nicola Tesla el inventor que revoluciono el mundo
```

###### *Resultado:*

El inventor que cambio el mundo como lo conocemos fue Tesla[^1]. El y sus inventos hicieron que el mundo prosperara.

---

[^1]: Nicola Tesla el inventor que revoluciono el mundo

---

## Abreviaciones de palabras

En muchas ocasiones escribimos abreviaciones o palabras que necesitan una
breve definición.
Si queremos definir la abreviación TAS, en cualquier parte del documento
hacemos lo siguiente:
1. Escribimos un *
2. Abrimos corchetes [
3. Escribimos la abreviación de palabra a definir.
4. Cerramos corchetes ] y acto seguido escribimos :
5. Finalmente dejamos un espacio y escribimos la definición de la abreviación.

###### *Ejemplo:*

```
El IMSS trabaja para todos los Mexicanos

*[IMSS]: Instituto Mexicano del Seguro Social

A partir de estos momentos siempre que escribamos IMSS tendremos
```

###### *Resultado:*

El IMSS trabaja para todos los Mexicanos

*[IMSS]: Instituto Mexicano del Seguro Social

----

## Definir palabras

1. Escribimos la palabra a definir y presionamos la tecla Enter.
2. Acto seguido escribimos :, dejamos un espacio y empezamos a escribir la definición de la palabra.

###### *Ejemplo:*

```
MarkDown
: Es un lenguaje de marcado
```

###### *Resultado:*

MarkDown
: Es un lenguaje de marcado

---

## Anular Codigo

Para anular el código Markdown tendremos que usar el carácter \.

###### *Ejemplo:*


```
*Palabra de ejemplo*

\*Palabra de ejemplo*
```

###### *Resultado:*

*Palabra de ejemplo*

\*Palabra de ejemplo*

---

## Insertar Videos

#### Para usuarios de Markdown Editor en Nextcloud

Si en Nextcloud usan Markdown Editor tan solo tienen que realizar lo siguiente:

1. Escriben el símbolo de admiración !.
2. Acto seguido abren corchetes [ y escriben el nombre del servicio en que está alojado el vídeo.
3. Cierren corchetes ]. Finalmente, entre paréntesis peguen la URL del vídeo que quieren insertar.

###### *ejemplo:*

```
![youtube](https://www.youtube.com/watch?v=Mh0Of4LzEfk)
![vimeo](https://vimeo.com/76979871)
```

###### *Resiltado:*

![youtube](https://www.youtube.com/watch?v=Mh0Of4LzEfk)
![vimeo](https://vimeo.com/76979871)

Para visualizar los videos tan solo tendremos que clicar sobre el icono Play.

#### Insertar vídeos en el caso que su editor de Markdown acepte código html

En los editores de Markdown que acepten html tan solo tendremos que usar el link de inserción que proporcionan servicios como Youtube, Vimeo o DailyMotion para insertar los vídeos en las web.

Para obtener el link de Youtube que nos permitirá insertar un vídeo determinado lo haremos del siguiente modo.

1. Empezamos a reproducir el vídeo que queremos insertar.
2. Encima del vídeo presionamos el botón izquierdo del ratón y cuando aparezca el menú contextual clicamos encima de la opción Copiar código de inserción.
3. Nos vamos a nuestro editor de Markdown y pegamos el contenido del portapapeles. De este modo tan sencillo podremos insertar vídeos los servicios de vídeo online más populares

###### *Ejemplo:*

```
<iframe width="744" height="419" src="https://www.youtube.com/embed/HUBNt18RFbo" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
```

###### *Resultado:*

<iframe width="744" height="419" src="https://www.youtube.com/embed/HUBNt18RFbo" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Si desean insertar sonidos de servicios de audio como soundcloud, el procedimiento es el mismo que se muestra en este apartado. Tan solo tienen que buscar el link para insertar el sonido y pegarlo en su editor de Markdown


#### Insertar vídeos en el caso usemos un editor de markdown sin ningún tipo de soporte

En el caso que su editor de markdown no tenga ningún tipo de soporte usaremos la siguiente sintaxis para insertar vídeos:

```
[![texto_alternativo_imagen](url_imagen_que_representará_el_video)](url_del_vídeo_que_queremos_insertar)
```

###### *Ejemplo:*

```
[![MARKDOW](https://upload.wikimedia.org/wikipedia/commons/thumb/5/51/Octicons-markdown.svg/1024px-Octicons-markdown.svg.png)](https://www.youtube.com/watch?time_continue=3&v=y6XdzBNC0_0)
```
###### * Resultado:*

[![MARKDOW](https://upload.wikimedia.org/wikipedia/commons/thumb/5/51/Octicons-markdown.svg/1024px-Octicons-markdown.svg.png)](https://www.youtube.com/watch?time_continue=3&v=y6XdzBNC0_0)

---
